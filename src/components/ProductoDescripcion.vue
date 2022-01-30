<template>
  <div class="description">
    <h1>RT-AC66U</h1>
    <p class="price">84.95€</p>
    <div class="contador">
      <p>Cantidad:&nbsp;&nbsp;&nbsp;</p>
      <button @click="cambiarCantidad('-1')" class="btn">-</button>
      <input class="cantidad" type="text" :value="cantidad" />
      <button @click="cambiarCantidad('1')" class="btn">+</button>
    </div>
    <button class="carrito">Añadir al carrito</button>
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
  box-sizing: border-box;
  padding: 3%;
  padding-top: 0;
  text-align: justify;
  font-size: clamp(.5rem, 1rem, 1.5rem);
}

.description ul li {
  margin-top: 2%;
}

.price {
  margin: 0;
  font-weight: bold;
  font-size: clamp(2rem, 3rem, 4rem);
}

.contador {
  display: flex;
  align-items: center;
  margin-bottom: 1rem;
  width: 35%;
}

.cantidad {
  width: 2rem;
  height: 1.6rem;
  border: none;
  text-align: center;
  font-size: 1rem;
}

.btn {
  border: .15rem solid dodgerblue;
  border-radius: 5px;
  width: 1.6rem;
  height: 1.6rem;
  font-size: 1.1rem;
}

.carrito {
  cursor: pointer;
  font-weight: bold;
  font-size: 1rem;
  padding: 1.2rem;
  border: 2px solid dodgerblue;
  border-radius: 10px;
  margin-left: auto;
  margin-right: auto;
}
</style>
