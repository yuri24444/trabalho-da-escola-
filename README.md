<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tudo Sobre Animais - Sua Empresa</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f8ff;
      margin: 0;
      padding: 0;
      animation: fadeIn 1.5s ease-in-out;
    }
    
    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    header {
      background-color: #008080;
      color: white;
      padding: 20px;
      text-align: center;
      animation: slideDown 1s ease-in-out;
    }

    @keyframes slideDown {
      from {
        transform: translateY(-100%);
      }
      to {
        transform: translateY(0);
      }
    }

    section {
      padding: 20px;
    }

    .animal {
      margin-bottom: 30px;
      background-color: #e0f7fa;
      padding: 10px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      opacity: 0;
      animation: fadeInUp 1s forwards;
    }

    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    img {
      width: 250px;
      border-radius: 10px;
      transition: transform 0.3s;
    }

    img:hover {
      transform: scale(1.1);
    }

    .preco {
      font-weight: bold;
      color: green;
    }

    .categoria {
      background-color: #e0f7fa;
      padding: 10px;
      margin-bottom: 20px;
      border-radius: 8px;
    }

    footer {
      text-align: center;
      background-color: #008080;
      color: white;
      padding: 10px;
      animation: slideUp 1s ease-in-out;
    }

    @keyframes slideUp {
      from {
        transform: translateY(100%);
      }
      to {
        transform: translateY(0);
      }
    }

    .empresa-info {
      text-align: center;
      margin-top: 50px;
    }

    .empresa-info h2 {
      color: #008080;
    }

    .empresa-info p {
      font-size: 1.2em;
      line-height: 1.6;
    }

    .contact {
      background-color: #f0f8ff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      margin-top: 40px;
    }

    .contact a {
      color: #008080;
      text-decoration: none;
      font-weight: bold;
    }

    .location {
      margin-top: 40px;
      text-align: center;
    }

    iframe {
      border: 0;
      width: 100%;
      height: 400px;
      border-radius: 10px;
    }
  </style>
</head>
<body>

<header>
  <h1>Tudo Sobre Animais - Sua Empresa</h1>
  <p>Somos uma empresa especializada em fornecer produtos e serviços relacionados aos animais.</p>
</header>

<section>
  <h2>🥩 Animais para Consumo</h2>

  <div class="animal">
    <h3>Frango</h3>
    <img src="https://upload.wikimedia.org/wikipedia/commons/e/eb/White_Leghorn_hen.jpg" alt="Frango">
    <p><strong>Características:</strong> Criado principalmente para produção de carne e ovos. Bastante comum em pequenas propriedades rurais.</p>
    <p class="preco">Preço médio da carne: R$ 8 - R$ 15/kg</p>
  </div>

  <div class="animal">
    <h3>Porco</h3>
    <img src="https://upload.wikimedia.org/wikipedia/commons/a/a2/Pig_in_Thailand.jpg" alt="Porco">
    <p><strong>Características:</strong> Criado para produção de carne (carne suína). Animais de fácil adaptação e crescimento rápido.</p>
    <p class="preco">Preço médio da carne: R$ 20 - R$ 35/kg</p>
  </div>

  <div class="animal">
    <h3>Vaca</h3>
    <img src="https://upload.wikimedia.org/wikipedia/commons/e/e2/Cow_in_Field.jpg" alt="Vaca">
    <p><strong>Características:</strong> Criada principalmente para produção de leite e carne bovina. É um dos principais animais de consumo no mundo.</p>
    <p class="preco">Preço médio da carne: R$ 35 - R$ 50/kg</p>
  </div>

  <div class="animal">
    <h3>Cordeiro</h3>
    <img src="https://upload.wikimedia.org/wikipedia/commons/2/28/Newborn_lamb.jpg" alt="Cordeiro">
    <p><strong>Características:</strong> Carne muito apreciada em várias culturas. Criado especialmente para produção de carne de cordeiro.</p>
    <p class="preco">Preço médio da carne: R$ 50 - R$ 70/kg</p>
  </div>

  <div class="animal">
    <
