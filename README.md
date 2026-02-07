
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ram Babu | Full Stack Developer</title>
  <link rel="stylesheet" href="style.css" />
</head>

<body>

<!-- NAVBAR -->
<nav class="nav">
  <a class="nav-logo" href="#home">RB</a>

  <div class="nav-links">
    <a href="#skills">Expertise</a>
    <a href="#experience">History</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </div>

  <button class="theme-btn" id="themeBtn" aria-label="Toggle theme">☀</button>
</nav>

<!-- HERO -->
<header class="hero hero-wave" id="home">

  <!-- WAVE BACKGROUND (this creates the purple curve like the picture) -->
  <div class="wave-wrap" aria-hidden="true">
    <svg class="wave" viewBox="0 0 1440 420" preserveAspectRatio="none">
      <defs>
        <linearGradient id="grad" x1="0" y1="0" x2="1" y2="0">
          <stop offset="0%" stop-color="#ff2bd6" stop-opacity="0.95"/>
          <stop offset="55%" stop-color="#8b2cff" stop-opacity="0.95"/>
          <stop offset="100%" stop-color="#5c7cfa" stop-opacity="0.85"/>
        </linearGradient>

        <filter id="glow">
          <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
          <feMerge>
            <feMergeNode in="coloredBlur"/>
            <feMergeNode in="SourceGraphic"/>
          </feMerge>
        </filter>
      </defs>

      <!-- striped wave lines -->
      <path class="wave-line" d="M0,270 C260,340 420,150 720,210 C1000,270 1120,70 1440,160" />
      <path class="wave-line" d="M0,285 C260,355 420,165 720,225 C1000,285 1120,85 1440,175" />
      <path class="wave-line" d="M0,300 C260,370 420,180 720,240 C1000,300 1120,100 1440,190" />
      <path class="wave-line" d="M0,315 C260,385 420,195 720,255 C1000,315 1120,115 1440,205" />
      <path class="wave-line" d="M0,330 C260,400 420,210 720,270 C1000,330 1120,130 1440,220" />
      <path class="wave-line" d="M0,345 C260,415 420,225 720,285 C1000,345 1120,145 1440,235" />
      <path class="wave-line" d="M0,360 C260,430 420,240 720,300 C1000,360 1120,160 1440,250" />
    </svg>
  </div>

  <!-- HERO CONTENT -->
  <div class="hero-inner">
    <div class="avatar">
      <!-- put your image in repo: assets/profile.jpg -->
      <img src="assets/profile.jpg" alt="Ram Babu photo" />
    </div>

    <div class="hero-content">
      <div class="social">
        <a href="https://github.com/" target="_blank" aria-label="GitHub">⌂</a>
        <a href="https://www.linkedin.com/in/rambabu64681" target="_blank" aria-label="LinkedIn">in</a>
      </div>

      <h1 class="hero-title">Ram Babu</h1>
      <p class="hero-sub">Sr Software Developer | Full Stack | Java</p>

      <p class="hero-desc">
        Passionate about creating enterprise-grade applications with strong focus on scalability,
        performance, security, and cloud-native architecture.
      </p>

      <div class="hero-actions">
        <a class="btn primary" href="#projects">View My Work</a>
        <a class="btn" href="resume.pdf" download>Download Resume</a>
        <a class="btn" href="#contact">Let's Connect</a>
      </div>
    </div>
  </div>

</header>



  <!-- PROJECTS -->
  <section id="projects" class="section">
    <h2>View My Work</h2>

    <p>
      Over the course of my career, I have contributed to the design and development of high-impact
      software systems across healthcare, finance, retail, and customer service domains. I have built
      full-stack applications using modern frameworks like React, Angular, and Java Spring Boot,
      focusing on scalability, performance, and secure architecture.
    </p>
  </section>


  <!-- CONTACT -->
  <section id="contact" class="section">
    <h2>Contact</h2>

    <p><strong>Name:</strong> Ram Babu</p>
    <p><strong>Email:</strong> Rambabu64681@gmail.com</p>
    <p><strong>Phone:</strong> 860-600-5205</p>
    <p><strong>LinkedIn:</strong> https://www.linkedin.com/in/rambabu64681</p>
    <p><strong>Location:</strong> East Windsor, CT, USA</p>
  </section>


</body>
</html>


   
  <h2>View My Work</h2>

  <p class="work-intro">
    Over the course of my career, I have contributed to the design and development of high-impact software systems across healthcare, finance, retail, and customer service domains. I have built full-stack applications with modern frameworks like React, Angular, and React Native, delivering user-centric interfaces for both web and mobile platforms. On the backend, I have engineered scalable microservices and real-time data systems using Java, Spring Boot, Node.js, and Kafka—focusing on performance, modularity, and security.

