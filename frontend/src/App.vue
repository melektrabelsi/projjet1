<template>
  <!-- Le conteneur principal de l'application -->
  <div id="app">
    <!-- Barre de navigation -->
    <nav-bar />
  </div>
</template>

<script>
// Importez le composant NavBar depuis le fichier 'NavBar.vue'
import NavBar from './components/NavBar.vue';

export default 
{
  name: 'App', // Le nom du composant App
  components: { // Les composants utilisés dans cette vue
    NavBar, // Composant NavBar
  },
};
</script>

<style lang="scss">
/* Styles CSS pour l'apparence de la page */
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 100%;
}
</style>
