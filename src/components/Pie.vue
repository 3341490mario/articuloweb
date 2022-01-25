<template>
  <div class="prueba">
    <footer>
      <div id="contact">
        <h2>Contacto</h2>
      </div>
      <div id="pedidos">
        <h2>Pedidos</h2>
        <ul>
          <li><a href="#">Métodos de pago</a></li>
          <li><a href="#">Envíos y devoluciones</a></li>
          <li><a href="#">Seguimiento de pedidos</a></li>
        </ul>
      </div>
      <div id="rrss">
        <h2>Redes Sociales</h2>
        <a href="#"
          ><img src="../assets/instagram-logo.png" alt="Instagram"
        /></a>
        <a href="#"><img src="../assets/facebook-logo.png" alt="Facebook" /></a>
        <a href="#"><img src="../assets/twitter-logo.png" alt="Twitter" /></a>
      </div>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style>
.prueba {
  width: 100%;
}
footer {
  background-color: lightslategray;
  display: flex;
  justify-content: space-around;
}

#rrss img {
  width: 50px;
}
</style>
