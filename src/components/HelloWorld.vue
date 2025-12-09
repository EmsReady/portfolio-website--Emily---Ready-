<template>
  <header>
    <div class="container">
      <h1>Emily Ready</h1>
      <p class="tagline">Creative Technologist & Future Web Developer</p>
    </div>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>
  
  <section class="about">
    <div class="about-card">
      <h3>Creative Developer</h3>
      <p>Building interactive experiences with Vue, JavaScript, and modular design.</p>
    </div>
    <div class="about-card">
      <h3>Color theoryist</h3>
      <p>Designing intuitive interfaces with color theory and user empathy.</p>
    </div>
  </section>
  

  <main>
    <section class="about">
      <div class="container">
        <h2>About Me</h2>
        <p>
          I'm a passionate and resilient developer-in-training with a strong foundation in HTML, CSS, JavaScript, Java, and SQL. I love crafting interactive, user-friendly web experiences and experimenting with color theory, modular design, and multimedia elements. My goal is to build a career that blends technical precision with creative expression.
        </p>
        <p>
          This site will grow with me—soon you'll find a full portfolio showcasing my projects, design sensibilities, and development journey.
        </p>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      <p>&copy; 2025 Emily Ready. All rights reserved.</p>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
nav {
    background-color: #3498db;
    padding: 15px 0;
    text-align: center;
  }
  
  nav a {
    color: #ecf0f1;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s ease;
  }
  
  nav a:hover {
    color: #d6eaf8;
  }

  
  .about {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
    padding: 40px 0;
  }
  
  .about-card {
    background-color: #ecf0f1;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(44, 62, 80, 0.1);
    transition: transform 0.3s ease;
  }
  
  .about-card:hover {
    transform: translateY(-5px);
  }
  
  .about-card h3 {
    color: #2c3e50;
    margin-bottom: 10px;
  }
  
  .about-card p {
    color: #2d3436;
  }

  .button {
    display: inline-block;
    background-color: #3498db;
    color: #fff;
    padding: 10px 20px;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
    transition: background-color 0.3s ease;
  }
  
  .button:hover {
    background-color: #2980b9;
  }
  
</style>
