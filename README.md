# INOVAPET
O INOVA PET é um site dedicado a facilitar a adoção de animais, divulgando informações sobre animais disponíveis para adoção.
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>INOVA PET</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fff8f0;
      color: #333;
    }

    header {
      background-color: #ff914d;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    nav ul {
      list-style: none;
      padding: 0;
      margin: 10px 0 0 0;
      display: flex;
      justify-content: center;
      gap: 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
    }

    h2, h3 {
      color: #ff914d;
    }

    form input[type="text"],
    form input[type="submit"] {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      font-size: 1em;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    form input[type="submit"] {
      background-color: #ff914d;
      color: white;
      border: none;
      cursor: pointer;
    }

    form input[type="submit"]:hover {
      background-color: #e67e22;
    }

    ul {
      padding-left: 20px;
    }

    ul li {
      margin-bottom: 10px;
    }

    button {
      background-color: #ff914d;
      color: white;
      border: none;
      padding: 8px 12px;
      border-radius: 5px;
      cursor: pointer;
      margin-left: 10px;
    }

    button:hover {
      background-color: #e67e22;
    }

    article {
      background-color: #fff0e0;
      padding: 15px;
      border-radius: 8px;
      margin-bottom: 20px;
    }

    blockquote {
      font-style: italic;
      border-left: 4px solid #ff914d;
      padding-left: 15px;
      margin: 20px 0;
      background: #fff0e0;
      border-radius: 5px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #ff914d;
      color: white;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>INOVA PET</h1>
    <nav>
      <ul>
        <li><a href="#formulario">Adote</a></li>
        <li><a href="#servicos">Serviços</a></li>
        <li><a href="#eventos">Eventos</a></li>
        <li><a href="#clientes">Clientes</a></li>
        <li><a href="#sobre">Sobre</a></li>
      </ul>
    </nav>
  </header>

  <section>
    <h2>Seja Bem-Vindo ao INOVA PET</h2>
    <p><strong>Adote um amigo:</strong> Preencha nosso formulário para adoção de animais e encontre seu companheiro perfeito hoje mesmo.</p>
  </section>

  <section id="formulario">
    <h3>Formulário de Adoção</h3>
    <form action="processa_cadastro.php" method="POST">
      <input type="text" name="nome" placeholder="Seu nome completo" required>
      <input type="submit" value="Enviar formulário">
    </form>
  </section>

  <section id="servicos">
    <h2>Serviços</h2>
    <ul>
      <li>Workshop Educativo <button>Agendar</button></li>
      <li>Castração Gratuita <button>Agendar</button></li>
      <li>Consulta de Adoção <button>Agendar</button></li>
    </ul>
  </section>

  <section id="eventos">
    <h2>Eventos Futuros</h2>

    <article>
      <h3>Castração Gratuita</h3>
      <p>Data: quarta, 21 de maio</p>
      <p>Local: Curitiba</p>
      <button>Mais informações</button>
      <button>RSVP</button>
    </article>

    <article>
      <h3>Show dos Cães e Gatos Talentos</h3>
      <p>Data: domingo, 01 de junho</p>
      <p>Local: Curitiba</p>
      <button>Mais informações</button>
      <button>Comprar ingressos</button>
    </article>
  </section>

  <section id="clientes">
    <h2>Nossos clientes</h2>
    <blockquote>
      "Adotar o Max foi a melhor decisão que já tomei. Sempre quis ter um animal de estimação, mas não sabia por onde começar. Ao descobrir o site 'INOVA PET', fiquei encantado com o trabalho deles e a possibilidade de dar um lar a um animal abandonado. O processo foi muito tranquilo e transparente."
      <br><br>— Roberto Santos
    </blockquote>
  </section>

  <section id="sobre">
    <h2>Sobre o INOVA PET</h2>
    <h3>Nossa Missão</h3>
    <p>
      O INOVA PET é um site dedicado a facilitar a adoção de animais, divulgando informações sobre animais disponíveis para adoção. 
      Além disso, oferecemos um cadastro para potenciais adotantes, uma agenda de castração gratuita e realizamos ações de conscientização 
      sobre a importância da adoção responsável e do cuidado com os animais. Nosso objetivo é promover o bem-estar dos animais e encontrar 
      lares amorosos para aqueles que mais precisam.
    </p>
  </section>

  <footer>
    &copy; 2025 INOVA PET — Todos os direitos reservados.
  </footer>

</body>
</html>
