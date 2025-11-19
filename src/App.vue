<script setup>
import About from './components/About.vue';
import Contact from './components/Contact.vue';
import FooterComponent from './components/FooterComponent.vue';
import Navbar from './components/Navbar.vue';
import Projects from './components/Projects.vue';
import Tools from './components/Tools.vue';

</script>

<template>
  <Navbar />
  <div class="container-fluid">
    <About />
    <Projects />
    <Tools />
    <Contact />
  </div>
  <FooterComponent />
</template>

<style scoped>

</style>