My work includes developing intelligent mobile assistants for retail associates, enterprise-grade EHR systems for clinicians, real-time chat support platforms, and digital investment tools—all hosted on robust cloud infrastructures (AWS & Azure). I’ve ensured system reliability through thorough testing, CI/CD automation, and implemented industry-standard protocols like OAuth2, HL7, and HIPAA for secure and compliant applications. This diverse experience reflects my strength in building enterprise solutions that are performant, maintainable, and aligned with user and business needs.
  </p>

</section>

      
<section id="contact" class="section">
  <h2>Let's Connect</h2>
  <p>I’m open to full-time roles, contract opportunities, and technical discussions.</p>

  <div class="contact-box">

    <p><strong>Name:</strong> Ram Babu</p>

    <p>
      <strong>Email:</strong>
      <a href="mailto:Rambabu64681@gmail.com">
        Rambabu64681@gmail.com
      </a>
    </p>

    <p>
      <strong>Phone:</strong>
      <a href="tel:+18606005205">
        860-600-5205
      </a>
    </p>

    <p>
      <strong>LinkedIn:</strong>
      <a href="https://www.linkedin.com/in/rambabu64681" target="_blank">
        www.linkedin.com/in/rambabu64681
      </a>
    </p>

    <p><strong>Location:</strong> 06088, East Windsor, CT</p>

    <!-- Optional Buttons -->
    <div style="margin-top:15px;">
      


    </div>
  

  <!-- ABOUT -->
  <section class="about">
    <h2>About Me</h2>
    <p>
      Full-stack developer with 8+ years experience in Java, Spring Boot, Angular,
      Microservices, and Google Cloud Platform. Experienced in building scalable,
      secure, and high-performance enterprise applications.
    </p>
  </section>

 


  <!-- PROFESSIONAL SUMMARY -->
<section id="summary">
  <h2>Professional Summary</h2>
  <div class="card">
    <p>
      Software Engineer with <strong>8+ years of experience</strong> building scalable, secure, and high-performance enterprise
      applications using <strong>Java, React, Spring Boot, and G Cloud Platforms </strong>.
      Proven ability to design responsive frontend systems, optimize cloud deployments, and deliver real-time,
      data-driven web applications across financial and healthcare domains.
    </p>
  </div>
</section>


