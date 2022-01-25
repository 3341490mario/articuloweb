<template>
  <div id="breadcrumb">
    <p>Breadcrumb</p>
    <ul class="breadcrumb">
      <li>Primera</li>
      <li>Segunda</li>
      <li>Tercera</li>
      <li id="actual">Actual</li>
    </ul>
  </div>
</template>
<script>
export default {};
</script>
<style>
#breadcrumb p {
  width: 100%;
  background-color: limegreen;
  margin: 0;
}

#actual {
  font-weight: bold;
}

.breadcrumb {
  margin: 0;
  list-style: none;
  display: flex;
  background-color: brown;
}
</style>
