<template>
  <div id="cabecera">
    <img src="../assets/logoasus.png" alt="Logo Xixohelat" />
    <nav class="menu">
      <ul>
        <li><a href="#">Routers</a></li>
        <li><a href="#">Placas base</a></li>
        <li><a href="#">Portátiles</a></li>
        <li><a href="#">Monitores</a></li>
        <li><a href="#">Soporte</a></li>
      </ul>
    </nav>
    <div class="session">
      <a href="#" class="button">Registrarse</a>
      <a href="#" class="button">Iniciar sesión</a>
      <a href="#" class="button">Cesta</a>
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
  background-color: lightblue;
}

#cabecera img {
  width: 8%;
}

#cabecera .menu {
  width: 30%;
  background-color: lightyellow;
}

#cabecera .menu ul {
  margin: 0;
  padding: 0;
  display: flex;
  width: 100%;
  list-style: none;
  background-color: blue;
  box-sizing: border-box;
}

#cabecera .menu ul li {
  padding: 1rem;
  margin-left: auto;
  margin-right: auto;
  background-color: lightcoral;
  font-weight: bold;
}

.session {
  display: flex;
  box-sizing: border-box;
  width: 20%;
  background-color: lime;
}

.button {
  padding: 1rem;
  border: 2px solid cadetblue;
  border-radius: 10px;
  margin-left: auto;
  margin-right: auto;
}

a {
  text-decoration: none;
}
</style>