<!-- EXPERIENCE -->
<section id="experience">
  <h2>Professional Experience</h2>

  <!-- WESTERN UNION -->
  <div class="card">
    <h3>Western Union — Software Developer</h3>
    <p>Dec 2024 – Present · Massachusetts, United States · Remote</p>
    <ul>

      <li>Delivered high-volume financial applications under strict latency targets, improving response time by 41% using <strong>Java, Spring Boot, Microservices, REST APIs</strong> while supporting millions of secure transactions daily.</li>

      <li>Improved customer interaction speed and engagement by redesigning UI rendering using <strong>React, HTML5, CSS3, Performance Optimization</strong>, reducing page load time from 3.1s to 1.3s across browsers.</li>

      <li>Strengthened backend scalability during peak transaction loads using <strong>Java, Multithreading, Caching, Distributed Systems</strong>, increasing throughput by 52% without impacting reliability.</li>

      <li>Reduced infrastructure and runtime cost by optimizing deployments through <strong>Cloud Architecture, Containerization, Auto Scaling, Load Balancing</strong>, saving 27% compute expenses under production workload.</li>

      <li>Achieved 99.97% uptime by implementing proactive observability using <strong>Logging, Metrics, Monitoring, Performance Tracking</strong>, improving incident detection and resolution time significantly.</li>

      <li>Accelerated release frequency and reduced deployment risk by automating pipelines with <strong>CI/CD, Docker, Git, Build Automation</strong>, cutting manual errors and enabling faster production delivery.</li>

      <li>Enhanced real-time transaction processing performance using <strong>Event Driven Architecture, Messaging, Async Processing</strong>, improving system response speed by 36% under concurrent user traffic.</li>

      <li>Improved software quality and reduced production defects by implementing automation using <strong>Unit Testing, Integration Testing, JUnit, Test Automation</strong>, lowering critical bugs by 45%.</li>

    </ul>
  </div>


  <!-- LEGACY HEALTH -->
  <div class="card">
    <h3>Legacy Health — Software Developer</h3>
    <p>Sep 2023 – Nov 2024 · Oregon, United States · Remote</p>
    <ul>

      <li>Delivered secure healthcare applications handling sensitive data with strict compliance, improving response latency by 38% using <strong>Java, Spring Boot, REST APIs, Backend Architecture</strong>.</li>

      <li>Improved patient portal usability and engagement by optimizing UI rendering using <strong>React, State Management, HTML5, CSS3</strong>, increasing user session duration by 32%.</li>

      <li>Handled peak healthcare data load efficiently using <strong>Java, Multithreading, Caching, Distributed Processing</strong>, improving backend throughput by 48% without service degradation.</li>

      <li>Optimized cloud resource usage under budget constraints using <strong>Cloud Deployment, Containerization, Load Balancing, Auto Scaling</strong>, reducing operational cost by 24%.</li>

      <li>Improved system reliability and achieved 99.95% uptime by implementing proactive monitoring with <strong>Logging, Observability, Metrics, Performance Monitoring</strong>.</li>

      <li>Accelerated secure feature delivery by automating build and release flow using <strong>CI/CD, Git, Docker, Automation Pipelines</strong>, improving deployment success rate significantly.</li>

      <li>Enhanced real-time healthcare data synchronization using <strong>Messaging, Async Processing, Event Driven Architecture</strong>, improving processing speed and system responsiveness by 34%.</li>

      <li>Reduced post-release defects by strengthening validation and automation using <strong>Unit Testing, Integration Testing, Test Automation, JUnit</strong>, improving production quality and stability.</li>

    </ul>
  </div>


  <!-- TCS -->
  <div class="card">
    <h3>Tata Consultancy Services — Software Engineer</h3>
    <p>Dec 2019 – Aug 2023 · Hyderabad, India · On-site</p>
    <ul>

      <li>Delivered enterprise-grade applications under heavy workloads improving response time by 43% using <strong>Java, Spring Boot, REST APIs, Microservices Architecture</strong>.</li>

      <li>Enhanced frontend rendering efficiency and user engagement by redesigning UI flow using <strong>React, HTML5, CSS3, Performance Optimization</strong>, reducing latency significantly.</li>

      <li>Improved backend system throughput under concurrent traffic using <strong>Java, Multithreading, Caching, Distributed Systems</strong>, increasing processing efficiency by 50%.</li>

      <li>Optimized resource utilization and reduced operational cost using <strong>Cloud Infrastructure, Containerization, Auto Scaling, Load Balancing</strong>, improving runtime performance.</li>

      <li>Strengthened application uptime to 99.94% by implementing proactive monitoring using <strong>Logging, Metrics, Monitoring, Observability</strong>.</li>

      <li>Improved release consistency and reduced deployment failures using <strong>CI/CD, Docker, Git, Automation Pipelines</strong>, accelerating production delivery cycles.</li>

      <li>Enhanced real-time system communication speed using <strong>Event Driven Architecture, Messaging, Async Processing</strong>, improving application responsiveness.</li>

      <li>Reduced production defects and improved stability using <strong>Unit Testing, Integration Testing, Test Automation, JUnit</strong>, strengthening software quality.</li>

    </ul>
  </div>


  <!-- PIPRA -->
  <div class="card">
    <h3>PIPRA Solutions — Associate Software Engineer</h3>
    <p>Jan 2018 – Nov 2019 · Hyderabad, India · On-site</p>
    <ul>

      <li>Delivered responsive web interfaces improving rendering performance by 36% using <strong>JavaScript, React, HTML5, CSS3, UI Optimization</strong> across devices.</li>

      <li>Built stable backend communication layers improving response speed using <strong>Java, REST APIs, Backend Processing, JSON</strong> for enterprise data flow.</li>

      <li>Improved application throughput and stability under load using <strong>Java, Multithreading, Caching, Performance Optimization</strong>.</li>

      <li>Optimized deployment efficiency and reduced runtime cost using <strong>Cloud Deployment, Containerization, Resource Optimization</strong>.</li>

      <li>Strengthened production stability by implementing monitoring using <strong>Logging, Metrics, Observability, Performance Tracking</strong>.</li>

      <li>Improved delivery speed and reduced manual work using <strong>CI/CD, Git, Docker, Automation</strong>.</li>

      <li>Enhanced real-time processing capability using <strong>Messaging, Event Driven Architecture, Async Processing</strong>, improving system responsiveness.</li>

      <li>Improved software reliability and reduced bugs using <strong>Unit Testing, Integration Testing, Test Automation, JUnit</strong>.</li>

    </ul>
  </div>

</section>

