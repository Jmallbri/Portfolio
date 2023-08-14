<template>
  <section id="contact">
    <h2>Contact Me</h2>
    <p class="contact-info">Jeffery Allbright</p>
    <p class="contact-info">(317) 965-9334</p>
    <p class="contact-info">jm.allbright@yahoo.com</p>
    <p class="contact-info">
      <a
        href="https://www.linkedin.com/in/jeffery-allbright/"
        target="_blank"
        rel="noopener noreferrer"
        class="linkedin-link"
      >
        LinkedIn Profile
      </a>
    </p>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
#contact {
  background-color: #f5f5f5;
  padding: 40px;
  text-align: center;
}

h2 {
  font-size: 28px;
  margin-bottom: 20px;
}

.contact-info {
  font-size: 18px;
  margin: 10px 0;
}

.linkedin-link {
  color: #0077b5;
  text-decoration: none;
  transition: color 0.3s;
}

.linkedin-link:hover {
  color: #004471;
}

/* Add more styles here */
</style>