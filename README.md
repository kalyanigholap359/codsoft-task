<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Kalyani’s Portfolio</title>
  <style>
     {
      margin: 0; padding: 0; box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f7f9fc;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #0d47a1;
      color: white;
      padding: 20px 0;
      text-align: center;
      font-size: 1.8rem;
      font-weight: 700;
      letter-spacing: 2px;
    }
    nav {
      background: #1565c0;
    }
    nav ul {
      max-width: 900px;
      margin: auto;
      display: flex;
      justify-content: center;
      list-style: none;
      padding: 10px 0;
      gap: 30px;
    }
    nav ul li a {
      color: #e3f2fd;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s ease;
    }
    nav ul li a:hover {
      color: #bbdefb;
    }
    
    .hero {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 30px;
    }
    .hero img {
      width: 200px;
      border-radius: 12px;
      flex-shrink: 0;
    }
    .hero-text {
      flex: 1;
    }
    .hero-text h1 {
      font-size: 2.5rem;
      margin-bottom: 15px;
      color: #0d47a1;
    }
    .hero-text p {
      font-size: 1.1rem;
      margin-bottom: 20px;
    }
    
    .btn:hover {
      background: #093c87;
    }
    h2 {
      color: #0d47a1;
      margin-bottom: 15px;
      border-bottom: 2px solid #0d47a1;
      padding-bottom: 5px;
    }
    ul.skills {
      list-style: none;
      display: flex;
      gap: 15px;
      flex-wrap: wrap;
    }
    ul.skills li {
      background: #bbdefb;
      color: #0d47a1;
      padding: 7px 15px;
      border-radius: 20px;
      font-weight: 600;
      font-size: 0.9rem;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
      gap: 20px;
    }
    .project-card {
      background: #e3f2fd;
      border-radius: 10px;r̥
      padding: 15px;
      box-shadow: 0 2px 8px rgb(0 0 0 / 0.1);
    }
    .project-card h3 {
      margin-bottom: 10px;
      color: #0d47a1;
    }
    .project-card p {
      font-size: 0.95rem;
      line-height: 1.4;
    }
    #contact p {
      font-size: 1.1rem;
      margin-bottom: 10px;
    }
    footer {
      text-align: center;
      padding: 20px 10px;
      background: #1565c0;
      color: #e3f2fd;
      margin-top: 40px;
      font-size: 0.9rem;
    }
    @media(max-width:700px) {
      .hero {
        flex-direction: column;
        text-align: center;
      }
      .hero img {
        margin: 0 auto;
      }
      ul.skills {
        justify-content: center;
      }
    }
  </style>
</head>
<body>

<header>Kalyani’s Portfolio</header>

<nav>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#resume">Resume</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<section id="home" class="hero">
  <img src="IMG-20250610-WA0003~3.jpg" alt="Kalyani Gholap" />
  <div class="hero-text">
    <h1>Hi, I’m Kalyani!</h1>
    <p>Web Developer & IT Student passionate about creating clean and modern websites using HTML, CSS, and JavaScript.</p>
    <a href="#" class="btn">Hire Me</a>
  </div>
</section>

<section id="about">
  <h2>About Me</h2>
  <p>I am an enthusiastic learner focusing on building user-friendly web apps. Currently enhancing skills in frontend development and exploring new technologies.</p>
</section>

<section id="skills">
  <h2>Skills</h2>
  <ul class="skills">
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
    <li>React</li>
    <li>Git</li>
    <li>Responsive Design</li>
  </ul>
</section>

<section id="projects">
  <h2>Projects</h2>
  <div class="projects">
    <div class="project-card">
      <h3>Portfolio Website</h3>
      <p>A responsive portfolio website built with HTML, CSS, and JavaScript showcasing my skills and projects.</p>
    </div>
    <div class="project-card">
      <h3>Todo App</h3>
      <p>A simple, interactive todo list app using vanilla JavaScript for managing daily tasks.</p>
    </div>
    <div class="project-card">
      <h3>Weather Dashboard</h3>
      <p>A weather info app using APIs to display current weather and forecasts with clean UI.</p>
    </div>
  </div>
</section>

<section id="resume">
  <h2>Resume</h2>
  <a href="Kalyani_Gholap_Resume.pdf" download class="btn">Download Resume (PDF)</a>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Email: <a href="mailto:kalyani@example.com">kalyani@example.com</a></p>
  <p>Phone: +91 12345 67890</p>
</section>

<footer>
  &copy; 2025 Kalyani Gholap. All rights reserved.
</footer>

</body>
</html>
