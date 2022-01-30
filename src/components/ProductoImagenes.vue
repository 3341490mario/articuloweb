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
        "https://pbs.twimg.com/profile_images/1438905642262175753/kesiMZxW_400x400.jpg",
        "https://pbs.twimg.com/profile_images/1438905642262175753/kesiMZxW_400x400.jpg",
        "../assets/router2.jpg",
        "../assets/router3.jpg",
        "../assets/router4.jpg",
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
