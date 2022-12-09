<script setup>
</script>

<template>
  <main>
    <div class="left-side container">
      <img src="../assets/dog-photo.jpg">
    </div>
    <div class="right-side container">
      <h3>I'm Chelsey.</h3>
      <p>A <em>Full-Stack Software Engineer</em> with a passion for creating performant, de-coupled front-end applications.</p>
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

.left-side img {
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

.header-container img {
  width: 64px;
  height: 64px;
  margin-left: 1rem;
  margin-top: 3rem;
}

h1 {
  font-size: 6rem;
}

h3 {
  font-size: 4rem;
  align-self: start;
}

</style>
