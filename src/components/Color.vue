<template>
  <div class="compoments">
    <div class="compo-content">
      <form class="flex">
      <div class="button-radio flex50">
        <input type="radio" id="white" name="color" value="white">
        <label for="white">
          <div class="content-type">
            <div class="color auto"></div>
            <p class="bold">Blanc</p>
          </div>
        </label>
      </div>
      <div class="button-radio flex50">
        <input type="radio" id="black" name="color" value="black">
        <label for="black">
          <div class="content-type">
            <div class="color auto black"></div>
            <p class="bold">Noir</p>
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
  name: "Color",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
</style>
