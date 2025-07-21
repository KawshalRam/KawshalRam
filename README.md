<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kawshal Ram | Developer Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #004aad;
      --accent: #facc15;
      --bg: #0e1117;
      --card: #161b22;
      --text: #e6edf3;
      --subtext: #8b949e;
    }
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Inter', sans-serif;
      background-color: var(--bg);
      color: var(--text);
      line-height: 1.6;
      padding: 2rem;
    }
    header {
      text-align: center;
      margin-bottom: 4rem;
    }
    header h1 {
      font-size: 3rem;
      color: var(--accent);
    }
    header p {
      font-size: 1.2rem;
      color: var(--subtext);
    }
    .badges a {
      display: inline-block;
      margin: 0.5rem;
      text-decoration: none;
    }
    .badges img {
      height: 28px;
    }
    section {
      margin-bottom: 3rem;
    }
    h2 {
      color: var(--accent);
      margin-bottom: 1rem;
      font-size: 1.8rem;
    }
    ul {
      list-style: none;
      padding-left: 1rem;
    }
    li::before {
      content: "\2728";
      margin-right: 0.5rem;
    }
    .project {
      background: var(--card);
      padding: 1.5rem;
      margin-bottom: 1.5rem;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
    }
    .project h3 {
      color: var(--primary);
      margin-bottom: 0.5rem;
    }
    .project a {
      color: var(--accent);
      text-decoration: none;
    }
    footer {
      text-align: center;
      margin-top: 4rem;
      font-size: 0.9rem;
      color: var(--subtext);
    }
  </style>
</head>
<body>
  <header>
    <h1>👋 Hi, I'm Kawshal Ram</h1>
    <p>Software Development Intern @ OpenLynks · LLM Developer · Cybersecurity Explorer</p>
    <div class="badges">
      <a href="mailto:kawshalram09@gmail.com"><img src="https://img.shields.io/badge/Gmail-kawshalram09@gmail.com-D14836?logo=gmail" alt="Gmail" /></a>
      <a href="https://linkedin.com/in/KawshalRam"><img src="https://img.shields.io/badge/LinkedIn-KawshalRam-blue?logo=linkedin" alt="LinkedIn" /></a>
      <a href="https://github.com/KawshalRam"><img src="https://img.shields.io/badge/GitHub-KawshalRam-black?logo=github" alt="GitHub" /></a>
    </div>
  </header>

  <section>
    <h2>🔍 About Me</h2>
    <ul>
      <li>Currently building intelligent tools using LLMs and scalable APIs</li>
      <li>Cybersecurity enthusiast and AI developer</li>
      <li>Love blending tech with real-world utility</li>
    </ul>
  </section>

  <section>
    <h2>💡 Tech Stack</h2>
    <div class="badges">
      <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
      <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
      <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
      <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
      <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
    </div>
  </section>

  <section>
    <h2>🚀 Projects</h2>
    <div class="project">
      <h3>🧠 <a href="https://github.com/KawshalRam/RASA-AI">RASA AI Chat Assistant</a></h3>
      <p>Fully responsive AI chatbot app with voice, markdown, theme switch, and chat history. Uses Google Gemini 1.5 Flash API.</p>
    </div>
    <div class="project">
      <h3>📈 <a href="https://github.com/KawshalRam/STOCK-prediction">Stock Market Prediction AI</a></h3>
      <p>Forecast model using Keras + NumPy with real-time YFinance data, achieving 93% accuracy on stocks like Apple and Infosys.</p>
    </div>
  </section>

  <section>
    <h2>🧠 Extras</h2>
    <ul>
      <li>Chairperson @ ACM SIGAI, Manipal</li>
      <li>Partnership Director @ TEDxMUJ</li>
      <li>Certified by Google, Mastercard, EC-Council, IBM</li>
    </ul>
  </section>

  <footer>
    Built with ❤️ by Kawshal Ram · 2025
  </footer>
</body>
</html>
