<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vishal Pinjeera | Portfolio</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Poppins', sans-serif; background: #000; color: #fff; }

    header { background: #111; color: #fff; padding: 1.5rem 0; text-align: center; }
    header h1 { font-size: 2rem; }
    header p { font-size: 1.1rem; opacity: 0.8; }
    header .email { font-size: 1rem; color: #00bcd4; margin-top: 0.3rem; }

    nav { background: #222; display: flex; justify-content: center; flex-wrap: wrap; gap: 1.5rem; padding: 1rem; }
    nav a { color: #fff; text-decoration: none; font-weight: 500; }
    nav a:hover { color: #00bcd4; }

    section { padding: 3rem 10%; }
    section h2 { font-size: 2rem; margin-bottom: 1.5rem; border-bottom: 3px solid #00bcd4; display: inline-block; }

    .about-container { display: flex; align-items: center; justify-content: flex-start; flex-wrap: wrap; gap: 2rem; }
    .about-text { flex: 1; min-width: 280px; }
    .about-img { flex: 1; text-align: left; }
    .about-img img { width: 380px; height: 380px; object-fit: cover; border-radius: 50%; border: 4px solid #00bcd4; box-shadow: 0 0 25px rgba(0,188,212,0.6); transition: transform 0.3s ease; }
    .about-img img:hover { transform: scale(1.05); }

    .skills-list { display: flex; flex-wrap: wrap; gap: 1rem; }
    .skill { background: #00bcd4; color: #fff; padding: 0.7rem 1.2rem; border-radius: 25px; font-weight: 500; }

    .projects-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1.5rem; }
    .project { background: #111; border-radius: 10px; box-shadow: 0 4px 10px rgba(255,255,255,0.1); padding: 1.5rem; transition: transform 0.3s ease; }
    .project:hover { transform: translateY(-5px); }
    .project h3 { margin-bottom: 0.5rem; color: #00bcd4; }
    .project p { font-size: 0.95rem; margin-bottom: 1rem; color: #ddd; }
    .project a { color: #00bcd4; text-decoration: none; font-weight: 600; }

    .contact { text-align: center; }
    .contact p { font-size: 1rem; margin-bottom: 1rem; }
    .contact a { color: #00bcd4; text-decoration: none; font-weight: 500; }
    .contact a:hover { text-decoration: underline; }

    .contact form { max-width: 500px; margin: 0 auto; display: flex; flex-direction: column; gap: 1rem; }
    .contact input, .contact textarea { padding: 0.8rem; border: 1px solid #444; border-radius: 5px; width: 100%; background: #111; color: #fff; }
    .contact button { padding: 0.8rem; background: #00bcd4; color: #fff; border: none; border-radius: 5px; cursor: pointer; font-weight: 600; }
    .contact button:hover { background: #0097a7; }

    footer { background: #111; color: #fff; text-align: center; padding: 1.5rem; }
    footer p { font-size: 0.9rem; }

    /* Responsive Design */
    @media (max-width: 768px) {
      .about-container { flex-direction: column; text-align: center; }
      .about-img { text-align: center; }
      .about-img img { width: 250px; height: 250px; margin: 0 auto; }
      section { padding: 2rem 5%; }
    }

    @media (max-width: 480px) {
      header h1 { font-size: 1.6rem; }
      header p { font-size: 1rem; }
      nav { flex-direction: column; gap: 0.8rem; }
      .about-img img { width: 200px; height: 200px; }
    }
  </style>
</head>
<body>
  <header>
    <h1>Vishal Pinjeera</h1>
    <p>Full Stack Developer</p>
    <p class="email">vishalpinjeera612@gmail.com</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about" class="about">
    <h2>About Me</h2>
    <div class="about-container">
      <div class="about-text">
        <p>Hello! I'm Vishal Pinjeera, a passionate Full Stack Developer with strong skills in building responsive, efficient, and user-friendly websites using modern web technologies. I enjoy learning new tools and frameworks to continuously improve my craft and deliver high-quality results.</p>
      </div>
      <div class="about-img">
        <img src="your-photo.jpg" alt="Vishal Pinjeera Photo">
      </div>
    </div>
  </section>

  <section id="skills" class="skills">
    <h2>Skills</h2>
    <div class="skills-list">
      <div class="skill">HTML</div>
      <div class="skill">CSS</div>
      <div class="skill">JavaScript</div>
      <div class="skill">GitHub</div>
    </div>
  </section>

  <section id="projects" class="projects">
    <h2>Projects</h2>
    <div class="projects-grid">
      <div class="project">
        <h3>Portfolio Website</h3>
        <p>A personal portfolio website built with HTML, CSS, and JavaScript to showcase my projects and experience.</p>
        <a href="#">View Project</a>
      </div>
      <div class="project">
        <h3>To-Do App</h3>
        <p>A simple to-do list application created with JavaScript that allows users to add, delete, and mark tasks as completed.</p>
        <a href="#">View Project</a>
      </div>
      <div class="project">
        <h3>Weather App</h3>
        <p>Displays live weather information using an external API and provides a clean, responsive user interface.</p>
        <a href="#">View Project</a>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>You can reach me directly at <a href="mailto:vishalpinjeera612@gmail.com">vishalpinjeera612@gmail.com</a></p>
    <form onsubmit="sendMessage(event)">
      <input type="text" id="name" placeholder="Your Name" required>
      <input type="email" id="email" placeholder="Your Email" required>
      <textarea id="message" placeholder="Your Message" rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© <span id="year"></span> Vishal Pinjeera. All Rights Reserved.</p>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();

    function sendMessage(e) {
      e.preventDefault();
      const name = document.getElementById('name').value;
      const email = document.getElementById('email').value;
      const message = document.getElementById('message').value;
      if (name && email && message) {
        alert(`Thank you, ${name}! Your message has been sent.`);
        e.target.reset();
      }
    }
  </script>
</body>
</html>
