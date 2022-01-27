<template>
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
      <a href="#"><img src="../assets/instagram-logo.png" alt="Instagram" /></a>
      <a href="#"><img src="../assets/facebook-logo.png" alt="Facebook" /></a>
      <a href="#"><img src="../assets/twitter-logo.png" alt="Twitter" /></a>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style>
footer {
  background-color: lightslategray;
  display: flex;
  justify-content: space-around;
  align-content: center;
}

#contact {
  background-color: burlywood;
  width: 20%;
}

#pedidos {
  width: 20%;
  background-color: chocolate;
}

#rrss {
  width: 20%;
  background-color: brown;
}
#rrss img {
  width: 50px;
  padding: 5%;
}
</style>
