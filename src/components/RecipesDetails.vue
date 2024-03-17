<script setup>

</script>

<template>
  <div id="container">
    <div class="card">
      <img class="card-img" src="/src/assets/img/home/cuchara.jpg" alt="">
      <h2>Fabada Asturiana</h2>
    </div>
    <div class="recipe">
        <p>Ingredientes para 8 personas<br />
          1 kg. de fabes de La Granja<br />
          3 chorizos asturianos<br />
          3 morcillas asturianas<br />
          500 gr. de lacón</br>
          150 gr. de tocino ibérico<br />
          1 ajo<br />
          1 cebolla<br />
          1 cucharada sopera de aceite de oliva<br />
          Azafrán<br />
          Pimentón dulce de buena calidad</br>
          Preparación<br />
          - Ponemos las fabes a remojo con agua y una cucharada de aceite durante mínimo 8 horas.<br />
          - Dejamos el lacón a desalar en un recipiente con agua durante el tiempo que estén en remojo las fabes. Cambiamos el agua una vez, cuando lleven 3 ó 4 horas.<br />
          - En una olla grande, tened en cuenta que las fabes van a aumentar de volumen, ponemos todos lo ingredientes: las fabes, la cebolla partida a la mitad, el ajo en trozos, los chorizos, las morcillas, el lacón, el tocino y el perejil. Cubrimos con agua fría y dejamos que comience a cocer lentamente.<br />
          - Una vez que comienza a hervir, se quita la espuma que aparece en la superficie y se va echando agua fría, 1/4 de vaso, cada vez que hierba con intensidad. Esto es lo que se llama «asustar les fabes».<br />
          - Dejamos cocer todo junto lentamente durante 2 ó 3 horas, dependiendo de la faba. Habrá que tener cuidado de que no alcancen una cocción alta, ya que deberá ser lenta en todo momento.<br />
          - Cuando la cocción ya esté casi lista, añadimos una cucharada de postre de pimentón dulce y un poco de azafrán tostado. No será necesaria la sal, pero por si acaso probadla y rectificar si lo pide.<br />
</p>
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
    width: 40%;
    padding: 3%;
  
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
  .recipe {
   float: inline-end;
    p {
      font-family: "Montserrat", 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      font-size: 20px;
      color: #333333;
      width: 60%;
      height: 60%;
      text-align: justify;
      border: 2px solid #BEBBBB; 
      border-radius:1.5%;
      padding: 15px;
      margin: 2%;
      
    }

  }
  


}

</style>