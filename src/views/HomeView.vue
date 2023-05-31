<template>
  <h1> mi home </h1>
  <mytitle :title="homeTitle"/>

  <lizbeth/>
</template>

<script setup>
  import lizbeth from '../components/Nav.vue'
  import mytitle from '../components/mytitle.vue';
  
  const homeTitle = "hola al mundo gato"
</script>