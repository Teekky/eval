<template>
  <div class="step-content">
    <p>Veuillez valider toutes les étapes de la personnalisation</p>
    <div class="step">
      <div class="number" v-if="step === step1">1</div>
      <div class="number" v-if="step === step2">2</div>
      <div class="number" v-if="step === step3">3</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Step",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
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
