<template>
  <footer>
    <div id="contact">
      <h2>Contacto</h2>
      <address>
        <p>Calle Inventada, 15</p>
        <p>Tlf: +34 968 589 685</p>
      </address>
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
      <a href="#"><img src="../assets/instagram-logo.png" alt="Instagram" title="Instagram" /></a>
      <a href="#"><img src="../assets/facebook-logo.png" alt="Facebook" title="Facebook" /></a>
      <a href="#"><img src="../assets/twitter-logo.png" alt="Twitter" title="Twitter" /></a>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style>
footer {
  font-size: 1.2rem;
  background-color: slategrey;
  display: flex;
  justify-content: space-around;
  align-content: center;
}

#contact {
  width: 20%;
}

#pedidos {
  width: 20%;
}

#rrss {
  width: 20%;
}
#rrss img {
  width: 50px;
  padding-right: 10%;
  padding-left: 10%;
}
</style>
