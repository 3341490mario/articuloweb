<template>
  <div id="images">
    <div id="principal">
      <img v-bind:src="fotos[0]" alt="Producto" />
    </div>
    <div id="miniaturas">
      <a @click="cambiarFoto(1)">
        <img v-bind:src="fotos[1]" alt="Portátil Huawei MateBoot X" /></a>
      <a @click="cambiarFoto(2)">
        <img v-bind:src="fotos[2]" alt="Portátil Huawei MateBoot X" /></a>
      <a @click="cambiarFoto(3)">
        <img v-bind:src="fotos[3]" alt="Portátil Huawei MateBoot X"/></a>
      <a @click="cambiarFoto(4)">
        <img v-bind:src="fotos[4]" alt="Portátil Huawei MateBoot X"/></a>
    </div>
  </div>
</template>

<script>
export default {
  Name: 'ProductoImagenes',
    data () {
        return {
            fotos: [
                '/src/assets/router1.jpg',              
                '/src/assets/router1.jpg',
                '/src/assets/router2.jpg',
                '/src/assets/router3.jpg',
                '/src/assets/router4.jpg'
            ]
        }
    },
    methods: {
        cambiarFoto(id) {
            this.fotos[0] = this.fotos[id]
        }
    }
}
</script>

<style>
#images {
  width: 50%;
  padding: 2rem;
  box-sizing: border-box;
  text-align: center;
}

#images img {
  border: 4px solid cadetblue;
  border-radius: 10px;
}

#principal img {
  width: 70%;
  height: auto;
  margin-top: 5%;
}

#miniaturas {
  margin-left: 15%;
  margin-top: 5%;
  width: 70%;
  display: flex;
}

#miniaturas img {
  width: 70%;
  height: auto;
}
</style>
