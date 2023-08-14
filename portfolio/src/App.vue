<template>
  <div id="app">
    <Header />
    <About />
    <Projects />
    <Contact />
  </div>
</template>

<script>
import Header from "./components/HeaderSection.vue";
import About from "./components/AboutSection.vue";
import Projects from "./components/ProjectsSection.vue";
import Contact from "./components/ContactSection.vue";

export default {
  components: {
    Header,
    About,
    Projects,
    Contact,
  },
};
</script>

<style>
/* Add your global styles here */
</style>

