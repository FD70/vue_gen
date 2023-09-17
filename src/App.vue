<script setup>
import MainBody from './components/MainBody.vue';
</script>

<template>
  <header>
    <p>TEXT</p>
  </header>
  <MainBody />
  <!-- <footer/> -->
</template>

<style scoped>
header {
  height: 42px;
  background-color: #180AC2;

  align-items: center;
  text-align: center;

  > p {
    color: white;
    font-family: monospace;
    font-weight: 800;
    font-size: 24px;
  }
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}
</style>
