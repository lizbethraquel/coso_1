<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
  <lizbeth/>
  <mytitle :title="aboutTitle"/>

</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>

<script setup>
  import lizbeth from '../components/Nav.vue'
  import mytitle from '../components/mytitle.vue';

  const aboutTitle ="Soy about"
</script>