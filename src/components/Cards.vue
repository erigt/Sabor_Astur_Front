<script setup>

</script>

<template>
  <div id="container">
    <div class="card">
      <img class="card-img" src="/src/assets/img/Fabada1 1.png" alt="">
      <h2>Recetas de Cuchara</h2>
    </div>
    <div class="card">
      <img class="card-img" src="/src/assets/img/El-mejor-cachopo-de-Asturias-1920x1280-1.jpg" alt="">
      <h2>Recetas de Carne</h2>
    </div>
    <div class="card">
      <img class="card-img" src="/src/assets/img/VERDINAS-CON-MARISCO.jpg" alt="">
      <h2>Recetas de Pescado</h2>
    </div>
    <div class="card">
      <img class="card-img" src="/src/assets/img/arroz-con-leche-asturiano-receta.jpg" alt="">
      <h2>Recetas de Dulces</h2>
    </div>
      

      
  
  




  </div>





  </template>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Hind+Vadodara:wght@300;400;500;600;700&family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap');

#container { 
  display: flex;
  justify-content: flex-start;
  align-items: center;

  .card {
    width: 20%;
    padding: 2%;
  }
  .card-img {
    width: 100%;
  }

  h2{
    font-family: "Montserrat", 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: #333333;
    text-align: center;
  }


}

</style>