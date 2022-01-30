<template>
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet" />
  <div id="container">
    <Cabecera />
    <Breadcrumb />
    <div id="product">
      <ProductoImagenes />
      <ProductoDescripcion />
    </div>
    <Video />
    <Pie />
  </div>
</template>

<script>
import Cabecera from "./components/Cabecera.vue";
import ProductoImagenes from "./components/ProductoImagenes.vue";
import ProductoDescripcion from "./components/ProductoDescripcion.vue";
import Video from "./components/Video.vue";
import Pie from "./components/Pie.vue";
import Breadcrumb from "./components/Breadcrumb.vue";

export default {
  name: "App",
  components: {
    Cabecera,
    ProductoImagenes,
    ProductoDescripcion,
    Video,
    Breadcrumb,
    Pie,
  }
}
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Dongle&family=Inter&family=Nunito&display=swap");

body {
  font-family: "Nunito", sans-serif;
  margin: 0px;
  padding: 0px;
}

#container {
  margin-left: auto;
  margin-right: auto;
}

#product {
  display: flex;
  flex-direction: row;
}

a {
  text-decoration: none;
  color: black;
}

button:hover {
  cursor: pointer;
  background: dodgerblue;
  color: white;
  font-weight: bold;
}
</style>
