<template>

  <div id="app">
  
    <Header />

    <Cards />

    <Main />

    <Footer />

  </div>
 
</template>

<script>

import Header from './components/Header';
import Cards from './components/Cards';
import Main from './components/Main';
import Footer from './components/Footer';

export default {
    name: 'App',
    components: {
      Header,
      Cards,
      Main,
      Footer
    }
}

</script>

<style>

  * {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
  }

</style>
