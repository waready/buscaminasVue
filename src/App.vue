<template>
  <div id="app" class="principal">
    <tablero></tablero>
  </div>
</template>

<script>
import Tablero from './components/Tablero.vue'

export default {
  name: 'app',
  components: {
    Tablero
  }
}
</script>

<style>
.principal{
  display:grid;
  justify-content:center;
}
</style>
