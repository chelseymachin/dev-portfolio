<script setup>
import { RouterView } from 'vue-router';
import HeaderNav from './components/HeaderNav.vue';
</script>

<template>
  <div>
    <HeaderNav />
    <div class="outer-container">
      <RouterView />
    </div>
    <div class="signature-container">
      <h1>Chelsey Machin</h1>
    </div>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@700&display=swap');
.signature-container {
  display: flex;
  justify-content: center;
  font-family: 'Comfortaa', cursive;
  font-size: 3rem;
  text-shadow: 8px 8px 8px var(--deep-purple);
  color: var(--dusty-coral);
}



.signature-container img {
  width: 15rem;
}

</style>
