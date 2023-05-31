<script setup> //es el ciclo de vida del componente que cuando se pone el setup, no hay que llamar a ninguna base de datos 
  import Nav from './components/Nav.vue'
  import mytitle from './components/mytitle.vue';
</script>


<template>
<RouterView />
  <header>
    <div class="wrapper">
      
      <mytitle/>
      <Nav/>
      

    </div>
  </header>

  
</template>

