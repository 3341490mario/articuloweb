<template>
  <div id="breadcrumb">
    <a href="#">Routers</a> \
    <a href="#">Domésticos</a> \
    <a href="#" id="actual">RT-AC66U</a>
  </div>
</template>
<script>
export default {};
</script>
<style>
#actual {
  font-weight: bold;
}

#breadcrumb {
  margin: 0;
  list-style: none;
  display: flex;
  border-top: solid 3px dodgerblue;
  border-bottom: solid 3px dodgerblue;
}

#breadcrumb a:hover {
  color: dodgerblue;
}

#breadcrumb a, #breadcrumb a:visited{
    text-decoration: none;
    margin-left: 1rem;
    margin-right: 1rem;
}
</style>
