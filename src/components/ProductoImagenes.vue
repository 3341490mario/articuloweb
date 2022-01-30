<template>
  <div id="images">
    <div id="principal">
      <img v-bind:src="fotos[0]" alt="Router ASUS RT-AC66U"/>
    </div>
    <div id="miniaturas">
      <a @click="cambiarFoto(1)">
        <img v-bind:src="fotos[1]" alt="ASUS RT-AC66U Frontal" 
      /></a>
      <a @click="cambiarFoto(2)">
        <img v-bind:src="fotos[2]" alt="ASUS RT-AC66U Cenital" 
      /></a>
      <a @click="cambiarFoto(3)">
        <img v-bind:src="fotos[3]" alt="ASUS RT-AC66U Trasera de pie"
      /></a>
      <a @click="cambiarFoto(4)">
        <img v-bind:src="fotos[4]" alt="ASUS RT-AC66U Puertos" 
      /></a>
    </div>
  </div>
</template>
 
<script>
export default {
  Name: "ProductoImagenes",
  data() {
    return {
      fotos: [
        "https://www.asus.com/media/global/products/LzShv8ma7TrQB4eO/cdNNvKnT2n4saY3R_480.jpg",
        "https://www.asus.com/media/global/products/LzShv8ma7TrQB4eO/cdNNvKnT2n4saY3R_480.jpg",
        "https://www.asus.com/media/global/products/LzShv8ma7TrQB4eO/VGmK4P0hlDfXLH49_480.jpg",
        "https://www.asus.com/media/global/products/LzShv8ma7TrQB4eO/kTQywRpwLT3Q4LUp_480.jpg",
        "https://www.asus.com/media/global/products/LzShv8ma7TrQB4eO/lONmmYVjqmPshLvG_480.jpg",
        ],
    }
  },
  methods: {
    cambiarFoto(id) {
      this.fotos[0] = this.fotos[id];
    }
  }
};
</script>

<style>
#images {
  width: 50%;
  padding: 2rem;
  box-sizing: border-box;
  text-align: center;
}

#images img {
  border: 3px solid dodgerblue;
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
