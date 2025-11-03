<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Darizhan Bidot — Profil GitHub</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');
    :root {
      --accent: #e63946;
      --bg: #f7f7f7;
      --text: #1d1d1d;
      --sub: #555;
      --card: #fff;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background-color: var(--bg);
      color: var(--text);
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 50px 20px;
    }

    .container {
      background: var(--card);
      border-radius: 20px;
      max-width: 900px;
      width: 100%;
      box-shadow: 0 6px 20px rgba(0, 0, 0, 0.1);
      padding: 40px;
      transition: 0.3s ease;
    }

    .container:hover {
      transform: translateY(-3px);
    }

    header {
      text-align: center;
      margin-bottom: 40px;
    }

    header h1 {
      font-size: 2.4rem;
      color: var(--accent);
      letter-spacing: 1px;
    }

    header p {
      color: var(--sub);
      font-size: 1.1rem;
      margin-top: 10px;
    }

    section {
      margin-bottom: 40px;
    }

    h2 {
      color: var(--accent);
      font-size: 1.4rem;
      margin-bottom: 15px;
      text-transform: uppercase;
      border-bottom: 2px solid var(--accent);
      display: inline-block;
      padding-bottom: 3px;
    }

    .skills {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 10px;
    }

    .skill {
      background: var(--bg);
      padding: 10px 15px;
      border-radius: 10px;
      text-align: center;
      font-weight: 600;
      color: var(--text);
      transition: all 0.2s ease;
    }

    .skill:hover {
      background: var(--accent);
      color: white;
      transform: scale(1.05);
    }

    .exp-item, .edu-item {
      margin-bottom: 20px;
    }

    .exp-item h3, .edu-item h3 {
      color: var(--text);
      font-size: 1.1rem;
    }

    .exp-item span, .edu-item span {
      color: var(--sub);
      font-size: 0.95rem;
    }

    footer {
      text-align: center;
      margin-top: 30px;
    }

    .buttons {
      margin-top: 20px;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 15px;
    }

    .btn {
      background-color: var(--accent);
      color: white;
      padding: 12px 25px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: 600;
      transition: 0.3s ease;
    }

    .btn:hover {
      background-color: #c92f3a;
      transform: scale(1.05);
    }

    .contact {
      margin-top: 10px;
      color: var(--sub);
      font-size: 0.95rem;
      line-height: 1.5;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 1.8rem;
      }
      .container {
        padding: 25px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Darizhan Bidot</h1>
      <p>Étudiant en BTS SIO — Développement & Réseaux à MyDigitalSchool Nice</p>
      <p>Passionné par le développement web et la création d’expériences digitales modernes.</p>
      <div class="buttons">
        <a href="https://www.linkedin.com/in/darizhanbidot" target="_blank" class="btn">LinkedIn</a>
        <a href="mailto:darizhan1998@gmail.com" class="btn">Email</a>
        <a href="tel:+33662257327" class="btn">Appeler</a>
      </div>
    </header>

    <section id="skills">
      <h2>Compétences</h2>
      <div class="skills">
        <div class="skill">JavaScript</div>
        <div class="skill">TypeScript</div>
        <div class="skill">HTML5 / CSS3</div>
        <div class="skill">React.js</div>
        <div class="skill">Python (Flask, FastAPI)</div>
        <div class="skill">SQL (MySQL, SQLite)</div>
        <div class="skill">Git / GitHub</div>
        <div class="skill">Node.js</div>
        <div class="skill">Figma (UI/UX)</div>
        <div class="skill">Jira / Confluence</div>
        <div class="skill">Agile (Scrum, Kanban)</div>
        <div class="skill">REST API</div>
        <div class="skill">ORM (SQLAlchemy)</div>
        <div class="skill">SEO / Accessibilité</div>
      </div>
    </section>

    <section id="experience">
      <h2>Expériences Professionnelles</h2>
      <div class="exp-item">
        <h3>Systèmes Analyste — AntiCode</h3>
        <span>Juillet 2024 – Octobre 2024</span>
      </div>
      <div class="exp-item">
        <h3>Business Analyst — ARTA</h3>
        <span>Mars 2024 – Juillet 2024</span>
      </div>
      <div class="exp-item">
        <h3>Business Analyst — EasyPack</h3>
        <span>Février 2023 – Février 2024</span>
      </div>
    </section>

    <section id="education">
      <h2>Formation</h2>
      <div class="edu-item">
        <h3>BTS SIO — Développement & Réseaux</h3>
        <span>MyDigitalSchool Nice, 2025 – 2027</span>
      </div>
      <div class="edu-item">
        <h3>Business Analysis Certifiée — TechOrda</h3>
        <span>Kazakhstan, 2022 – 2023</span>
      </div>
      <div class="edu-item">
        <h3>Licence en Traduction (Anglais–Français–Russe)</h3>
        <span>Minsk State Linguistic University, 2017 – 2022</span>
      </div>
    </section>

    <section id="languages">
      <h2>Langues</h2>
      <p>Anglais — Courant (C1)</p>
      <p>Français — Bilingue</p>
      <p>Russe — Langue maternelle</p>
    </section>

    <footer>
      <div class="contact">
        📞 06 62 25 73 27   ✉️ darizhan1998@gmail.com<br>
        🌐 <a href="https://www.linkedin.com/in/darizhanbidot" target="_blank">www.linkedin.com/in/darizhanbidot</a>
      </div>
      <p style="margin-top:10px;color:#aaa;">© 2025 — Darizhan Bidot</p>
    </footer>
  </div>

  <script>
    // Simple animation for buttons
    const buttons = document.querySelectorAll('.btn');
    buttons.forEach(btn => {
      btn.addEventListener('click', () => {
        btn.style.transform = 'scale(0.95)';
        setTimeout(() => btn.style.transform = 'scale(1)', 150);
      });
    });
  </script>
</body>
</html>
