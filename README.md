
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pamela Ramirez | Technology Portfolio</title>
  <style>
    :root {
      --bg: #0b1220;
      --card: #162235;
      --text: #edf4ff;
      --muted: #a9b8cd;
      --accent: #62d6cb;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.7;
    }

    header {
      padding: 80px 20px;
      text-align: center;
      background: linear-gradient(135deg, #162a43, #0b1220);
    }

    h1 { font-size: 2.8rem; margin-bottom: 8px; }
    h2 { color: var(--accent); }
    h3 { margin-top: 0; }

    .subtitle {
      color: var(--accent);
      font-weight: bold;
    }

    p { color: var(--muted); }

    main {
      max-width: 1000px;
      margin: auto;
      padding: 25px;
    }

    section { margin: 55px 0; }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: var(--card);
      border: 1px solid #293c56;
      padding: 24px;
      border-radius: 12px;
    }

    .tag {
      display: inline-block;
      padding: 6px 12px;
      margin: 5px 5px 5px 0;
      background: #20364a;
      border-radius: 20px;
      color: var(--accent);
      font-size: 0.9rem;
    }

    a { color: var(--accent); }

    .button {
      display: inline-block;
      padding: 12px 22px;
      margin-top: 15px;
      background: var(--accent);
      color: #0b1220;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 25px;
      border-top: 1px solid #293c56;
      color: var(--muted);
    }
  </style>
</head>
<body>

  <header>
    <h1>Pamela Ramirez</h1>
    <div class="subtitle">
      Computer Science Student | IT | Cybersecurity
    </div>
    <p>
      Exploring technology through programming,
      troubleshooting, security labs, and hands-on projects.
    </p>
    <a class="button" href="#projects">View My Projects</a>
  </header>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>
        I'm a Computer Science student at Florida International
        University with an interest in IT support, cybersecurity,
        software development, and emerging technologies.
      </p>
      <p>
        I'm developing practical technical skills through
        coursework, independent learning, and hands-on projects.
        My background in behavioral services and STEM education
        has strengthened my problem-solving, communication,
        documentation, and analytical skills.
      </p>
    </section>

    <section id="skills">
      <h2>Technical Skills & Learning</h2>
      <div>
        <span class="tag">Java</span>
        <span class="tag">Python</span>
        <span class="tag">Programming Fundamentals</span>
        <span class="tag">Object-Oriented Programming</span>
        <span class="tag">IT Troubleshooting</span>
        <span class="tag">Cybersecurity Fundamentals</span>
        <span class="tag">Git & GitHub</span>
        <span class="tag">Windows</span>
      </div>
      <p>
        This section includes technologies I'm currently
        studying or practicing.
      </p>
    </section>

    <section id="projects">
      <h2>Projects & Technical Labs</h2>
      <div class="grid">

        <article class="card">
          <h3>Windows Wi-Fi Troubleshooting</h3>
          <p>
            A documented troubleshooting experience involving
            wireless connectivity problems, technical research,
            diagnostic steps, and resolution.
          </p>
          <p><strong>Status:</strong> Documentation in progress</p>
        </article>

        <article class="card">
          <h3>Cybersecurity Labs</h3>
          <p>
            A collection of hands-on security exercises,
            including networking concepts, authentication,
            password security, and threat awareness.
          </p>
          <p><strong>Status:</strong> In development</p>
        </article>

        <article class="card">
          <h3>Programming Projects</h3>
          <p>
            Programming exercises and applications developed
            while studying computer science and strengthening
            my Java and Python skills.
          </p>
          <p><strong>Status:</strong> Projects being organized</p>
        </article>

      </div>
    </section>

    <section id="education">
      <h2>Education</h2>
      <div class="card">
        <h3>Florida International University</h3>
        <p>Bachelor of Arts in Computer Science — In Progress</p>
        <p>
          Academic interests include programming,
          computer systems, and cybersecurity.
        </p>
      </div>
    </section>

    <section id="contact">
      <h2>Connect</h2>
      <p>
        Interested in my technical projects or professional
        development? Explore my GitHub repositories.
      </p>
      <a id="github-link" class="button"
         href="https://github.com/" target="_blank"
         rel="noopener noreferrer">
        Visit My GitHub
      </a>
    </section>
  </main>

  <footer>
    <p>&copy; <span id="year"></span> Pamela Ramirez</p>
  </footer>

  <script>
    document.getElementById("year").textContent =
      new Date().getFullYear();

    // Replace with your actual GitHub profile URL.
    document.getElementById("github-link").href =
      "https://github.com/YOUR-USERNAME";
  </script>

</body>
</html>
