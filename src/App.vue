<template>
  <div class="jumbotron jumbotron-fluid">
    <div class="container">
      <h1 class="display-4">Nuestros platos</h1>
      <p class="lead">
        Inicio / Nuestros platos
      </p>
    </div>
  </div>

  <div class="container">
    <div class="col-auto p-5 text-center">
      <h1>Ensaldas y Entrantes</h1>
    </div>

    <div class="row p-4">
      <div class="col-4">
        <Card url="https://www.comedera.com/wp-content/uploads/2017/08/tacos-al-pastor-receta.jpg" nombre="Tacos" descripcion="Tacos deliciosos con doble tortilla, cilantro, piña y carne al pastor" costo="5"/>
      </div>
      <div class="col-4">
        <Card url="https://www.comedera.com/wp-content/uploads/2017/08/tacos-al-pastor-receta.jpg" nombre="Tacos" descripcion="Tacos deliciosos con doble tortilla, cilantro, piña y carne al pastor" costo="5"/>
      </div>
      <div class="col-4">
        <Card url="https://www.comedera.com/wp-content/uploads/2017/08/tacos-al-pastor-receta.jpg" nombre="Tacos" descripcion="Tacos deliciosos con doble tortilla, cilantro, piña y carne al pastor" costo="5"/>
      </div>
    </div>

    <div class="row p-4">
      <div class="col-4">
        <Card url="https://www.comedera.com/wp-content/uploads/2017/08/tacos-al-pastor-receta.jpg" nombre="Tacos" descripcion="Tacos deliciosos con doble tortilla, cilantro, piña y carne al pastor" costo="5"/>
      </div>
      <div class="col-4">
        <Card url="https://www.comedera.com/wp-content/uploads/2017/08/tacos-al-pastor-receta.jpg" nombre="Tacos" descripcion="Tacos deliciosos con doble tortilla, cilantro, piña y carne al pastor" costo="5"/>
      </div>
      <div class="col-4">
        <Card url="https://www.comedera.com/wp-content/uploads/2017/08/tacos-al-pastor-receta.jpg" nombre="Tacos" descripcion="Tacos deliciosos con doble tortilla, cilantro, piña y carne al pastor" costo="5"/>
      </div>
    </div>
  </div>
</template>

<script>
import Card from "./components/Card.vue";
export default {
  components: {
    Card,
  },
};
</script>
