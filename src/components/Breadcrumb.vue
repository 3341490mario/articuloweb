<template>
  <div id="breadcrumb">
    <ul class="breadcrumb">
      <li>Routers</li>
      <li>Puntos de acceso</li>
      <li>Domésticos</li>
      <li id="actual">RT-AC66U</li>
    </ul>
  </div>
</template>
<script>
export default {};
</script>
<style>
#actual {
  font-weight: bold;
}

.breadcrumb {
  margin: 0;
  list-style: none;
  display: flex;
  background-color: cadetblue;
}
</style>
