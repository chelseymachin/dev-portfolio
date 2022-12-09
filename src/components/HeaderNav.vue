<script>

</script>

<template>
  <div class="header-container">
    <router-link to="/">
      <img src="../assets/HomeIcon.png" />
    </router-link>
    <router-link to="/work">
      <img src="../assets/WorkIcon.png" />
    </router-link>
    <router-link to="/projects">
      <img src="../assets/ProjectsIcon.png" />
    </router-link>
    <router-link to="/contact">
      <img src="../assets/ContactIcon.png" />
    </router-link>
  </div>
</template>

<style scoped>
.header-container {
  width: 100%;
  display: flex;
  justify-content: space-between;
  padding-bottom: 0;
  margin-bottom: 0;
}

img {
  padding: 2rem 2rem 0 2rem;
}

.router-link-active {
  background-color: var(--dusty-coral);
  border-radius: 2rem 2rem 0 0;
}

</style>