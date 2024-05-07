<template>
  <div id="app">
    <div class="container py-5">
      <div class="d-flex justify-content-between">
        <p> Fecha: <span> {{ fecha }}</span></p>
        <p>Lugar: <span> {{ lugar }}</span></p>
      </div>
      <p>En el siguiente contrato se estipula el acuerdo entre <span>{{
        arrendatario }}</span> en su rol de arrendador y <span>{{ arrendatario
          }}</span> como el arrendatario. </p>
      <p>Con fecha de <span>{{ fecha }}</span></p>
      <p>Se acuerda el valor mensual de <span>{{ valorMensual }}</span></p>
    </div>
    <hr class="border border-danger border-2">
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      arrendador: "Elon Musk",
      arrendatario: "Jeff Bezos",
      fecha: "25/09/2025",
      lugar: "Temuco",
      valorMensual: 1600000,
    };
  },
};
</script>

<style  scope>
span { 
  font-weight: bold; 
  text-decoration: underline;
   }
</style>
