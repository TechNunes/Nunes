# Nunes
Prestamos Serviços de Qualidade
<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <title>TechNunes - Serviços & Materiais Informáticos</title>
  <style>
    body {
      background-color: #f0f4f8;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    table {
      width: 90%;
      margin: auto;
      border-collapse: collapse;
      background-color: #ffffff;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }
    td {
      border: 1px solid #ccc;
      padding: 20px;
      vertical-align: top;
    }
    header {
      text-align: center;
      background-color: #004080;
      color: white;
      padding: 20px;
    }
    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    h2 {
      color: #004080;
    }
    .colorido {
      color: #e63946;
      font-weight: bold;
    }
    button {
      background-color: #004080;
      color: white;
      border: none;
      padding: 10px 20px;
      cursor: pointer;
      border-radius: 5px;
    }
    button:hover {
      background-color: #0066cc;
    }
    footer {
      text-align: center;
      background-color: #004080;
      color: white;
      padding: 15px;
    }
  </style>
</head>
<body>
  <!-- Cabeçalho -->
  <header>
    <h1>TechNunes</h1>
    <p><span class="colorido">Soluções inteligentes em informática</span></p>
    <nav>
      <!-- Agora abrem outras páginas -->
      <a href="Serviços.html">Serviços</a>
      <a href="Produtos.html">Produtos</a>
      <a href="Sobre.html">Sobre</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <!-- Estrutura em tabelas -->
  <table>
    <!-- Seção Hero -->
    <tr>
      <td colspan="2" style="text-align:center; background-color:#e6f2ff;">
        <h2>Bem-vindo à <span class="colorido">TechNunes</span></h2>
        <p>Manutenção, consultoria e venda de <span class="colorido">materiais informáticos</span> de qualidade.</p>
        <a href="orçamento.html"><button>Peça um Orçamento</button></a>
      </td>
    </tr>

    <!-- Serviços -->
    <tr id="servicos">
      <td colspan="2">
        <h2>Nossos Serviços</h2>
        <ul>
          <li><span class="colorido">Assistência Técnica:</span> Reparação e manutenção de computadores.</li>
          <li><span class="colorido">Consultoria:</span> Orientação para escolha de equipamentos.</li>
          <li><span class="colorido">Redes:</span> Instalação e configuração para empresas e residências.</li>
        </ul>
      </td>
    </tr>

    <!-- Produtos -->
    <tr id="produtos">
      <td>
        <h2>Produtos em Destaque</h2>
        <p><span class="colorido">Teclado Mecânico</span> - R$ 250,00</p>
        <p><span class="colorido">Mouse Gamer</span> - R$ 150,00</p>
        <p><span class="colorido">HD Externo 1TB</span> - R$ 350,00</p>
      </td>
      <td>
        <img src="pagina/equipamentos.jpg" alt="Produtos Informáticos" width="50%">
      </td>
    </tr>

    <!-- Sobre -->
    <tr id="sobre">
      <td colspan="2">
        <h2>Sobre Nós</h2>
        <p>Somos especializados em <span class="colorido">soluções tecnológicas</span> há mais de 10 anos.</p>
        <p>Nosso objetivo é fornecer confiança e qualidade em cada atendimento.</p>
      </td>
    </tr>

    <!-- Contato -->
    <tr id="contato">
      <td colspan="2">
        <h2>Fale Conosco</h2>
        <!-- Formulário com mailto -->
        <form action="mailto:nunescandidofrancisco@gmail.com" method="post" enctype="text/plain">
          <label for="nome">Nome:</label><br>
          <input type="text" id="nome" name="nome" required><br><br>

          <label for="email">Email:</label><br>
          <input type="email" id="email" name="email" required><br><br>

          <label for="mensagem">Mensagem:</label><br>
          <textarea id="mensagem" name="mensagem" required></textarea><br><br>

          <button type="submit">Enviar</button>
        </form>
      </td>
    </tr>
  </table>

  <!-- Rodapé -->
  <footer>
    <p>&copy; 2025 TechNunes - Todos os direitos reservados.</p>
  </footer>
</body>
</html>
