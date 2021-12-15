<template>
  <div id="api">
    <h1>2025-01-01": "1er janvier"</h1>
    <!-- Rien qui marche... -->
  </div>
</template>

<script>
import axios from "axios"
export default {
  name: "Api",
  props: {
    msg: String,
  },
  mounted() {
    axios
      .get("https://calendrier.api.gouv.fr/jours-feries/metropole.json")
      .then((response) => (this.info = response))
      .then((response) => (this.info = response.data.bpi))
  },
};
</script>

<style scoped>
</style>
