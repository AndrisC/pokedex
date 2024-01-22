<template>
  <div class="app-container">
    <h2>Welcome to the Pokedex</h2>
    <poke-card />
  </div>
</template>

<script>
import PokeCard from './components/pokeCard.vue'

export default {
  name: 'App',
  components: {
    PokeCard
  }
}
</script>

<style lang="css">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
