<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Irfan  Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    /* Global Styles */
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f1f0f8;
      color: black;
    }

    h1, h2, h3 {
      font-weight: 600;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* Navbar Styles */
    nav {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      background: #1e2a47;
      padding: 20px;
      z-index: 100;
    }

    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
    }

    nav ul li {
      margin: 0 15px;
    }

    nav ul li a {
      color: #fff;
      font-size: 18px;
      text-transform: uppercase;
      letter-spacing: 1px;
      transition: color 0.3s ease;
    }

    nav ul li a:hover {
      color: #ff9900;
    }

    /* Hero Section */
    #hero {
      background-image: url('https://source.unsplash.com/1600x900/?technology');
      background-size: cover;
      background-position: center;
      color: black;
      padding: 100px 0;
      text-align: center;
    }

    #hero h1 {
      font-size: 60px;
      margin-bottom: 20px;
    }

    #hero p {
      font-size: 24px;
      margin-bottom: 40px;
    }

    .cta-btn {
      padding: 10px 20px;
      background-color: #ff9900;
      color: #fff;
      border-radius: 5px;
      font-size: 18px;
      transition: background-color 0.3s ease;
    }

    .cta-btn:hover {
      background-color: #e68a00;
    }

    /* Section Styles */
    section {
      padding: 80px 0;
      text-align: center;
    }

    #about {
      background-color: #f1f0f8;
    }

    #skills {
      background-color: #f9f9f9;
    }

    #projects {
      background-color: #ffffff;
    }

    #contact {
      background-color: #fff;
    }

    /* About Section */
    #about h2 {
      font-size: 36px;
      margin-bottom: 20px;
    }

    #about p {
      font-size: 18px;
      line-height: 1.8;
      width: 60%;
      margin: 0 auto;
    }

    /* Skills Section */
    .skills-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 30px;
    }

    .skill-card {
        background-color: #cccccc;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      width: 200px;
      text-align: center;
    }

    .skill-card h3 {
      font-size: 24px;
      margin-bottom: 15px;
    }

    .skill-card p {
      font-size: 16px;
      color: #666;
    }

    /* Projects Section */
    .project {
      display: inline-block;
      width: 45%;
      margin: 20px 0;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      border-radius: 10px;
      overflow: hidden;
      transition: transform 0.3s ease;
      background-color: #f9f9f9;
    }

    .project:hover {
      transform: translateY(-10px);
    }

    .project img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .project-content {
      padding: 20px;
      text-align: left;
    }

    .project-content h3 {
      font-size: 22px;
      margin-bottom: 10px;
    }

    .project-content p {
      color: #666;
    }

    /* Contact Section */
    #contact h2 {
      font-size: 36px;
      margin-bottom: 20px;
    }

    #contact form {
      display: flex;
      flex-direction: column;
      width: 50%;
      margin: 0 auto;
    }

    input, textarea {
      padding: 15px;
      margin-bottom: 15px;
      border-radius: 5px;
        background-color: #f1f0f8;
        border: #1e2a47;
      font-size: 16px;
    }

    input[type="submit"] {
      background-color: #ff9900;
      color: #fff;
      cursor: pointer;
    }

    input[type="submit"]:hover {
      background-color: #e68a00;
    }

    /* Footer Styles */
    footer {
      background-color: #1e2a47;
      color: #fff;
      text-align: center;
      padding: 20px 0;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav>
    <ul>
      <li><a href="#hero">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- Hero Section -->
  <section id="hero">
    <img src="irfanIMG.jpg"  height="300" width="300">
    <h2>My Profile</h2>
    <h1>Welcome to My Portfolio</h1>
    <h1> Irfan Sathik Ali . J</h1>
    <p>I'm a Web Developer Passionate About Creating Beautiful Web Experiences</p>
    <a href="#projects" class="cta-btn">View My Work</a>
  </section>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm a passionate web developer with a love for crafting modern websites and applications. I specialize in front-end technologies like HTML, CSS, JavaScript, and React, but I also have experience with back-end development. I enjoy solving complex problems and bringing ideas to life on the web.</p>
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="skills-container">
      <div class="skill-card">
        <h3>HTML</h3>
        <p>Building the structure of websites</p>
      </div>
      <div class="skill-card">
        <h3>CSS</h3>
        <p>Designing stylish and responsive layouts</p>
      </div>
      <div class="skill-card">
        <h3>JavaScript</h3>
        <p>Creating interactive and dynamic web pages</p>
      </div>
      <div class="skill-card">
        <h3>React</h3>
        <p>Building modern single-page applications</p>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <img src="irfan1.html" alt="Project Image">
      <div class="project-content">
        <h3>Project 1</h3>
        <p>A web application that allows users to create and manage tasks.</p>
      </div>
    </div>
    <div class="project">
      <img src="https://via.placeholder.com/400x200" alt="Project Image">
      <div class="project-content">
        <h3>Project 2</h3>
        <p>A personal blog website built with React and styled-components.</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <form action="#" method="POST">
      <input type="text" name="name" placeholder="Enter your name" required>
      <input type="email" name="email" placeholder="Email address" required>
      <textarea name="message" rows="5" placeholder="Your message" required></textarea>
      <input type="submit" value="Send message">
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 My Portfolio | Designed by Me</p>
  </footer>

</body>
</html>
