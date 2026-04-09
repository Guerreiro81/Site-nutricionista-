# Site-nutricionista
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Nutricionista | Saúde e Bem-estar</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f9f4;
    }
    header {
      background-color: #4CAF50;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #388E3C;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px;
      max-width: 900px;
      margin: auto;
    }
    .card {
      background: white;
      padding: 20px;
      margin-top: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    footer {
      background: #2E7D32;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
    button {
      background: #4CAF50;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>

<header>
  <h1>Nutricionista Vanessa Biz Aver</h1>
  <p>Nutricionista Clínica e Esportiva</p>
</header>

<nav>
  <a href="#sobre">Sobre</a>
  <a href="#servicos">Serviços</a>
  <a href="#contato">Contato</a>
</nav>

<section id="sobre">
  <div class="card">
    <h2>Sobre mim</h2>
    <p>Sou nutricionista especializada em saúde e emagrecimento, ajudando pessoas a alcançarem seus objetivos com alimentação equilibrada.</p>
  </div>
</section>

<section id="servicos">
  <div class="card">
    <h2>Serviços</h2>
    <ul>
      <li>Consulta nutricional personalizada</li>
      <li>Plano alimentar para emagrecimento</li>
      <li>Nutrição esportiva</li>
      <li>Reeducação alimentar</li>
    </ul>
  </div>
</section>

<section id="contato">
  <div class="card">
    <h2>Contato</h2>
    <p>Email: contato@nutricionista.com</p>
    <p>WhatsApp: (00) 00000-0000</p>
    <button onclick="alert('Agendamento em breve!')">Agendar Consulta</button>
  </div>
</section>

<footer>
  <p>© 2026 Nutricionista | Todos os direitos reservados</p>
</footer>

</body>
</html>
