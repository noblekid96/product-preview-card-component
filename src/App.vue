<script setup>
 import ProductCard from './components/ProductCard.vue'
</script>

<template>
  <div>
  <div class="container">
    <ProductCard/>
    <div class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
      Coded by <a href="#">Cheow Fu</a>.
    </div>
  </div>
  </div>
</template>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,700&family=Montserrat:wght@500;700&display=swap');

 .container {
   min-height: 100vh;
   display: flex;
   align-items: center;
   justify-content: center;
   background-color: hsl(30, 38%, 92%);
   overflow: auto;
 }

 * {
   padding: 0px;
 }

.attribution {
  font-size: 11px;
  text-align: center;
  position: absolute;
  bottom: 10px;
}

.attribution a {
    color: hsl(158, 36%, 37%);
}



</style>
