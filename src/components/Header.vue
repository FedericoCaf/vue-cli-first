<template>
  <div>
   
     <ul class="d-flex justify-content-center">
       <li>Home</li>
       <li>Prodotti</li>
       <li>Gallery</li>
       <li>Chi siamo</li>
       <li>Contattaci</li>
     </ul>
  
  </div>
</template>

<script>

export default {
 name: 'Header',
}

</script>

<style scoped>

 ul{
   list-style: none;
 }

 ul li{
   font-size: 20px;
   padding-left: 60px;
   cursor: pointer;
 }

</style>