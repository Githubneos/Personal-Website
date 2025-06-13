---
layout: base
title: Hithin Pulamarasetty
description: Home Page
hide: true
image: /images/mario_animation.png
---

<!-- Main Content Area -->
<div class="main-content">
  <div class="page-title">
    <h1>Welcome to My Dashboard</h1>
    <p>Your one-stop place to learn more about my work, experience, and ways to get in touch.</p>
  </div>

  <div class="about-container">
    <!-- Screenshot Profile Card -->
    <div class="profile">
      <h3><i class="fas fa-qrcode"></i> My Profile</h3>
      <div class="qr-code">
        <img src="{{site.baseurl}}/images/CSP_MCQ/Screenshot 2025-06-09 at 9.53.53 PM.jpeg" alt="Screenshot 1">
      </div>
      <div class="qr-desc">Scan to view my digital profile</div>
    </div>

    <!-- Links Section -->
    <div class="links">
      <a class="link-card email" href="mailto:karumudikeerthan@gmail.com">
        <i class="fas fa-envelope"></i>
        <div class="content">
          <h4>Email</h4>
          <p>hithinp@gmail.com</p>
        </div>
      </a>
      <a class="link-card github" href="https://github.com/Githubneos">
        <i class="fab fa-github"></i>
        <div class="content">
          <h4>GitHub</h4>
          <p>github.com/hithin</p>
        </div>
      </a>
      <a class="link-card linkedin" href="https://www.linkedin.com/in/keerthan-karumudi-016699368/">
        <i class="fab fa-linkedin"></i>
        <div class="content">
          <h4>LinkedIn</h4>
          <p>linkedin.com/in/hithinp</p>
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

<!-- External FontAwesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<!-- Inline Styles -->
<style>
  /* Fonts & Reset */
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Inter', sans-serif;
  }

  body {
    background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
    color: #e0e0f8;
    line-height: 1.6;
    padding: 2rem;
    overflow-x: hidden;
    animation: fadeInBody 1.2s ease-out;
  }

  /* Header Styling */
  header {
    text-align: center;
    margin-bottom: 3rem;
    animation: floatIn 1s ease forwards;
  }

  h1 {
    font-size: 3rem;
    font-weight: 800;
    background: linear-gradient(to right, #00ffe0, #28ccff);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    letter-spacing: 1px;
  }

  p.tagline {
    font-size: 1.2rem;
    color: #9ae3ff;
    margin-top: 0.5rem;
    animation: pulseGlow 2s infinite ease-in-out;
  }

  /* Container */
  .container {
    max-width: 960px;
    margin: auto;
    padding: 2rem;
    border-radius: 20px;
    background: rgba(255, 255, 255, 0.05);
    box-shadow: 0 0 20px rgba(0, 255, 255, 0.2), 0 0 40px rgba(0, 128, 255, 0.1);
    backdrop-filter: blur(8px);
    transition: transform 0.4s ease, box-shadow 0.4s ease;
  }

  .container:hover {
    transform: scale(1.01);
    box-shadow: 0 0 30px rgba(0, 255, 255, 0.3), 0 0 60px rgba(0, 128, 255, 0.2);
  }

  /* Section Headers */
  h2 {
    font-size: 1.8rem;
    margin-top: 2rem;
    margin-bottom: 1rem;
    color: #77e2ff;
    position: relative;
  }

  h2::after {
    content: '';
    display: block;
    width: 60px;
    height: 3px;
    background: linear-gradient(to right, #00ffe0, #007acc);
    margin-top: 6px;
    border-radius: 3px;
    animation: slideInBar 1s ease-out forwards;
  }

  /* List Items */
  ul {
    list-style: none;
    padding-left: 0;
  }

  li {
    margin-bottom: 1rem;
    font-size: 1.05rem;
    background: rgba(255, 255, 255, 0.03);
    padding: 0.75rem 1rem;
    border-left: 4px solid #00ffe0;
    border-radius: 8px;
    transition: background 0.3s ease, transform 0.2s ease;
  }

  li:hover {
    background: rgba(0, 255, 255, 0.05);
    transform: translateX(6px);
  }

  li strong {
    color: #ffffff;
  }

  /* Links */
  a {
    color: #38e8ff;
    text-decoration: none;
</style>


<div style="font-family: Arial, sans-serif; max-width: 700px; margin: 2rem auto; padding: 1.5rem; border: 1px solid #ddd; border-radius: 12px; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
  <h2 style="font-size: 1.8rem; margin-bottom: 0.75rem;">About Me</h2>
  <p style="font-size: 1rem; color: #ccc; line-height: 1.6;">
  I focus on building practical, impactful solutions at the intersection of software, science, and education.
  </p><ul style="list-style: none; padding-left: 0; margin-top: 1rem;">
  <li style="margin-bottom: 0.5rem;"><strong>Software Development:</strong> Built full-stack apps and backend systems at PilotCity and Open Coding Society.</li>
  <li style="margin-bottom: 0.5rem;"><strong>Physics Research:</strong> Explored magnetized plasma interactions at UC San Diego to support fusion research.</li>
  <li style="margin-bottom: 0.5rem;"><strong>Technical Design:</strong> Led Blender and Onshape projects as 3D Animation Club VP, teaching students advanced modeling.</li>
  <li style="margin-bottom: 0.5rem;"><strong>STEM Education:</strong> Created aerospace-themed outreach programs for K–12 students through Project Flight.</li>
  <li style="margin-bottom: 0.5rem;"><strong>Team Leadership:</strong> Guided interdisciplinary teams across research, development, and outreach efforts.</li>
  <li style="margin-bottom: 0.5rem;"><strong>Mission-Driven:</strong> Dedicated to making engineering more accessible and inspiring curiosity through real-world projects.</li>
  </ul>
</div>

