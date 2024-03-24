<script setup>

</script>

<template>
  <div id="container">
    <div class="card">
      <img class="card-img" src="/src/assets/img/home/cuchara.jpg" alt="">
      <h2>Recetas de Cuchara</h2>
    </div>
    <div class="card">
      <img class="card-img" src="/src/assets/img/home/cuchara.jpg" alt="">
      <h2>Recetas de Cuchara</h2>
    </div>
    <div class="card">
      <img class="card-img" src="/src/assets/img/home/cuchara.jpg" alt="">
      <h2>Recetas de Cuchara</h2>
    </div>
    <div class="card">
      <img class="card-img" src="/src/assets/img/home/cuchara.jpg" alt="">
      <h2>Recetas de Cuchara</h2>
    </div>
 
  </div>



  </template>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Hind+Vadodara:wght@300;400;500;600;700&family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap');

#container { 
  display: flex;
  flex-direction:row;
  align-items: center;
 
  

  .card {
    width: 30%;
    padding: 1%;
  
  }
  .card-img {
    width: 100%;
    border-radius: 2%;
  }

  h2{
    font-family: "Montserrat", 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: #333333;
    text-align: center;
  }


}

</style>