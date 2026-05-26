<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Agro Forte | Futuro Sustentável</title>

  <style>

    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body{
      background:#f5f5f5;
      color:#333;
      line-height:1.6;
    }

    /* MENU */

    nav{
      width:100%;
      background:#1b5e20;
      padding:20px 8%;
      display:flex;
      justify-content:space-between;
      align-items:center;
      position:fixed;
      top:0;
      z-index:1000;
    }

    nav h1{
      color:white;
      font-size:28px;
    }

    nav ul{
      display:flex;
      list-style:none;
      gap:25px;
    }

    nav ul li a{
      color:white;
      text-decoration:none;
      font-weight:bold;
      transition:0.3s;
    }

    nav ul li a:hover{
      color:#c8e6c9;
    }

    /* HERO */

    .hero{
      height:100vh;
      background:
      linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
      url("https://images.unsplash.com/photo-1501004318641-b39e6451bec6?auto=format&fit=crop&w=1400&q=80");

      background-size:cover;
      background-position:center;

      display:flex;
      align-items:center;
      justify-content:center;
      text-align:center;
      color:white;
      padding:20px;
    }

    .hero-content h2{
      font-size:60px;
      margin-bottom:20px;
    }

    .hero-content p{
      font-size:22px;
      max-width:800px;
      margin:auto;
    }

    .btn{
      display:inline-block;
      margin-top:30px;
      padding:15px 35px;
      background:#43a047;
      color:white;
      text-decoration:none;
      border-radius:40px;
      font-weight:bold;
      transition:0.3s;
    }

    .btn:hover{
      background:#2e7d32;
      transform:scale(1.05);
    }

    /* SEÇÕES */

    section{
      padding:90px 10%;
    }

    .titulo{
      text-align:center;
      margin-bottom:60px;
    }

    .titulo h2{
      font-size:40px;
      color:#2e7d32;
      margin-bottom:15px;
    }

    .titulo p{
      color:#666;
      font-size:18px;
    }

    /* CARDS */

    .cards{
      display:grid;
      grid-template-columns:repeat(auto-fit, minmax(250px,1fr));
      gap:30px;
    }

    .card{
      background:white;
      padding:35px;
      border-radius:20px;
      box-shadow:0 5px 20px rgba(0,0,0,0.1);
      transition:0.3s;
    }

    .card:hover{
      transform:translateY(-10px);
    }

    .card h3{
      color:#2e7d32;
      margin-bottom:15px;
      font-size:24px;
    }

    .card p{
      color:#555;
    }

    /* BANNER */

    .banner{
      background:#2e7d32;
      color:white;
      text-align:center;
      padding:100px 20px;
    }

    .banner h2{
      font-size:45px;
      margin-bottom:20px;
    }

    .banner p{
      max-width:800px;
      margin:auto;
      font-size:20px;
    }

    /* RODAPÉ */

    footer{
      background:#111;
      color:#ccc;
      text-align:center;
      padding:30px;
    }

    /* RESPONSIVO */

    @media(max-width:768px){

      nav{
        flex-direction:column;
        gap:15px;
      }

      .hero-content h2{
        font-size:38px;
      }

      .hero-content p{
        font-size:18px;
      }

      .banner h2{
        font-size:32px;
      }

    }

  </style>
</head>

<body>

  <!-- MENU -->

  <nav>
    <h1>🌱 Agro Forte</h1>

    <ul>
      <li><a href="#">Início</a></li>
      <li><a href="#sobre">Sobre</a></li>
      <li><a href="#sustentabilidade">Sustentabilidade</a></li>
      <li><a href="#contato">Contato</a></li>
    </ul>
  </nav>

  <!-- HERO -->

  <section class="hero">

    <div class="hero-content">

      <h2>Futuro Sustentável</h2>

      <p>
        Produção agrícola e preservação ambiental trabalhando juntas
        para construir um mundo mais forte, moderno e sustentável.
      </p>

      <a href="#sobre" class="btn">Saiba Mais</a>

    </div>

  </section>

  <!-- SOBRE -->

  <section id="sobre">

    <div class="titulo">
      <h2>Agro Forte</h2>

      <p>
        O equilíbrio entre produção, tecnologia e meio ambiente.
      </p>
    </div>

    <div class="cards">

      <div class="card">
        <h3>🌿 Sustentabilidade</h3>

        <p>
          O agro sustentável preserva os recursos naturais e garante
          produção responsável para as futuras gerações.
        </p>
      </div>

      <div class="card">
        <h3>🚜 Tecnologia</h3>

        <p>
          Máquinas modernas, drones e inteligência artificial ajudam
          produtores a aumentar a produtividade no campo.
        </p>
      </div>

      <div class="card">
        <h3>💧 Preservação</h3>

        <p>
          O uso consciente da água e a preservação das florestas são
          fundamentais para o futuro do planeta.
        </p>
      </div>

    </div>

  </section>

  <!-- SUSTENTABILIDADE -->

  <section id="sustentabilidade">

    <div class="titulo">

      <h2>Equilíbrio Ambiental</h2>

      <p>
        Produzir alimentos e cuidar da natureza podem caminhar juntos.
      </p>

    </div>

    <div class="cards">

      <div class="card">
        <h3>🌎 Meio Ambiente</h3>

        <p>
          Preservar a biodiversidade é essencial para manter
          o equilíbrio ecológico e climático.
        </p>
      </div>

      <div class="card">
        <h3>⚡ Energia Limpa</h3>

        <p>
          Fontes renováveis ajudam o campo a produzir mais
          com menos impacto ambiental.
        </p>
      </div>

      <div class="card">
        <h3>🌱 Futuro Verde</h3>

        <p>
          A agricultura do futuro será cada vez mais tecnológica,
          eficiente e sustentável.
        </p>
      </div>

    </div>

  </section>

  <!-- BANNER -->

  <section class="banner">

    <h2>Produzir Hoje Para Preservar o Amanhã</h2>

    <p>
      O Agro Forte acredita em um futuro sustentável,
      onde desenvolvimento econômico e preservação ambiental
      caminham lado a lado.
    </p>

  </section>

  <!-- CONTATO -->

  <section id="contato">

    <div class="titulo">

      <h2>Contato</h2>

      <p>
        Juntos podemos construir um agro mais forte e sustentável.
      </p>

    </div>

    <div class="cards">

      <div class="card">
        <h3>📧 Email</h3>
        <p>contato@agroforte.com</p>
      </div>

      <div class="card">
        <h3>📱 Telefone</h3>
        <p>(11) 99999-9999</p>
      </div>

      <div class="card">
        <h3>📍 Localização</h3>
        <p>São Paulo - Brasil</p>
      </div>

    </div>

  </section>

  <!-- RODAPÉ -->

  <footer>
    <p>© 2026 Agro Forte - Todos os direitos reservados.</p>
  </footer>

</body>
</html>
