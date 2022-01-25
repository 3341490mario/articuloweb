<template>
  <Cabecera />
  <Breadcrumb />
  <ProductoImagenes />
  <Pie />
</template>

<script setup>
import Cabecera from "./components/Cabecera.vue";
import ProductoImagenes from "./components/ProductoImagenes.vue";
import Pie from "./components/Pie.vue";
import Breadcrumb from "./components/Breadcrumb.vue";
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Dongle&family=Inter&display=swap');

body {
  font-family: 'Dongle', sans-serif;
  font-size: 1.5rem;
  margin: 0px;
  padding: 0px;
}
</style>
