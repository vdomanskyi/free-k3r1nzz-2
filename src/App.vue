<template>
  <h1  style="width: 100%; text-align: center;">FREE K3R1NZZ</h1>

  <img :src="img" alt="">
</template>

<script lang="ts" setup>
import img from './assets/img.png'
</script>


<style lang="scss">
body {
display: flex;
align-items: center;
justify-content: center;

#app {
width: 100%;
display: flex;
align-items: center;
justify-content: center;
flex-direction: column;

height: 100vh;

padding: 30px;

img {
width: 100%;
object-fit: contain;
max-height: 70vh;

margin-top: 20px;
}
}
}
</style>
