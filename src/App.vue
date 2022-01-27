<template>
<div id="container">
  <Cabecera />
  <Breadcrumb />
  <div id="product">
    <ProductoImagenes />
    <ProductoDescripcion />
  </div>
  <Pie />
</div>
</template>

<script>
import Cabecera from "./components/Cabecera.vue";
import ProductoImagenes from "./components/ProductoImagenes.vue";
import ProductoDescripcion from "./components/ProductoDescripcion.vue";
import Pie from "./components/Pie.vue";
import Breadcrumb from "./components/Breadcrumb.vue";

export default {
  name: "App",
  components: {
    Cabecera,
    ProductoImagenes,
    ProductoDescripcion,
    Breadcrumb,
    Pie,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Dongle&family=Inter&family=Nunito&display=swap');

body {
  font-family: "Nunito", sans-serif;
  font-size: 1rem;
  margin: 0px;
  padding: 0px;
}
#container {
  max-width: 85%;
  margin-left: auto;
  margin-right: auto;
}
#product {
  display: flex;
  flex-direction: row;
}
</style>
