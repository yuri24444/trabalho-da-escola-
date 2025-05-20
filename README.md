<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carvão Caseiro</title>
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Corpo */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 50px 0;
            font-size: 3em;
            text-transform: uppercase;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        /* Efeitos de parallax */
        .parallax {
            background: url('https://via.placeholder.com/1600x900') no-repeat center center fixed;
            background-size: cover;
            height: 400px;
            position: relative;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
            font-size: 2.5em;
            animation: fadeIn 3s ease-in-out;
        }

        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        .parallax h1 {
            animation: slideIn 2s ease-out;
        }

        @keyframes slideIn {
            0% { transform: translateY(-100px); }
            100% { transform: translateY(0); }
        }

        /* Conteúdo principal */
        .content {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin: 40px;
        }

        .section {
            width: 45%;
            margin: 20px 0;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .section:hover {
            transform: translateY(-10px);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.2);
        }

        .section img {
            width: 100%;
            border-radius: 8px;
            transition: transform 0.3s ease;
        }

        .section img:hover {
            transform: scale(1.05);
        }

        .section h2 {
            font-size: 2em;
            margin-bottom: 20px;
            color: #333;
            text-align: center;
        }

        .text {
            font-size: 1.2em;
            line-height: 1.8;
            color: #666;
        }

        /* Botões */
        .button {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 1.2em;
            cursor: pointer;
            margin-top: 20px;
            transition: transform 0.3s ease, background-color 0.3s ease;
        }

        .button:hover {
            background-color: #555;
            transform: scale(1.1);
        }

        /* Características */
        .features {
            list-style-type: none;
            padding: 0;
            font-size: 1.1em;
            color: #444;
        }

        .features li {
            margin: 15px 0;
            padding-left: 30px;
            position: relative;
        }

        .features li:before {
            content: "✔";
            position: absolute;
            left: 0;
            color: #6dbf2f;
            font-size: 1.5em;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            font-size: 1em;
        }

        /* Responsividade */
        @media (max-width: 768px) {
            .content {
                flex-direction: column;
                align-items: center;
            }

            .section {
                width: 90%;
            }

            header {
                font-size: 2em;
                padding: 20px 0;
            }
        }
    </style>
</head>
<body>

<header>
    Como Fazer Carvão Caseiro
</header>

<!-- Seção Parallax -->
<div class="parallax">
    <h1>Descubra como fazer carvão caseiro de forma simples e sustentável!</h1>
</div>

<!-- Conteúdo Principal -->
<div class="content">
    <!-- Passos -->
    <div class="section">
        <h2>Passos para Produzir Carvão Caseiro</h2>
        <img src="https://via.placeholder.com/500x300" alt="Imagem de pessoas fazendo carvão">
        <div class="text">
            O processo de fabricação de carvão caseiro envolve a queima controlada de madeira, conhecido como pirólise. Primeiro, escolha uma madeira densa, como eucalipto ou pinho. A madeira é cortada em pedaços e colocada em um forno ou fornalha. Durante o processo, é importante controlar a temperatura e a quantidade de oxigênio para garantir que a madeira se transforme em carvão de qualidade.
        </div>
        <button class="button">Saiba mais</button>
    </div>

    <!-- Benefícios -->
    <div class="section">
        <h2>Benefícios do Carvão Caseiro</h2>
        <img src="https://via.placeholder.com/500x300" alt="Imagem de pessoas usando carvão caseiro">
        <div class="text">
            Além de ser uma alternativa sustentável, o carvão caseiro pode ser produzido de forma econômica. Ele é muito utilizado para churrascos, fogueiras e até para fins industriais. Produzir o próprio carvão reduz a dependência de fontes comerciais e pode ser uma atividade prazerosa.
        </div>
        <button class="button">Veja os benefícios</button>
    </div>
</div>

<!-- Características -->
<div class="section">
    <h2>Características do Carvão Caseiro</h2>
    <ul class="features">
        <li>Alta Durabilidade: O carvão caseiro é conhecido por sua longa duração quando queimado, permitindo um fogo constante e eficaz.</li>
        <li>Menos Fumaça: Em comparação com carvão industrial, o carvão caseiro emite muito menos fumaça, tornando-o ideal para churrascos e outras atividades ao ar livre.</li>
        <li>Maior Temperatura: A queima do carvão caseiro gera uma temperatura mais alta, o que pode acelerar o processo de cozimento ou aquecimento.</li>
        <li>Produto Sustentável: Produzir carvão em casa é uma prática ecológica, pois reutiliza materiais orgânicos como madeira de poda e restos de madeira.</li>
        <li>Mais Econômico: Com o tempo, fazer seu próprio carvão pode reduzir significativamente os custos com combustível para churrascos e outras atividades.</li>
        <li>Controle de Qualidade: Ao fazer o carvão caseiro, você pode controlar o processo e garantir que ele tenha a qualidade desejada, sem aditivos químicos ou tratamentos artificiais.</li>
    </ul>
</div>

<!-- Footer -->
<footer>
    &copy; 2025 Carvão Caseiro - Todos os direitos reservados
</footer>

</body>
</html>