<!-- TECHNICAL SKILLS -->
<section id="skills">
  <h2>Technical Skills</h2>
  <p>Technologies and tools I work with</p>

  <div class="card">

    <h3>Frontend Development</h3>
    <ul>
      <li>React.js & React Native</li>
      <li>Angular & TypeScript</li>
      <li>Redux & Context API</li>
      <li>HTML5, CSS3, Tailwind CSS</li>
      <li>Responsive & Cross-Platform UI</li>
    </ul>

    <h3>Backend & Microservices</h3>
    <ul>
      <li>Java (Spring Boot, Spring MVC, Spring Security)</li>
      <li>Microservices Architecture</li>
      <li>RESTful API Design</li>
      <li>Kafka & RabbitMQ Messaging</li>
      <li>OAuth2, JWT & API Security</li>
    </ul>

    <h3>Databases & Storage</h3>
    <ul>
      <li>MySQL & PostgreSQL</li>
      <li>MongoDB & Cassandra</li>
      <li>Hibernate & Spring Data JPA</li>
      <li>SQL, PL/SQL</li>
      <li>Data Modeling & Query Optimization</li>
    </ul>

    <h3>Cloud & DevOps</h3>
    <ul>
      <li>AWS (EC2, S3, Lambda, VPC)</li>
      <li>Azure Cloud Services</li>
      <li>Docker & Kubernetes</li>
      <li>CI/CD (Jenkins, Azure DevOps, GitHub Actions)</li>
      <li>Git & GitHub</li>
    </ul>

    <h3>Testing & Monitoring</h3>
    <ul>
      <li>JUnit, Mockito, Cypress</li>
      <li>Selenium, Test Automation</li>
      <li>Integration Testing & Testcontainers</li>
      <li>Logging, Monitoring, Observability</li>
      <li>Performance Testing & Debugging</li>
    </ul>

    <h3>Architecture & Design</h3>
    <ul>
      <li>System Architecture Design</li>
      <li>Distributed Systems</li>
      <li>Event-Driven Architecture</li>
      <li>Scalable & High-Performance Systems</li>
      <li>Secure Application Design</li>
    </ul>

  </div>
</section>


<!-- CERTIFICATIONS -->
<section id="certifications">
  <h2>Certifications</h2>

  <div class="card">
    <h3>AWS Certified Data Engineer – Associate</h3>
    <ul>
      <li>Achieved <strong>AWS Certified Data Engineer – Associate</strong>, demonstrating hands-on expertise in <strong>AWS Data Services, ETL Pipelines, Data Integration, Data Processing</strong>, supporting scalable and reliable data workflows for enterprise Java microservices.</li>
    </ul>
  </div>

</section>

<!-- EDUCATION -->
<section id="education">
  <h2>Education</h2>

  <!-- MASTER'S -->
  <div class="card">
    <h3>Master of Science in Computer Science</h3>
    <p><strong>Northern Arizona University</strong> · Arizona, United States</p>
    <ul>
      <li>Completed Master’s degree with strong focus on <strong>Software Engineering, Distributed Systems, Cloud Computing, Data Processing</strong>, building advanced technical and problem-solving skills.</li>
      <li>Graduated with a GPA of <strong>3.8 / 4.0</strong>, demonstrating consistent academic excellence and deep understanding of computer science fundamentals.</li>
    </ul>
  </div>

  <!-- BACHELOR'S -->
  <div class="card">
    <h3>Bachelor of Technology in Computer Science</h3>
    <p><strong>Jawaharlal Nehru Technological University, Kakinada</strong> · India</p>
    <ul>
      <li>Built strong foundation in <strong>Programming, Data Structures, Algorithms, Database Systems, Software Development</strong>, supporting long-term engineering expertise.</li>
      <li>Graduated with a GPA of <strong>8.1 / 10.0</strong>, maintaining solid academic performance and technical consistency throughout the program.</li>
    </ul>
  </div>

</section>





  <!-- CONTACT -->
  <section id="contact">
    <h2>Contact</h2>
    <p>Email: yourmail@gmail.com</p>
    <p>LinkedIn: linkedin.com/in/yourprofile</p>
  </section>

/* ===== Base ===== */
:root{
  --bg1:#0b1020;          /* deep navy */
  --bg2:#0a1733;          /* blue navy */
  --card: rgba(255,255,255,.07);
  --border: rgba(255,255,255,.12);
  --text:#e5e7eb;
  --muted:#a7b0c0;

  --accent:#38bdf8;       /* sky */
  --accent2:#a78bfa;      /* violet */
  --accent3:#22c55e;      /* java-green optional */
}

