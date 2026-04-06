# portfolio-
Portfólio pessoal desenvolvido para apresentar meus projetos e evolução como desenvolvedor. Reúne aplicações em Python, automação de tarefas e análise de dados, além de projetos web. Focado em prática, organização de código e resolução de problemas reais.

<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vitor Guilherme | Portfólio</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #0f0f1a;
      color: #fff;
    }

    header {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(135deg, #1a1a2e, #16213e);
    }

    header h1 {
      font-size: 2.8em;
      color: #a855f7;
    }

    header p {
      margin-top: 10px;
      color: #ccc;
    }

    section {
      padding: 50px 20px;
      max-width: 1100px;
      margin: auto;
    }

    h2 {
      margin-bottom: 25px;
      color: #a855f7;
    }

    /* PROJETOS */
    .projetos {
      display: flex;
      flex-wrap: wrap;
      gap: 25px;
    }

    .card {
      background: #1a1a2e;
      padding: 20px;
      border-radius: 15px;
      flex: 1 1 300px;
      transition: 0.3s;
      border: 1px solid transparent;
    }

    .card:hover {
      transform: translateY(-8px);
      border: 1px solid #a855f7;
      box-shadow: 0 0 25px rgba(168, 85, 247, 0.6);
    }

    .card h3 {
      margin-bottom: 10px;
    }

    .btn {
      display: inline-block;
      margin-top: 12px;
      padding: 10px 15px;
      background: #a855f7;
      color: white;
      border-radius: 10px;
      text-decoration: none;
      transition: 0.3s;
    }

    .btn:hover {
      background: #9333ea;
    }

    /* HABILIDADES */
    ul {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    ul li {
      background: #1a1a2e;
      padding: 10px 15px;
      border-radius: 10px;
      border: 1px solid #a855f7;
    }

    /* CONTATO */
    .contato a {
      color: #a855f7;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #1a1a2e;
      margin-top: 40px;
      color: #aaa;
    }
  </style>
</head>

<body>

<header>
  <h1>Vitor Guilherme</h1>
  <p>Desenvolvedor Python 🚀 | Automação | Dados</p>
</header>

<section>
  <h2>Sobre mim</h2>
  <p>
    Desenvolvedor focado em automação com Python, análise de dados e criação de soluções práticas.
    Busco minha primeira oportunidade remota na área de tecnologia.
  </p>
</section>

<section>
  <h2>Projetos</h2>

  <div class="projetos">

    <!-- PROJETO 1 -->
    <div class="card">
      <h3>🔧 Automação de Cadastro</h3>
      <p>
        Script em Python que automatiza o cadastro de produtos em sistema web,
        utilizando PyAutoGUI e leitura de dados via CSV com Pandas.
      </p>
      <p><strong>Tecnologias:</strong> Python, Pandas, PyAutoGUI</p>
      <a href="https://github.com/Vnasciment" target="_blank" class="btn">Ver Código</a>
    </div>

    <!-- PROJETO 2 -->
    <div class="card">
      <h3>📊 Análise de Dados</h3>
      <p>
        Projeto em Python utilizando Jupyter Notebook para análise e tratamento de dados,
        com foco em organização e insights.
      </p>
      <p><strong>Tecnologias:</strong> Python, Pandas</p>
      <a href="https://github.com/Vnasciment" target="_blank" class="btn">Ver Projeto</a>
    </div>

    <!-- PROJETO 3 -->
    <div class="card">
      <h3>🧠 Gabarito Automático</h3>
      <p>
        Sistema em Python que corrige respostas automaticamente,
        facilitando análise de resultados.
      </p>
      <p><strong>Tecnologias:</strong> Python</p>
      <a href="https://github.com/Vnasciment" target="_blank" class="btn">Ver Código</a>
    </div>

  </div>

</section>

<section>
  <h2>Habilidades</h2>

  <ul>
    <li>Python</li>
    <li>Pandas</li>
    <li>Automação</li>
    <li>Análise de Dados</li>
    <li>HTML</li>
    <li>CSS</li>
    <li>GitHub</li>
  </ul>

</section>

<section class="contato">
  <h2>Contato</h2>
  <p>📧 Email: vnascimentodesousa0204@gmail.com</p>
  <p>💻 GitHub: <a href="https://github.com/Vnasciment" target="_blank">github.com/Vnasciment</a></p>
</section>

<footer>
  <p>© 2026 - Vitor Guilherme</p>
</footer>

</body>
</html>
