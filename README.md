# Portfolio-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Samuel Obaro | UI/UX Designer</title>
  <link rel="stylesheet" href="styles/style.css">
</head>
<body>

  <!-- Hero Section -->
  <header class="hero">
    <h1>Samuel Obaro</h1>
    <p>Crafting Intuitive & Engaging User Experiences for 5+ Years</p>
    <a href="#contact" class="btn">Let's Work Together</a>
  </header>

  <!-- About Section -->
  <section id="about" class="about">
    <h2>About Me</h2>
    <p>I'm a 27-year-old UI/UX designer with a passion for creating user-friendly designs that deliver results.</p>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio" class="portfolio">
    <h2>My Work</h2>
    <div class="project">
      <img src="images/project1.jpg" alt="Project 1">
      <h3>Project Title</h3>
      <p>Brief description of the project.</p>
    </div>
    <!-- Add more projects as needed -->
  </section>

  <!-- Services Section -->
  <section id="services" class="services">
    <h2>My Services</h2>
    <ul>
      <li>UI/UX Design for Web & Mobile</li>
      <li>Wireframing & Prototyping</li>
      <li>Usability Testing</li>
      <li>Branding & Visual Design</li>
    </ul>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <form action="#" method="post">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer class="footer">
    <p>© 2024 Samuel Obaro | All Rights Reserved</p>
  </footer>

  <script src="scripts/script.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
}

.hero {
  text-align: center;
  background: #333;
  color: #fff;
  padding: 100px 20px;
}

.hero .btn {
  background: #ff7f50;
  color: #fff;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
}

section {
  padding: 20px;
  margin: 20px auto;
  max-width: 900px;
}

.about, .portfolio, .services, .contact {
  text-align: center;
}

.project {
  display: inline-block;
  margin: 15px;
}

footer {
  text-align: center;
  padding: 10px;
  background: #333;
  color: #fff;
}
document.addEventListener("DOMContentLoaded", () => {
  console.log("Portfolio site ready!");
});
