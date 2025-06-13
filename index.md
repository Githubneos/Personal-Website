---
layout: base
hide: true
image: /images/mario_animation.png
---

<!-- Main Content Area -->
<div class="main-content">
  <div class="page-title">
    <h1>Keerthan Karumudi</h1>
    <p>Student at Del Norte High School | Aspiring Aerospace engineer | Electricity and Magnetism intern at UCSD | Pilot City intern | STEM Innovator | Robotics Enthusiast |</p>
  </div>

  <div class="about-container">
    <!-- Profile and Links Side-by-Side -->
    <div class="profile-links-wrapper">
      <!-- Profile Picture -->
      <img src="images/pfp.JPEG" alt="Profile Picture" width="300" height="400">
<!-- Links Section -->
      <div class="links">
        <a class="link-card email" href="mailto:karumudikeerthan@gmail.com">
          <i class="fas fa-envelope"></i>
          <div class="content">
            <h4>Email</h4>
            <p>karumudikeerthan@gmail.com</p>
          </div>
        </a>
        <a class="link-card github" href="https://github.com/Githubneos">
          <i class="fab fa-github"></i>
          <div class="content">
            <h4>GitHub</h4>
            <p>github.com/Githubneos</p>
          </div>
        </a>
        <a class="link-card linkedin" href="https://www.linkedin.com/in/keerthan-karumudi-016699368/">
          <i class="fab fa-linkedin"></i>
          <div class="content">
            <h4>LinkedIn</h4>
            <p>linkedin.com/in/Keerthank</p>
          </div>
        </a>
        <a class="link-card resume" href="https://www.canva.com/design/DAGqMqKJxKQ/uIO9Cu6XeHyBzHG-_7Ageg/edit">
          <i class="fas fa-file-alt"></i>
          <div class="content">
            <h4>Resume</h4>
            <p>View my resume</p>
          </div>
        </a>
        <a class="link-card onshape" href="https://cad.onshape.com/documents?resourceType=resourceuserowner&nodeId=672eaeee5c1e190ae6501ec7">
          <i class="fas fa-cube"></i>
          <div class="content">
            <h4>Onshape</h4>
            <p>See my CAD work</p>
          </div>
        </a>
      </div>
    </div>
  </div>
</div>

<!-- External FontAwesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<!-- Custom Styles -->
<style>
  body {
    background-color: #001f3f; /* Navy blue */
    color: white;
    font-family: 'Inter', sans-serif;
    padding: 2rem;
  }

  .main-content {
    max-width: 1200px;
    margin: 0 auto;
  }

  .page-title {
    text-align: center;
    margin-bottom: 2rem;
  }

  .page-title h1 {
    font-size: 3rem;
    color: #ffcc00; /* Yellow */
  }

  .page-title p {
    font-size: 1.2rem;
    color: #ff9933; /* Orange */
  }

  .profile-links-wrapper {
    display: flex;
    flex-wrap: wrap;
    gap: 2.5rem;
    justify-content: center;
    align-items: center;
  }

  .profile-picture img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    border: 4px solid #ffcc00;
    box-shadow: 0 0 15px rgba(255, 204, 0, 0.6);
    animation: float 4s ease-in-out infinite;
  }

  @keyframes float {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-8px); }
  }

  .links {
    display: flex;
    flex-direction: column;
    gap: 1.2rem;
  }

  .link-card {
    background-color: rgba(255, 153, 51, 0.1); /* Orange tint */
    border-left: 4px solid #ffcc00;
    padding: 1rem;
    border-radius: 12px;
    display: flex;
    align-items: center;
    gap: 1rem;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    transition: background 0.3s ease, transform 0.3s ease;
  }

  .link-card:hover {
    background-color: rgba(255, 153, 51, 0.2);
    transform: translateY(-4px);
  }

  .link-card i {
    font-size: 1.6rem;
    color: #ffcc00;
  }

  .link-card h4,
  .link-card p {
    margin: 0;
  }

  .link-card h4 {
    color: white;
  }

  .link-card p {
    color: #ffcc00;
    font-size: 0.95rem;
  }

  .about-section {
    background-color: rgba(255, 255, 255, 0.05);
    border: 2px solid #ffcc00;
    border-radius: 16px;
    margin: 5rem auto 2rem;
    padding: 2.5rem;
    max-width: 900px;
    box-shadow: 0 2px 18px rgba(255, 255, 0, 0.1);
  }

  .about-section h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
    color: #ffcc00;
    text-align: center;
  }

  .about-section p,
  .about-section li {
    font-size: 1rem;
    line-height: 1.6;
    color: white;
  }

  .about-section ul {
    list-style: none;
    padding-left: 0;
    margin-top: 1rem;
  }

  .about-section li {
    margin-bottom: 1rem;
    background: rgba(255, 255, 255, 0.05);
    padding: 1rem;
    border-left: 4px solid #ff9933;
    border-radius: 8px;
  }
</style>

<!-- About Me Section -->
<div class="about-section">
  <h2>About Me</h2>
  <p>
    I focus on building practical, impactful solutions at the intersection of software, science, and education.
  </p>
  <ul>
    <li><strong>Software Development:</strong> Built full-stack apps and backend systems at PilotCity and Open Coding Society.</li>
    <li><strong>Physics Research:</strong> Explored magnetized plasma interactions at UC San Diego.</li>
    <li><strong>Technical Design:</strong> Led Blender and Onshape projects as 3D Animation Club VP, teaching students advanced modeling.</li>
    <li><strong>STEM Education:</strong> Developed curriculum for aerospace-themed outreach programs for K–12 students through Project Flight.</li>
    <li><strong>Team Leadership:</strong> Served as Robot design and fabrication lead in FRC team Optix.</li>
    <li><strong>Mission-Driven:</strong> Dedicated to making engineering more accessible and inspiring curiosity through real-world projects.</li>
  </ul>
</div>
