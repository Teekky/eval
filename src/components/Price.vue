<template>
  <div class="price flex">
    <h1>0 € TTC</h1>
    
    <!-- J'ai essayé mais les prix s'affichent quand même, je ne comprends pas..

    <div class="flex50" v-if="price = 'pricestep1'">
          <h1>111€ TTC</h1>
    </div>
        <div v-if="price = 'pricestep2'">
          <h1>222€ TTC</h1>
        </div>
        <div v-if="price = 'pricestep3'">  
          <h1>333€ TTC</h1>
        </div>
      -->
    <div class="button bold flex50">
      <button>VALIDER LE PANIER</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Price",
  props: {
    msg: String,
  },
  data() {
    return {
      price: "",
    };
  },
};
</script>

<style scoped>
.cart-content {
  text-align: center;
  border-top: 1px solid lightgrey;
  position: absolute;
  bottom: 0;
  right: 0;
  width: 600px;
}

.step-content {
  background-color: rgba(255, 255, 255, 0.9);
  padding: 1em 0;
}

.step {
  display: flex;
  justify-content: space-around;
}

.price {
  background-color: lightskyblue;
  padding: 3em;
}

-------------- .number {
  margin: 1em;
}

p {
  margin: 1em 0;
}

h1 {
  margin: 0;
}
</style>
