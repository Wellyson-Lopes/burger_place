<template>
  <Navbar :logo="logoSrc" :alt="appName" />
  <router-view />
  <Footer> </Footer>
</template>
<script>
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';

export default {
  components: {
    Navbar,
    Footer
  },
  data() {
    return {
      logoSrc: "/img/logo.png",
      appName: 'Make Your Burger',
    }
  }
}
</script>

<style>
* {
  font-family: Helvetica;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.main-container {
  margin: 50px;
  min-height: 250px;
}

h1 {
  text-align: center;
  font-size: 42px;
  margin-bottom: 30px;
  columns: #222;
}
</style>
