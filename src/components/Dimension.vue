<template>
  <div class="compoments">
    <h2>Personnalisez votre produit :</h2>
    <div class="compo-content flex">
      <div class="number">1</div>
      <div class="title">J'indique mes dimensions</div>
    </div>
    <div class="compo-content">
      <label for="longeur" class="block bold">Longeur du rail</label>
      <input type="text" id="longeur" name="longeur" required
       minlength="4" maxlength="8" min="0" max="200" placeholder="min. 0 cm / max. 200 cm">
    </div>
    <div class="button bold">
      <button v-on:click="$emit('pricestep1')">VALIDER</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Dimension",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
</style>
