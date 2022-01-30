<template>
  <div id="cabecera">
    <img src="../assets/logoasus.png" alt="Logo ASUS" />
    <nav class="menu">
      <ul>
        <li>
          <a href="#">Routers</a>
        </li>
        <li>
          <a href="#">Placas base</a>
        </li>
        <li>
          <a href="#">Portátiles</a>
        </li>
        <li>
          <a href="#">Monitores</a>
        </li>
        <li>
          <a href="#">Soporte</a>
        </li>
      </ul>
    </nav>
    <div class="session">
      <a href="#" class="material-icons md-36" title="Mi cuenta">account_circle</a>
      <a href="#" class="material-icons md-36" title="Mi cesta">shopping_bag</a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
#cabecera {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-around;
  background-color: slategrey;
}

#cabecera img {
  width: 8%;
}

#cabecera .menu {
  width: 40%;
}

#cabecera .menu ul {
  margin: 0;
  padding: 0;
  display: flex;
  width: 100%;
  list-style: none;
  box-sizing: border-box;
}

#cabecera .menu ul li {
  padding: 1rem;
  margin-left: auto;
  margin-right: auto;
  font-weight: bold;
  font-size: clamp(0.8rem, 1rem, 1.2rem);
}

#cabecera .menu ul li a:hover {
  color: white;
  font-size: clamp(1rem, 1.2rem, 1.4rem);
}

.session {
  display: flex;
  align-items: center;
  box-sizing: border-box;
  justify-content: space-around;
  width: 8%;
}

.material-icons.md-36 { font-size: 36px; }

a {
  text-decoration: none;
}
</style>
