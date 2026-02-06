
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Name | Full Stack Developer</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- HERO -->
  <header class="hero">
    <h1>Hi, I'm Ram Babu</h1>
    <h2>Sr Software Developer | Full Stack Developer | Java Developer</h2>
    <p>Passionate about creating innovative solutions through code. I specialize in building Enterprise grade applications in the Java ecosystem, Web architecture and cloud native applications.</p>

    <div class="buttons">
      <a href="#projects">View My Work</a>
      <a href="Ram Baburesume.pdf" download>Download Resume</a>
      <a href="#contact">Let's Connect</a>
    </div>
  </header>

  <!-- ABOUT -->
  <section class="about">
    <h2>About Me</h2>
    <p>
      Full-stack developer with 8+ years experience in Java, Spring Boot, Angular,
      Microservices, and Google Cloud Platform. Experienced in building scalable,
      secure, and high-performance enterprise applications.
    </p>
  </section>

  <!-- SKILLS -->
  <section class="skills">
    <h2>Skills</h2>
    <ul>
      <li>Java, Spring Boot, Microservices</li>
      <li>Angular, TypeScript, HTML, CSS</li>
      <li>GCP, Docker, Kubernetes</li>
      <li>SQL, BigQuery, Pub/Sub</li>
      <li>CI/CD, Jenkins, Git</li>
    </ul>
  </section>

  <!-- PROJECTS -->
  <section id="projects">
    <h2>Projects</h2>

    <div class="card">
      <h3>Cloud Microservices Platform</h3>
      <p>Built scalable microservices using Java, Spring Boot, GCP, Kubernetes, and Pub/Sub.</p>
    </div>

    <div class="card">
      <h3>Full Stack Enterprise App</h3>
      <p>Developed Angular + Spring Boot application with secure REST APIs and Cloud SQL.</p>
    </div>

  </section>

  <!-- CONTACT -->
  <section id="contact">
    <h2>Contact</h2>
    <p>Email: yourmail@gmail.com</p>
    <p>LinkedIn: linkedin.com/in/yourprofile</p>
  </section>

</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #f7f7f7;
}

.hero {
  text-align: center;
  padding: 60px;
  background: #1e293b;
  color: white;
}

.buttons a {
  margin: 10px;
  padding: 10px 18px;
  background: #3b82f6;
  color: white;
  text-decoration: none;
  border-radius: 6px;
}

section {
  padding: 40px;
}

.card {
  background: white;
  padding: 15px;
  margin: 10px 0;
  border-radius: 6px;
}

