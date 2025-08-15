<!DOCTYPE html><html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Violeta Celestial - Loja Mística</title>
    <link href="https://fonts.googleapis.com/css2?family=Crimson+Text:wght@400;700&family=Great+Vibes&display=swap" rel="stylesheet">
    <style>
        * { margin:0; padding:0; box-sizing:border-box; }
        body {
            font-family: 'Crimson Text', serif;
            background: url('https://i.ibb.co/8bzf6Zh/pergaminho-textura.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #f5f5f5;
        }
        a { text-decoration: none; color: inherit; }
        header {
            background: rgba(93, 58, 155, 0.9);
            padding: 20px;
            text-align: center;
            position: sticky;
            top:0;
            z-index: 100;
        }
        header h1 {
            font-family: 'Great Vibes', cursive;
            font-size: 3em;
            color: gold;
            text-shadow: 2px 2px #3a0d5c;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            margin-top: 10px;
        }
        nav ul li { margin: 0 15px; }
        nav ul li a { font-weight: bold; transition: color 0.3s; }
        nav ul li a:hover { color: #ffd700; }
        .banner {
            text-align: center;
            padding: 100px 20px;
            background: rgba(93, 58, 155, 0.7);
            box-shadow: inset 0 0 50px rgba(0,0,0,0.5);
        }
        .banner h2 { font-family: 'Great Vibes', cursive; font-size: 2.5em; color: gold; margin-bottom: 20px; }
        .banner p { font-size: 1.2em; max-width: 700px; margin: auto; }
        .products, .courses, .affiliates {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 50px 20px;
        }
        .product, .course, .affiliate {
            background: rgba(0,0,0,0.6);
            padding: 20px;
            border-radius: 15px;
            text-align: center;
            transition: transform 0.3s;
        }
        .product:hover, .course:hover, .affiliate:hover {
            transform: scale(1.05);
            box-shadow: 0 0 20px gold;
        }
        .product img, .course img, .affiliate img { width: 100%; border-radius: 10px; }
        h3 { margin: 15px 0 10px; color: gold; }
        p { font-size: 0.95em; color: #ddd; }
        button {
            margin-top: 10px;
            padding: 10px 20px;
            background: gold;
            border: none;
            border-radius: 5px;
            font-weight: bold;
            cursor: pointer;
            transition: background 0.3s;
        }
        button:hover { background: #ffd700; }
        footer { text-align: center; padding: 20px; background: rgba(93, 58, 155, 0.9); color: gold; font-size: 0.9em; }
        .section-title { text-align: center; font-family: 'Great Vibes', cursive; font-size: 2em; margin-bottom: 40px; color: gold; }
        .login-form { display:flex; flex-direction:column; max-width:300px; margin:auto; }
        .login-form input { margin:5px 0; padding:10px; border-radius:5px; border:none; }
        .login-form button { margin-top:10px; }
    </style>
</head>
<body><header>
    <h1>Violeta Celestial</h1>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#products">Loja</a></li>
            <li><a href="#courses">Cursos & Mentoria</a></li>
            <li><a href="#affiliates">Rede Celestial</a></li>
            <li><a href="#contact">Contato</a></li>
        </ul>
    </nav>
</header><section class="banner" id="home">
    <h2>Onde Magia e Prosperidade se Encontram</h2>
    <p>Descubra artefatos místicos, cursos sagrados e mentoria direta com o Lorde Zankai. Entre para a Rede Celestial e transforme sua vida.</p>
</section><section class="products" id="products">
    <h2 class="section-title">Produtos Místicos</h2>
    <div class="product">
        <img src="https://i.ibb.co/JdP7vK3/taro.jpg" alt="Tarô de Zankai">
        <h3>Tarô de Zankai</h3>
        <p>Baralho exclusivo para leituras profundas, energizado pelo Lorde Zankai.</p>
        <button>Comprar</button>
    </div>
    <div class="product">
        <img src="https://i.ibb.co/vYmTQxv/amuletos.jpg" alt="Amuletos Energizados">
        <h3>Amuletos Energizados</h3>
        <p>Proteção e prosperidade em amuletos preparados sob a luz da lua.</p>
        <button>Comprar</button>
    </div>
    <div class="product">
        <img src="https://i.ibb.co/5LQyWZf/rituais.jpg" alt="Materiais para Rituais">
        <h3>Materiais para Rituais</h3>
        <p>Velas, ervas e pós mágicos prontos para suas práticas espirituais.</p>
        <button>Comprar</button>
    </div>
</section><section class="courses" id="courses">
    <h2 class="section-title">Cursos & Mentoria</h2>
    <div class="course">
        <img src="https://i.ibb.co/TvVxB0m/tarot-course.jpg" alt="Curso de Tarot">
        <h3>Curso de Tarot</h3>
        <p>Aprenda tarot com profundidade, conduzido pelo Lorde Zankai.</p>
        <button>Inscrever-se</button>
    </div>
    <div class="course">
        <img src="https://i.ibb.co/GH3TJmD/mentoria.jpg" alt="Mentoria Espiritual">
        <h3>Mentoria Espiritual</h3>
        <p>Mentoria personalizada para evolução espiritual e prática mágica.</p>
        <button>Participar</button>
    </div>
</section><section class="affiliates" id="affiliates">
    <h2 class="section-title">Rede Celestial</h2>
    <div class="affiliate">
        <p>Ganhe comissões ao compartilhar e vender produtos da Violeta Celestial.</p>
        <p>1º nível: 10% | 2º nível: 5% | Bônus trimestral para melhores vendedores.</p>
        <div class="login-form">
            <input type="text" placeholder="Seu nome">
            <input type="email" placeholder="Seu e-mail">
            <button>Inscrever-se na Rede</button>
        </div>
    </div>
</section><footer>
    &copy; 2025 Violeta Celestial - Todos os direitos reservados | Criado por Lorde Zankai
</footer></body>
</html>
