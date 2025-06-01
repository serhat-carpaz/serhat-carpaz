<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Serhat Çarpaz | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron&family=Roboto&display=swap" rel="stylesheet" />
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Roboto', sans-serif;
      background: #0f0c29;
      background: linear-gradient(45deg, #0f0c29, #302b63, #24243e);
      color: #fff;
      overflow-x: hidden;
    }

    h1 {
      font-family: 'Orbitron', sans-serif;
      font-size: 2.5rem;
      text-align: center;
      margin-top: 2rem;
      animation: slideDown 1.2s ease-out;
    }

    p {
      text-align: center;
      margin: 1rem auto;
      max-width: 600px;
      font-size: 1.2rem;
      animation: fadeIn 2s ease;
    }

    section {
      padding: 2rem;
      animation: fadeInUp 2s ease;
    }

    .badges a {
      display: inline-block;
      margin: 0.5rem;
      animation: floatUp 0.5s ease-in-out forwards;
    }

    .stack span {
      display: inline-block;
      margin: 0.4rem;
      font-size: 0.9rem;
      padding: 0.6rem 1rem;
      border-radius: 5px;
      background-color: rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(3px);
      transition: transform 0.3s ease;
    }

    .stack span:hover {
      transform: scale(1.1);
    }

    .focus li {
      margin-bottom: 0.4rem;
    }

    .stats img {
      width: 45%;
      margin: 1rem;
      border-radius: 8px;
      animation: fadeIn 2s ease;
    }

    /* Animations */
    @keyframes slideDown {
      from { transform: translateY(-50px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes fadeInUp {
      from { transform: translateY(30px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    @keyframes floatUp {
      from { transform: translateY(20px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    footer {
      text-align: center;
      font-size: 0.8rem;
      padding: 1rem;
      color: #ccc;
    }
  </style>
</head>
<body>
  <h1>👋 Hi, I'm Serhat Çarpaz</h1>
  <p>🚀 I'm passionate about AI, embedded systems, and building smart projects using code and electronics.</p>

  <section>
    <h2>🌐 Socials</h2>
    <div class="badges">
      <a href="https://linkedin.com/in/senin-linkin" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
      <a href="https://discordapp.com/users/senin-idin" target="_blank"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" /></a>
      <a href="https://huggingface.co/serhatcarpaz" target="_blank"><img src="https://img.shields.io/badge/HuggingFace-FF6F00?style=for-the-badge&logo=huggingface&logoColor=white" /></a>
    </div>
  </section>

  <section>
    <h2>💻 Tech Stack</h2>
    <div class="stack">
      <span>Python</span><span>C</span><span>C++</span><span>SQL</span><span>HTML</span><span>CSS</span>
      <span>JavaScript</span><span>Node.js</span><span>Electron</span><span>Flutter</span><span>Arduino</span>
      <span>PyTorch</span><span>TensorFlow</span><span>Scikit-Learn</span><span>HuggingFace</span>
    </div>
  </section>

  <section>
    <h2>🛠 Focus Areas</h2>
    <ul class="focus">
      <li>🧠 Artificial Intelligence (AI)</li>
      <li>📊 Machine Learning</li>
      <li>🤖 Deep Learning</li>
      <li>🎨 Generative Models</li>
      <li>👁️ Vision Transformers (ViT)</li>
      <li>📚 Natural Language Processing (NLP)</li>
      <li>🕹️ Reinforcement Learning</li>
      <li>🔐 Cybersecurity</li>
      <li>⚛️ Quantum Physics & Computing</li>
    </ul>
  </section>

  <section class="stats" align="center">
    <h2>📊 GitHub Stats</h2>
    <img src="https://github-readme-stats.vercel.app/api?username=serhat-carpaz&show_icons=true&theme=tokyonight" />
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=serhat-carpaz&theme=tokyonight" />
  </section>

  <footer>
    © 2025 Serhat Çarpaz. Built with 💙 and HTML/CSS.
  </footer>
</body>
</html>
