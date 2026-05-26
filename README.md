<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Agro Forte - Futuro Sustentável</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body{
      background:#f4f7f2;
      color:#333;
      line-height:1.6;
    }

    header{
      background:linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
      url('https://images.unsplash.com/photo-1501004318641-b39e6451bec6?auto=format&fit=crop&w=1400&q=80');
      background-size:cover;
      background-position:center;
      height:90vh;
      display:flex;
      align-items:center;
      justify-content:center;
      text-align:center;
      color:white;
      padding:20px;
    }

    header h1{
      font-size:4rem;
      margin-bottom:20px;
    }

    header p{
      font-size:1.3rem;
      max-width:700px;
      margin:auto;
    }

    section{
      padding:70px 10%;
    }

    .titulo{
      text-align:center;
      margin-bottom:50px;
    }

    .titulo h2{
      color:#2e7d32;
      font-size:2.5rem;
      margin-bottom:15px;
    }

    .cards{
      display:grid;
      grid-template-columns:repeat(auto-fit, minmax(250px,1fr));
      gap:25px;
    }

    .card{
      background:white;
      padding:30px;
      border-radius:15px;
      box-shadow:0 5px 15px rgba(0,0,0,0.1);
      transition:0.3s;
    }

    .card:hover{
      transform:translateY(-10px);
    }

    .card h3{
      color:#388e3c;
      margin-bottom:15px;
    }

    .banner{
      background:#2e7d32;
      color:white;
      text-align:center;
      padding:80px 20px;
    }

    .banner h2{
      font-size:2.8rem;
      margin-bottom:20px;
    }

    .banner p{
      max-width:800px;
      margin:auto;
      font-size:1.2rem;
    }

    footer{
      background:#1b1b1b;
      color:#ccc;
      text-align:center;
      padding:25px;
    }

    @media(max-width:768px){
      header h1{
        font-size:2.5rem;
      }

      header p{
        font-size:1rem;
      }
    }
  </style>
</head>

<body>

  <header>
    <div>
      <h1>AGRO FORTE</h1>
      <p>
        Construindo um futuro sustentável através do equilíbrio
        entre produção agrícola e preservação ambiental.
      </p>
    </div>
  </header>

  <section>
    <div class="titulo">
      <h2>Futuro Sustentável</h2>
      <p>
        O agro moderno cresce com responsabilidade,
        inovação e respeito à natureza.
      </p>
    </div>

    <div class="cards">

      <div class="card">
        <h3>🌱 Sustentabilidade</h3>
        <p>
          Uso consciente dos recursos naturais para garantir
          produção eficiente sem prejudicar o meio ambiente.
        </p>
      </div>

      <div class="card">
        <h3>🚜 Tecnologia no Campo</h3>
        <p>
          Máquinas inteligentes, drones e agricultura de precisão
          aumentam a produtividade e reduzem impactos ambientais.
        </p>
      </div>

      <div class="card">
        <h3>💧 Preservação da Água</h3>
        <p>
          Sistemas modernos de irrigação ajudam no combate ao desperdício
          e preservam recursos hídricos.
        </p>
      </div>

      <div class="card">
        <h3>🌍 Equilíbrio Ambiental</h3>
        <p>
          Produzir alimentos e preservar a natureza caminham juntos
          para garantir qualidade de vida às próximas gerações.
        </p>
      </div>

    </div>
  </section>

  <section class="banner">
    <h2>Produzir Hoje Para Preservar o Amanhã</h2>
    <p>
      O Agro Forte representa a união entre desenvolvimento econômico,
      responsabilidade ambiental e inovação tecnológica.
      O futuro do campo depende do equilíbrio entre produção
      e preservação da natureza.
    </p>
  </section>

  <footer>
    <p>© 2026 Agro Forte - Futuro Sustentável</p>
  </footer>

</body>
</html>
