<template>
  <section id="about">
    <h2>About Me</h2>
    <div class="about-content">
      
      <div class="about-text">
        <p>
          Hi there! I'm Jeffery Allbright, a versatile and diligent software engineer based in Indianapolis, IN. With a strong foundation in both software engineering and liberal arts, I bring a unique perspective to problem-solving and innovation.
        </p>
        <p>
          I hold a Bachelor of Arts degree in Liberal Arts and Business from Indiana University, and I'm a graduate of Tech Elevator's Full Stack Software Development program. My technical skills include Java, Spring Boot, PostgreSQL, HTML, CSS, JavaScript, and Vue.js.
        </p>
        <p>
          My technical journey includes projects like creating a virtual vending machine, building a payment calculator using RESTful APIs, and developing a property manager application that enhances the lives of renters, landlords, and service staff.
        </p>
        <p>
          Beyond coding, I've gained valuable experience in roles like Mine Subsidence Program Manager at the Indiana Department of Insurance and Assistant Geologist at the Indiana Department of Transportation. My work there involved investigating insurance claims, organizing data, and leveraging software tools for geological records.
        </p>
        <p>
          When I'm not crafting code or diving into data, you can find me exploring the world of technology, hiking in the beautiful landscapes of Indiana, or enjoying a cup of coffee while brainstorming my next project. I'm always eager to collaborate, learn, and create solutions that make a positive impact.
        </p>
        <p>
          Feel free to reach out to me through my email <a href="mailto:jm.allbright@yahoo.com">jm.allbright@yahoo.com</a> or connect with me on LinkedIn at <a href="https://www.linkedin.com/in/jeffery-allbright/" >linkedin.com/in/jeffery-allbright</a>. Let's build something amazing together!
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
#about {
  padding: 40px;
  background-color: #fff;
}

.about-content {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
}

.profile-image {
  flex: 1;
  text-align: center;
}

.profile-image img {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  object-fit: cover;
  margin: 0 auto;
}

.about-text {
  flex: 2;
  padding: 20px;
  font-size: 18px;
  line-height: 1.6;
}
</style>