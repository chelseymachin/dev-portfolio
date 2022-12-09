<script setup>
</script>

<template>
  <main>
    <div class="left-side container">
      <img src="../assets/dog-photo.jpg">
    </div>
    <div class="right-side container">
      <h1>Hi!</h1>
      <h3>I'm Chelsey.</h3>
    </div>
  </main>
</template>

<style scoped>
main {
  min-height: 60vh;
  padding: 2rem;
  display: flex;
  background-color: var(--dusty-coral);
  border-radius: 0 2rem 2rem 2rem;
}

img {
  width: 20rem;
  height: 20rem;
  align-self: center;
  border-radius: 50%;
}

.container {
  padding-top: 1rem;
  width: 50%;
  display: flex;
  flex-direction: column;
}

</style>
