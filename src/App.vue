<template>
  <NavBar/>
  <router-view/>
  <Footer/>
</template>

<script>
import NavBar from './components/NavBar.vue';
import Footer from './components/Footer.vue';

export default {
  components: {
    NavBar, Footer
  }
  
}
</script>

<style>
#app {
  font-family: 'Optien', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #31572C;
  background: url(./assets/background.jpg);
  overflow: hidden;
  min-height: 100vh;
}

</style>
