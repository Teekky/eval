<template>
  <div>
    <h1>Tringle Rail</h1>
    <img
      src="https://cdn-icons.flaticon.com/png/512/3926/premium/3926106.png?token=exp=1639572483~hmac=7124f09cc2c699911cb00959462c03ee"
      alt=""
      class="coeur"
    />
    <img
      src="https://cdn2.mesrideaux.fr/media/catalog/product/cache/c4f8953d6b68b8073272b21c1e15595e/t/r/tringles-rail.jpg"
      alt=""
      style="width:100%"
    />
  </div>
</template>

<script>
export default {
  name: "Article",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.coeur {
  width: 25px;
  display: block;
  margin: 1em 0;
  cursor: pointer;
}
</style>
