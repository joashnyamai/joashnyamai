<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Malila Nyamai | Full-stack Developer</title>
  <style>
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      background-color: #0d1117;
      color: #e6edf3;
      line-height: 1.6;
      overflow-x: hidden;
    }

    a {
      color: #58a6ff;
      text-decoration: none;
      transition: color 0.3s ease;
    }
    a:hover {
      color: #79c0ff;
    }

    /* Hero section */
    .hero {
      text-align: center;
      width: 100%;
      animation: fadeIn 2s ease-in-out;
    }
    .hero img {
      width: 100%;
      height: auto;
    }
    .hero h1 {
      margin-top: 1.2rem;
      font-size: 2.2rem;
    }
    .hero strong {
      display: block;
      margin-bottom: 0.3rem;
      color: #c9d1d9;
    }
    .hero p a {
      margin: 0 8px;
    }

    section {
      max-width: 900px;
      margin: 2.5rem auto;
      padding: 0 20px;
      animation: fadeUp 1.5s ease-in-out;
    }
    section h2 {
      color: #58a6ff;
      border-bottom: 1px solid #30363d;
      padding-bottom: 0.3rem;
      margin-bottom: 1rem;
      font-size: 1.3rem;
    }

    .badges {
      text-align: center;
      margin-top: 2rem;
    }
    .badges img {
      margin: 0.3rem;
      transition: transform 0.3s ease, opacity 0.3s ease;
    }
    .badges img:hover {
      transform: scale(1.1);
      opacity: 0.9;
    }

    footer {
      text-align: center;
      padding: 1.5rem;
      border-top: 1px solid #30363d;
      font-size: 0.9rem;
      color: #8b949e;
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }
    @keyframes fadeUp {
      from {opacity: 0; transform: translateY(15px);}
      to {opacity: 1; transform: translateY(0);}
    }
  </style>
</head>
<body>

  <!-- Hero Section -->
  <div class="hero">
    <a href="https://joashnyamai.github.io/malila-nyamai-profile" target="_blank">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github.com/joashnyamai/joashnyamai/blob/main/profile-dark.png?raw=true">
        <img src="https://github.com/joashnyamai/joashnyamai/blob/main/profile-light.png?raw=true" alt="Malila Nyamai - Full-stack Developer">
      </picture>
    </a>
    <h1>Hi, I'm Malila Nyamai 👋</h1>
    <p>
      <strong>Full-stack Developer • Kenya</strong><br>
      React • Node.js • Cloud • Scalable Architectures
    </p>
    <p>
      <a href="https://joashnyamai.github.io/malila-nyamai-profile" target="_blank">🌐 View Full Profile</a> •
      <a href="https://www.linkedin.com/in/malila-nyamai-0b2711221/">LinkedIn</a> •
      <a href="https://malila-nyamai.netlify.app/">Portfolio</a>
    </p>
  </div>

  <section>
    <h2>🔭 Currently Working On</h2>
    <p>Developing scalable, responsive front-end architectures with focus on performance and accessibility.</p>
  </section>

  <section>
    <h2>🌱 Currently Learning</h2>
    <p>Advanced React patterns, TypeScript, and DevOps tools like Docker and CI/CD pipelines.</p>
  </section>

  <section>
    <h2>👯 Open to Collaborate On</h2>
    <p>Innovative web projects, open-source contributions, or tech initiatives in East Africa.</p>
  </section>

  <section>
    <h2>🤝 Collaboration & Community</h2>
    <p>Beyond personal projects, I actively collaborate with organizations through 
      <a href="https://github.com/joashnyamai" target="_blank">@joashnyamai</a> — 
      contributing to community-driven solutions, mentoring developers, and helping teams adopt modern web technologies.
    </p>
  </section>

  <section>
    <h2>💬 Ask Me About</h2>
    <p>Front-end frameworks, backend integrations, or insights on the Kenyan tech scene.</p>
  </section>

  <section>
    <h2>⚡ Fun Fact</h2>
    <p>I built a personal weather dashboard that not only forecasts but also suggests the perfect Kenyan playlist based on the vibe – rainy days call for some classic Benga!</p>
  </section>

  <div class="badges">
    <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" alt="React Badge">
    <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white" alt="Node.js Badge">
    <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white" alt="TypeScript Badge">
    <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white" alt="AWS Badge">
  </div>

  <footer>
    © 2025 Malila Nyamai • Crafted with ❤️ and JavaScript
  </footer>

</body>
</html>
