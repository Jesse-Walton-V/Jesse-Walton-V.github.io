<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jesse Walton V | Portfolio</title>
  <style>
    :root {
      --bg: #0f0f11;
      --card: #1a1a1d;
      --text: #f2f2f7;
      --accent: #6a5acd; /* slate purple */
      --accent2: #ffb347; /* warm orange */
      --radius: 18px;
      --transition: 0.3s ease;
      --font: "Inter", sans-serif;
    }

    body {
      margin: 0;
      background: var(--bg);
      color: var(--text);
      font-family: var(--font);
      line-height: 1.6;
    }

    header {
      padding: 3rem 2rem;
      text-align: center;
      background: linear-gradient(135deg, var(--accent) 0%, var(--accent2) 100%);
      color: white;
    }

    header h1 {
      margin: 0;
      font-size: 3rem;
      font-weight: 800;
    }

    header h2 {
      margin-top: 0.5rem;
      font-weight: 400;
      opacity: 0.9;
    }

    section {
      max-width: 900px;
      margin: 2rem auto;
      padding: 1.5rem;
      background: var(--card);
      border-radius: var(--radius);
      box-shadow: 0 6px 16px rgba(0, 0, 0, 0.35);
    }

    h3 {
      color: var(--accent2);
      margin-top: 0;
      font-size: 1.8rem;
    }

    a {
      color: var(--accent2);
      text-decoration: none;
      transition: var(--transition);
    }

    a:hover {
      color: var(--accent);
    }

    .project-card {
      margin-top: 1rem;
      padding: 1rem;
      background: #232326;
      border-radius: var(--radius);
      border-left: 4px solid var(--accent2);
      transition: var(--transition);
    }

    .project-card:hover {
      transform: translateY(-4px);
      border-left-color: var(--accent);
    }

    footer {
      text-align: center;
      padding: 2rem;
      color: #aaa;
    }

  </style>
</head>
<body>
  <header>
    <h1>Hi, I’m Jesse Walton V</h1>
    <h2>Aspiring Game Developer · CS Student</h2>
  </header>

  <section>
    <h3>About Me</h3>
    <p>
      I’m passionate about game development, neural networks, and interactive media. Currently studying
      Computer Science with a minor in American Popular Culture Studies, I mix technical skill with creativity to
      build projects that feel fun, polished, and expressive.
    </p>
  </section>

  <section>
    <h3>Projects</h3>
    <div class="project-card">
      <h4>Untitled Rhythm Game (WIP)</h4>
      <p>Built in Godot · focusing on timing systems, beat mapping, and punchy visuals.</p>
    </div>
  </section>

  <section>
    <h3>Skills</h3>
    <ul>
      <li><strong>Languages:</strong> Java, Python, GDScript</li>
      <li><strong>Tools:</strong> Git, VS Code, Godot, IntelliJ</li>
    </ul>
  </section>

  <section>
    <h3>Experience</h3>
    <p><strong>Crew Member – Dairy Queen (2024–2025)</strong></p>
    <ul>
      <li>Worked in fast‑paced teams while maintaining professionalism and communication.</li>
      <li>Mentored youth, assisted events, and delivered strong customer interactions.</li>
      <li>Wrote daily professional emails to clients and customers.</li>
    </ul>
  </section>

  <section>
    <h3>Resume</h3>
    <p><a href="Jesse_Walton_V_Resume.pdf" target="_blank">Download my resume (PDF)</a></p>
  </section>

  <section>
    <h3>Contact</h3>
    <p><strong>Email:</strong> waltonjesse123@gmail.com</p>
    <p>
      <a href="https://linkedin.com/in/jesse-walton-v" target="_blank">LinkedIn</a> ·
      <a href="https://github.com/Jesse-Walton-V" target="_blank">GitHub</a>
    </p>
  </section>

  <footer>
    © 2025 Jesse Walton V — All Rights Reserved
  </footer>
</body>
</html>

