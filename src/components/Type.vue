<template>
  <div class="compoments">
    <div class="compo-content">
      <form class="flex">
      <div class="button-radio">
        <input type="radio" id="ds" name="type" value="ds">
        <label for="ds">
          <div class="content-type">
            <img src="https://www.mesrideaux.fr/media/customoptions/f/o/forest_ds_s_arret_metal.jpg" alt="">
            <p class="bold">Modèle DS : Fixation au léger plafond pour rideaux légers</p>
            <p class="details">(sans doublure, hauteur max 300 cm</p>
          </div>
        </label>
      </div>
      <div class="button-radio">
        <input type="radio" id="cs" name="type" value="cs">
        <label for="cs">
          <div class="content-type">
            <img src="https://www.mesrideaux.fr/media/customoptions/c/s/cs_b34156.png" alt="">
            <p class="bold">Modèle CS : Fixation au léger plafond ou au mur pour rideaux lourds</p>
            <p class="details">(doublé, hauteur + 300 cm</p>
          </div>
        </label>
      </div>
      </form>
    </div>

    <div class="button bold">
      <button>VALIDER</button>
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
