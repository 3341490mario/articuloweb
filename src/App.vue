<template>
  <Cabecera />
  <Breadcrumb />
  <div id="product">
    <ProductoImagenes />
    <ProductoDescripcion />
  </div>
  <Pie />
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
@import url("https://fonts.googleapis.com/css2?family=Dongle&family=Inter&display=swap");

body {
  font-family: "Dongle", sans-serif;
  font-size: 1.5rem;
  margin: 0px;
  padding: 0px;
}

#product {
  display: flex;
  flex-direction: row;
}
</style>
