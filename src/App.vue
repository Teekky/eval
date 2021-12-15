<template>
  <div id="api">
    <Api msg="" />
  </div>
  <div id="main-container">
    <div class="content-left">
      <Article msg="" />
    </div>
    <div class="content-right">
      <div class="scroll">
        <!-- Chaque option est en radio button et il est caché -->
        <Dimension msg="" />
        <Type msg="" />
        <Color msg="" />
      </div>
      <div class="cart-content">
        <Step msg="" />
        <Price msg="" />
      </div>
    </div>
  </div>
</template>

<script>
import Article from "./components/Article.vue";
import Dimension from "./components/Dimension.vue";
import Type from "./components/Type.vue";
import Color from "./components/Color.vue";
import Step from "./components/Step.vue";
import Price from "./components/Price.vue";
import Api from "./components/Api.vue";

export default {
  name: "App",
  components: {
    Article,
    Dimension,
    Type,
    Color,
    Step,
    Price,
    Api,
  },
  data() {
    return {
      price: "",
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#main-container {
  width: 1250px;
  margin: auto;
  display: flex;
  text-align: left;
  justify-content: space-between;
}

.content-left {
  width: 600px;
}

.content-right {
  width: 600px;
  margin-top: 2em;
}

.scroll {
  max-height: 500px;
  overflow-y: scroll;
}

h2 {
  color: darkblue;
  border-bottom: 1px solid blue;
  padding-bottom: 10px;
}

.compoments {
  border-bottom: 1px solid blue;
  padding-bottom: 2em;
  margin: 2em 0;
}

.compo-content {
  margin: 2em;
}

.number {
  background-color: lightblue;
  color: darkblue;
  padding: 1em;
  border-radius: 50px;
}

.title {
  align-self: center;
  margin-left: 1em;
}

label {
  margin: 1em 0;
}

#longeur {
  padding: 1em 4em;
}

.button {
  text-align: right;
}

button {
  background-color: darkblue;
  color: white;
  padding: 1em;
  border: none;
  cursor: pointer;
}

.content-type {
  text-align: center;
  border: 1px solid black;
  padding: 1em;
}

.content-type img {
  width: 80px;
}

.details {
  font-size: 8px;
}

p {
  margin: 5px 0;
}

.button-radio {
  position: relative;
}

.button-radio input {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 0;
  visibility: ;
}

.color {
  height: 80px;
}

.cart-content {
  text-align: center;
  border-top: 1px solid lightgrey;
}
------------------------- .w100 {
  width: 100%;
}

.flex {
  display: flex;
}

.relative {
  position: relative;
}

.block {
  display: block;
}

.bold {
  font-weight: bold;
}

.center {
  text-align: center;
}

.black {
  background-color: black;
}

.flex50 {
  flex: 50%;
}

.auto {
  margin: auto;
}
</style>
