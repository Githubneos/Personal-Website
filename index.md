---
layout: base
title: Keerthan Karumudo
description: Home Page
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
      <div class="profile-picture">
        <img src="/images/profile.jpg" alt="Profile Picture">
      </div>
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
        <a class="link-card resume" href="https://www.canva.com/design/DAGp7N7WX1o/ZzquNIIBr2z0hGxQblvh6g/edit?utm_content=DAGp7N7WX1o&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton">
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
    background: linear-gradient(135deg, #ff9900, #007acc, #ffe600);
    color: #fffbe6;
    font-family: 'Inter', sans-serif;
    padding: 2rem;
  }

  .profile-links-wrapper {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
    justify-content: center;
    align-items: flex-start;
  }

  .profile-picture img {
    width: 180px;
    height: 180px;
    border-radius: 50%;
    box-shadow: 0 0 15px rgba(255, 255, 255, 0.2);
    border: 3px solid #ffe600;
    animation: float 3s ease-in-out infinite;
  }

  @keyframes float {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-10px); }
  }

  .links {
    display: flex;
    flex-direction: column;
    gap: 1.2rem;
  }

  .link-card {
    background: rgba(255, 255, 255, 0.1);
    padding: 1rem;
    border-radius: 16px;
    display: flex;
    align-items: center;
    gap: 1rem;
    transition: transform 0.3s ease, background 0.3s ease;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
  }

  .link-card:hover {
    transform: translateY(-5px);
    background: rgba(255, 255, 255, 0.15);
  }

  .link-card i {
    font-size: 1.8rem;
    color: #ffe600;
  }

  .link-card h4 {
    margin: 0;
    color: #ffffff;
  }

  .link-card p {
    margin: 0;
    color: #ffe600;
    font-size: 0.9rem;
  }
</style>

<!-- About Me Section -->
<div style="font-family: Arial, sans-serif; max-width: 700px; margin: 4rem auto; padding: 1.5rem; border: 1px solid #ffe600; border-radius: 12px; background-color: rgba(255,255,255,0.05); box-shadow: 0 2px 12px rgba(255,255,0,0.2);">
  <h2 style="font-size: 1.8rem; color: #ffe600;">About Me</h2>
  <p style="font-size: 1rem; color: #fffbe6; line-height: 1.6;">
    I focus on building practical, impactful solutions at the intersection of software, science, and education.
  </p>
  <ul style="list-style: none; padding-left: 0; margin-top: 1rem;">
    <li style="margin-bottom: 0.5rem;"><strong>Software Development:</strong> Built full-stack apps and backend systems at PilotCity and Open Coding Society.</li>
    <li style="margin-bottom: 0.5rem;"><strong>Physics Research:</strong> Explored magnetized plasma interactions at UC San Diego.</li>
    <li style="margin-bottom: 0.5rem;"><strong>Technical Design:</strong> Led Blender and Onshape projects as 3D Animation Club VP, teaching students advanced modeling.</li>
    <li style="margin-bottom: 0.5rem;"><strong>STEM Education:</strong> Developed curriculum for aerospace-themed outreach programs for K–12 students through Project Flight.</li>
    <li style="margin-bottom: 0.5rem;"><strong>Team Leadership:</strong> Served as Robot design and fabrication lead in FRC team Optix</li>
    <li style="margin-bottom: 0.5rem;"><strong>Mission-Driven:</strong> Dedicated to making engineering more accessible and inspiring curiosity through real-world projects.</li>
  </ul>
</div>
