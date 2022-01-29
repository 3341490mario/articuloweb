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
  font-size: 1.2rem;
}

#cabecera .menu ul li a:hover {
  color: white;
  font-size: 1.4rem;
}

.session {
  display: flex;
  box-sizing: border-box;
  width: 20%;
}

.button {
  font-weight: bold;
  font-size: 1.1rem;
  padding: 1.5rem;
  border: 2px solid cadetblue;
  border-radius: 10px;
  margin-left: auto;
  margin-right: auto;
}

a {
  text-decoration: none;
}
</style>
