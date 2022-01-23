<template>
  <div class="container">
    <div id="cabecera">
      <img src="#" alt="logo" />
      <nav class="menu">
        <ul>
          <li><a href="">Menu 1</a></li>
          <li><a href="">Menu 2</a></li>
          <li><a href="">Menu 3</a></li>
          <li><a href="">Menu 4</a></li>
          <li><a href="">Menu 5</a></li>
        </ul>
      </nav>
      <div class="session">
        <a href="#" class="button">Registrarse</a>
        <a href="#" class="button">Iniciar sesión</a>
        <a href="#" class="button">Cesta</a>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style>
#cabecera {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: lightblue;
}

#cabecera img {
  width: 10%;
}

#cabecera .menu {
  background-color: lightyellow;
}

#cabecera .menu ul {
  margin: 0;
  padding: 0;
  display: flex;
  width: 100%;
  list-style: none;
}

#cabecera .menu ul li {
  display: flex;
  padding: 1rem;
  background-color: lightcoral;
  font-weight: bold;
}

.session {
  display: flex;
  background-color: lime;
}

.button {
  padding: 1rem;
}

a {
  text-decoration: none;
}
</style>