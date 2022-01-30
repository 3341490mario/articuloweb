<template>
  <footer>
    <div id="contact">
      <h3>Contacto</h3>
      <address>
        <p>Calle Inventada, 15</p>
        <p>Tlf: +34 968 589 685</p>
        <a href="mailto:info@asus.com">info@asus.com</a>
      </address>
    </div>
    <div id="pedidos">
      <h3>Pedidos</h3>
      <ul>
        <li><a href="#">Métodos de pago</a></li>
        <li><a href="#">Envíos y devoluciones</a></li>
        <li><a href="#">Seguimiento de pedidos</a></li>
      </ul>
    </div>
    <div id="rrss">
      <h3>Redes Sociales</h3>
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
  font-size: clamp(.8rem, 1rem, 1.2rem);
  background-color: slategrey;
  display: flex;
  justify-content: space-around;
  align-content: center;
  border-top: 3px solid white;
}

#contact {
  width: 20%;
  line-height: 1rem;
}

#pedidos {
  width: 20%;
}

#rrss {
  width: 20%;
}
#rrss img {
  width: clamp(25px, 40px, 50px);
  padding-right: clamp(5%, 7%, 10%);
  padding-left: clamp(5%, 7%, 10%);
}
</style>
