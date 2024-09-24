<template>
  <div>
    <Navbar />
    <Header />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'; 
import Header from './components/Header.vue'; 

export default {
  components: {
    Navbar,
    Header, // Register Header component here
  },
};
</script>

<style scoped>
</style>
