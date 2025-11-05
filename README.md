```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Malila Nyamai — About</title>
  <meta name="description" content="Malila Nyamai — Full-stack developer from Kenya. React, Node.js, cloud, and scalable front-end architectures." />
  <style>
    :root{
      --bg:#0b1220;
      --panel:#0f1724;
      --muted:#94a3b8;
      --accent:#06b6d4;
      --accent-2:#7c3aed;
      --glass:rgba(255,255,255,0.03);
      --radius:14px;
      --transition:300ms cubic-bezier(.2,.9,.2,1);
      --maxw:980px;
    }
    *{box-sizing:border-box}
    html,body{margin:0;font-family:Inter, ui-sans-serif, system-ui, -apple-system,"Segoe UI",Roboto,Arial;line-height:1.45;background:linear-gradient(180deg,var(--bg),#020617);color:#e6eef6;-webkit-font-smoothing:antialiased;padding:20px 0}
    .wrap{max-width:var(--maxw);margin:0 auto;padding:20px}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px;flex-wrap:wrap}
    .brand{display:flex;gap:14px;align-items:center}
    .avatar{width:76px;height:76px;border-radius:12px;background:linear-gradient(135deg,var(--accent),var(--accent-2));display:flex;align-items:center;justify-content:center;font-weight:700;color:#021124;font-size:20px;box-shadow:0 8px 20px rgba(2,8,23,0.6)}
    h1{font-size:1.45rem;margin:0}
    p.lead{margin:4px 0 0;color:var(--muted);font-size:0.95rem}
    .controls{display:flex;gap:8px;align-items:center;flex-wrap:wrap}
    .btn{background:linear-gradient(180deg,rgba(255,255,255,0.02),rgba(255,255,255,0.01));border:1px solid var(--glass);padding:8px 12px;border-radius:10px;color:inherit;text-decoration:none;cursor:pointer;transition:all var(--transition);font-size:0.9rem}
    .btn:hover{transform:translateY(-3px);box-shadow:0 6px 18px rgba(2,8,23,0.6)}
    main{display:grid;grid-template-columns:1fr;gap:18px;margin-top:22px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:18px;border-radius:var(--radius);border:1px solid var(--glass);box-shadow:0 4px 20px rgba(2,8,23,0.6)}
    .grid-2{display:grid;grid-template-columns:1fr 340px;gap:18px}
    @media (max-width:920px){.grid-2{grid-template-columns:1fr}.avatar{width:56px;height:56px}}
    ul.badges{display:flex;flex-wrap:wrap;gap:8px;padding:0;margin:8px 0 0;list-style:none}
    ul.badges li{padding:8px 12px;border-radius:999px;background:linear-gradient(180deg,rgba(255,255,255,0.01),rgba(255,255,255,0.02));font-size:0.95rem;transition:transform var(--transition)}
    ul.badges li:hover{transform:translateY(-4px)}
    .muted{color:var(--muted)}
    .tech-cloud{display:flex;flex-wrap:wrap;gap:8px;margin-top:8px}
    .chip{padding:6px 10px;border-radius:999px;background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.02);font-size:0.85rem}
    .contact-links{display:flex;flex-direction:column;gap:10px}
    .copy-hint{font-size:0.88rem;color:var(--muted)}
    footer{margin-top:20px;text-align:center;color:var(--muted);font-size:0.9rem}
    a {color:var(--accent);text-decoration:none;transition:color var(--transition),transform var(--transition)}
    a:hover{color:var(--accent-2);transform:translateY(-2px)}
    h2,h3{margin:0 0 8px 0;color:#dffaff}
    hr.sep{border:none;border-top:1px solid rgba(255,255,255,0.03);margin:12px 0}
    button{cursor:pointer}
  </style>
</head>
<body data-theme="dark">
  <div class="wrap">
    <header>
      <div class="brand">
        <div class="avatar">MN</div>
        <div>
          <h1>Malila Nyamai <span class="muted">— Software Developer</span></h1>
          <p class="lead">Full-stack developer in Kenya. React, Node.js, cloud services & user-centered design.</p>
        </div>
      </div>
      <div class="controls">
        <a class="btn" href="#contact">Contact</a>
      </div>
    </header>

    <main>
      <section class="card">
        <h2>About</h2>
        <p>I'm <strong>Malila Nyamai</strong>, a dedicated software developer based in Kenya. I design and build impactful web applications focused on excellent UX and scalable architectures.</p>
        <p>Active on <a href="https://github.com/joashnyamai" target="_blank">@joashnyamai</a> — contributing to open-source, mentoring, and helping teams adopt modern web tech.</p>
        <ul class="badges">
          <li>Working on: scalable front-end architectures</li>
          <li>Learning: TypeScript, DevOps, Docker</li>
          <li>Open to: collaborations in East Africa</li>
          <li>Help with: performance & scaling</li>
          <li>Ask me about: React, Node.js, Kenyan tech</li>
          <li>Pronouns: he/him</li>
        </ul>
        <div class="muted">Fun fact: I built a weather dashboard that plays Benga on rainy days!</div>
      </section>

      <div class="grid-2">
        <section class="card">
          <h3>Selected Projects & Focus</h3>
          <div><strong>Responsive Web Apps</strong><p class="muted">React, modern CSS, accessibility.</p></div>
          <div><strong>Front-End Experiences</strong><p class="muted">Smooth, interactive UIs.</p></div>
          <div><strong>Cloud & Backend</strong><p class="muted">Node.js, serverless, CI/CD.</p></div>
          <h4>Tech stack</h4>
          <div class="tech-cloud">
            <span class="chip">React</span>
            <span class="chip">TypeScript</span>
            <span class="chip">Node.js</span>
            <span class="chip">Express</span>
            <span class="chip">MongoDB</span>
            <span class="chip">Postgres</span>
            <span class="chip">Docker</span>
            <span class="chip">AWS</span>
            <span class="chip">CI/CD</span>
          </div>
        </section>

        <aside class="card" id="contact">
          <h3>Contact & Links</h3>
          <div class="contact-links">
            <a class="btn" href="https://www.linkedin.com/in/malila-nyamai-0b2711221/" target="_blank">LinkedIn</a>
            <a class="btn" href="https://malila-nyamai.netlify.app/" target="_blank">Portfolio</a>
            <a class="btn" href="https://github.com/malila-nyamai" target="_blank">GitHub</a>
            <button id="copyEmail" class="btn">Copy Email</button>
            <div class="copy-hint">Email: <span id="copiedEmail"></span></div>
          </div>
          <hr class="sep" />
          <div><strong>Currently</strong><p class="muted">Building scalable, responsive front-ends.</p></div>
        </aside>
      </div>
    </main>

    <footer>
      <small>Made with ❤️ — <span class="muted">Malila Nyamai • Kenya</span></small>
    </footer>
  </div>

  <script>
    const user = 'malila';
    const domain = 'example.com';
    const email = `${user}@${domain}`;

    document.getElementById('copyEmail').addEventListener('click', async () => {
      try {
        await navigator.clipboard.writeText(email);
        const hint = document.getElementById('copiedEmail');
        hint.textContent = email;
        hint.style.fontWeight = '600';
      } catch (e) {
        alert('Copy failed. Email: ' + email);
      }
    });
  </script>
</body>
</html>
