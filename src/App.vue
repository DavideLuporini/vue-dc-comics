<template>
  <div id="app">
    <Header />
    <Jumbotron />
    <Info />
    <Links />
    <Footer />
  
    
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Jumbotron from './components/Jumbotron.vue';
import Info from './components/Info.vue';
import Links from './components/Links.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    Info,
    Links,
    Footer,
  }
}
</script>

<style lang="scss">
*{
    margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body
{
  font-family: "Segoe UI", "Open Sans", Helvetica, sans-serif;
  height: 100vh;
}
</style>
