<template>
  <div id="container">
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

#cabecera .menu {
  background-color: lightyellow;
  display: block;
}

#cabecera .menu ul {
  display: flex;
  list-style: none;
  padding: 1rem;
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