<template>
  <div id="breadcrumb">
    <ul>
      <li><a href="#">Routers</a></li>
      <li><a href="#">Domésticos</a></li>
      <li><a href="#" id="actual">RT-AC66U</a></li>
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

#breadcrumb ul {
  margin: 0;
  list-style: none;
  display: flex;
  border-top: solid 3px dodgerblue;
  border-bottom: solid 3px dodgerblue;
}

#breadcrumb ul li+li:before {
  color: dodgerblue;
  font-weight: bold;
  content: "\003E";
}

#breadcrumb ul li a:hover {
  color: dodgerblue;
}

#breadcrumb ul li a, #breadcrumb ul li a:visited{
    text-decoration: none;
    margin-left: 1rem;
    margin-right: 1rem;
}
</style>