*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  margin:0;
  font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  color:var(--text);

  /* Premium background */
  background:
    radial-gradient(900px 500px at 15% 10%, rgba(56,189,248,.22), transparent 60%),
    radial-gradient(900px 500px at 85% 20%, rgba(167,139,250,.18), transparent 60%),
    radial-gradient(800px 600px at 50% 90%, rgba(34,197,94,.10), transparent 60%),
    linear-gradient(135deg, var(--bg1), var(--bg2));
}

/* ===== Layout ===== */
.section, section{
  padding: 56px 18px;
  max-width: 1080px;
  margin: 0 auto;
}
h1,h2,h3{margin:0 0 12px 0; line-height:1.2}
p{color:var(--muted); line-height:1.7}

/* ===== Top Navbar (add in HTML) ===== */
.nav{
  position: sticky;
  top: 0;
  z-index: 50;
  backdrop-filter: blur(10px);
  background: rgba(2,6,23,.55);
  border-bottom: 1px solid rgba(255,255,255,.08);
}
.nav-inner{
  max-width:1080px;
  margin:0 auto;
  padding: 12px 18px;
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:14px;
}
.brand{
  font-weight:700;
  letter-spacing:.2px;
  color: var(--text);
  text-decoration:none;
}
.nav a{
  color: var(--muted);
  text-decoration:none;
  font-size:14px;
  margin-left:14px;
}
.nav a:hover{color:var(--text)}

/* ===== Hero ===== */
.hero{
  padding: 76px 18px 44px;
  text-align:center;
  max-width:1080px;
  margin:0 auto;
}
.hero h1{
  font-size: clamp(32px, 4vw, 46px);
  background: linear-gradient(90deg, var(--accent), var(--accent2));
  -webkit-background-clip: text;
  background-clip:text;
  color:transparent;
}
.hero h2{
  font-size: 16px;
  font-weight:600;
  color: var(--muted);
  margin-top:8px;
}
.hero p{
  max-width: 850px;
  margin: 16px auto 0;
}

/* ===== Buttons ===== */
.buttons{
  display:flex;
  flex-wrap:wrap;
  justify-content:center;
  gap:12px;
  margin-top: 22px;
}
.btn, .buttons a{
  display:inline-flex;
  align-items:center;
  justify-content:center;
  gap:8px;
  padding: 11px 16px;
  border-radius: 10px;
  border: 1px solid rgba(255,255,255,.12);
  background: rgba(255,255,255,.06);
  color: var(--text);
  text-decoration:none;
  transition: transform .15s ease, background .15s ease, border-color .15s ease;
}
.btn:hover, .buttons a:hover{
  transform: translateY(-1px);
  background: rgba(255,255,255,.10);
  border-color: rgba(56,189,248,.35);
}
.btn.primary{
  background: linear-gradient(90deg, rgba(56,189,248,.85), rgba(167,139,250,.85));
  border-color: rgba(255,255,255,.10);
  color: #06101f;
  font-weight:700;
}

/* ===== Section headings ===== */
section > h2{
  font-size: 22px;
  letter-spacing:.2px;
  display:inline-block;
  padding-bottom: 8px;
  border-bottom: 1px solid rgba(255,255,255,.12);
  margin-bottom: 18px;
  color: #f8fafc;
}
section > h2::after{
  content:"";
  display:block;
  height:3px;
  width:64px;
  margin-top:10px;
  border-radius:999px;
  background: linear-gradient(90deg, var(--accent), var(--accent2));
}

/* ===== Cards ===== */
.card{
  background: var(--card);
  border: 1px solid var(--border);
  border-radius: 14px;
  padding: 18px;
  margin: 14px 0;
  box-shadow: 0 10px 24px rgba(0,0,0,.25);
}
.card h3{
  font-size: 18px;
  color: #f1f5f9;
}
.card p{margin: 8px 0 0}

/* ===== Lists ===== */
ul{padding-left: 18px; margin: 12px 0 0}
li{margin: 10px 0; color: var(--muted); line-height:1.6}

/* Highlight skill tags in middle */
strong{
  color: #0b1020;
  background: rgba(56,189,248,.85);
  padding: 2px 8px;
  border-radius: 999px;
  font-weight: 700;
}

/* ===== Contact box ===== */
.contact-box{
  background: rgba(255,255,255,.06);
  border: 1px solid rgba(255,255,255,.12);
  border-radius: 14px;
  padding: 18px;
}
.contact-box a{color: var(--accent); text-decoration:none}
.contact-box a:hover{text-decoration:underline}

/* ===== Footer (optional) ===== */
.footer{
  text-align:center;
  padding: 24px 18px 40px;
  color: var(--muted);
  font-size: 14px;
}

}


