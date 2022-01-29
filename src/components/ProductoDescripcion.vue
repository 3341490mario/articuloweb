<template>
  <div class="description">
    <h1>RT-AC66U</h1>
    <p class="price">84.95€</p>
    <div class="contador">
      <button @click="cambiarCantidad('-1')">-</button>
      <input class="cantidad" type="text" :value="cantidad" />
      <button @click="cambiarCantidad('1')">+</button>
    </div>
    <button class="button">Añadir al carrito</button>
    <h3>Router Gigabit Wireless-AC1750 dual-band 802.11ac</h3>
    <ul>
      <li>
        El chipset 802.11ac ofrece conexiones simultáneas en las bandas
        2.4GHz/5GHz con un ancho de banda total de 1.75Gbps
      </li>
      <li>
        Funcionalidad Triple-VLAN. Ofrece gestión automática de direcciones IP,
        servidor y cliente OpenVPN y mucho más
      </li>
      <li>Puertos Gigabit Ethernet para un rendimiento más rápido y fiable</li>
      <li>
        AiRadar optimiza la cobertura inalámbrica mediante dos antenas con una
        gran potencia
      </li>
      <li>
        Download Master permite el almacenamiento inalámbrico de datos y el
        acceso a los dispositivos de almacenamiento USB conectados
      </li>
      <li>
        Los puertos USB permiten emplearlo para compartir archivos, funciones de
        impresión y la conexión 3G
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  Name: "ProductoDescripcion",
  data() {
    return {
      cantidad: 1
    }
  },
  methods: {
    cambiarCantidad(number){
      this.cantidad += +number;
      
      if(!isNaN(this.cantidad) && (this.cantidad <= 0)){
        this.cantidad = 1
      }
    }
  }
}
</script>
<style>
.description {
  width: 50%;
  background-color: cadetblue;
  box-sizing: border-box;
  padding: 3%;
  padding-top: 0;

  text-align: justify;
  font-size: 1.5rem;
}
.description ul li {
  margin-top: 2%;
}
.price {
  margin: 0;
  font-weight: bold;
  font-size: 4rem;
}
</style>
