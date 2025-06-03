<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>README do Projeto</title>
  <style>
    body {
      background-color: #0e0e2c;
      color: #f8f8f8;
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
    }

    .container {
      max-width: 800px;
      margin: 40px auto;
      background-color: #1f1f3a;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(138, 43, 226, 0.4);
    }

    h1, h2 {
      color: #ad94ff;
    }

    p {
      line-height: 1.6;
    }

    button.toggle-btn {
      background-color: #6a5acd;
      color: white;
      border: none;
      padding: 10px 20px;
      margin: 10px 0;
      cursor: pointer;
      border-radius: 5px;
      transition: background 0.3s;
    }

    button.toggle-btn:hover {
      background-color: #7b68ee;
    }

    .section {
      margin-bottom: 20px;
    }

    .section-content {
      display: none;
      padding-left: 10px;
      border-left: 3px solid #ad94ff;
      margin-top: 10px;
    }

    footer {
      text-align: center;
      padding: 20px;
      color: #aaa;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>📘 README - Meu Projeto</h1>
    <p>Este é um projeto exemplo para demonstrar uma página README interativa com HTML, CSS e JavaScript.</p>

    <div class="section">
      <button class="toggle-btn" onclick="toggleSection('instalacao')">📦 Instalação</button>
      <div id="instalacao" class="section-content">
        <p>1. Clone o repositório<br>2. Abra o arquivo <code>index.html</code><br>3. Pronto!</p>
      </div>
    </div>

    <div class="section">
      <button class="toggle-btn" onclick="toggleSection('uso')">🚀 Uso</button>
      <div id="uso" class="section-content">
        <p>Abra o arquivo no navegador. Use os botões para navegar entre seções. Personalize conforme necessário.</p>
      </div>
    </div>

    <div class="section">
      <button class="toggle-btn" onclick="toggleSection('tecnologias')">🛠 Tecnologias</button>
      <div id="tecnologias" class="section-content">
        <ul>
          <li>HTML5</li>
          <li>CSS3</li>
          <li>JavaScript</li>
        </ul>
      </div>
    </div>

    <div class="section">
      <button class="toggle-btn" onclick="toggleSection('licenca')">📄 Licença</button>
      <div id="licenca" class="section-content">
        <p>Este projeto está licenciado sob a licença MIT.</p>
      </div>
    </div>
  </div>

  <footer>
    &copy; 2025 - Projeto Exemplo README Interativo
  </footer>

  <script>
    function toggleSection(id) {
      const section = document.getElementById(id);
      section.style.display = section.style.display === 'block' ? 'none' : 'block';
    }
  </script>

</body>
</html>
