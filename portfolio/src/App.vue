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
body, h1, h2, h3, p {
  margin: 0;
  padding: 0;
}

/* Set a background color and font for the entire page */
#app {
  font-family: Arial, sans-serif;
  background-color: #f5f5f5;
  color: #333;
}

/* Style for the header section */
#header {
  background-color: #222;
  color: #fff;
  padding: 20px;
}

/* Style for the navigation links */
#header nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  align-items: center;
}

#header nav ul li {
  margin: 0 20px;
}

#header nav ul li a {
  text-decoration: none;
  color: #fff;
  font-weight: bold;
  transition: color 0.3s;
}

#header nav ul li a:hover {
  color: #ff9900;
}

/* Style for the main sections */
.section {
  padding: 40px;
}

/* Style for the about section */
#about {
  background-color: #fff;
  border-bottom: 1px solid #ddd;
}

/* Style for the projects section */
#projects {
  background-color: #f9f9f9;
}

/* Style for the contact section */
#contact {
  background-color: #fff;
}

/* Basic styling for headings */
h2 {
  font-size: 24px;
  margin-bottom: 20px;
}

/* Add your additional custom styles here */
</style>

