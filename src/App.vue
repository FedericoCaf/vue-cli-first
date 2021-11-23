<template>
  <div class="fc-container text-center">
    <header class="d-flex align-items-center justify-content-center">
      <Header/>
    </header>
    
    <main class="d-flex align-items-center justify-content-center">
      <Title/>
    </main>
    <footer class="d-flex align-items-center justify-content-center">
      <Footer/>
    </footer>
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Title,
    Header,
    Footer,
  }
}
</script>

<style>
 
.fc-container{
  height: 100vh;
  background-color: lightcoral;
}

header{
  height: 100px;
  background-color: lightcyan;
}
footer{
  height: 130px;
  background-color: black;
  color: white;
}

main{
  height: calc(100% - 230px);
  background-color: aquamarine;
}

</style>
