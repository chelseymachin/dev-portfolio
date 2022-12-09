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
  </div>
</template>

<style scoped>
.outer-container {

}

</style>
