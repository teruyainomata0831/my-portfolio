<template>
  <div class="home">
    <h1>Welcome to MySite / <router-link to="/about">&gt;</router-link></h1>
    <Footer />
  </div>
</template>

<script>
import Footer from '../components/Footer.vue'
export default {
  components: {
    Footer
  }
}
</script>

<style scoped>
  h1 {
    text-align: center;
    margin: auto;
    font-size: 70px;
    margin-top: 250px;
    font-family: 'Lato', sans-serif;
    font-family: 'Baloo Bhaina 2', cursive;
    font-family: 'Source Sans Pro', sans-serif;
    font-family: 'Playfair Display', serif;
    cursor: pointer;
    color: #FF8C00;
    background: -webkit-linear-gradient(0deg, #40E0D0, #FF8C00, #FF0080);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }
</style>