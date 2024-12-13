
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>IPTV Premium</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1a1a1a;
            color: #fff;
        }
        header {
            background-color: #ff5722;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #e64a19;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 20px;
            text-align: center;
        }
        .package {
            border: 2px solid #ff5722;
            border-radius: 10px;
            padding: 20px;
            margin: 20px auto;
            max-width: 300px;
            background-color: #333;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .package:hover {
            transform: translateY(-10px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
        }
        .package h3 {
            color: #ffccbc;
        }
        .package p {
            color: #fff;
        }
        .package .price {
            font-size: 1.5em;
            font-weight: bold;
            color: #ff5722;
        }
        .package button {
            margin-top: 10px;
            padding: 10px 20px;
            font-size: 1em;
            font-weight: bold;
            color: white;
            background-color: #ff5722;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .package button:hover {
            background-color: #e64a19;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        img {
            max-width: 100%;
            border-radius: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo ao IPTV PontalMais!</h1>
        <p>Os melhores canais e filmes para você e sua família.</p>
    </header>
    <nav>
        <a href="#inicio">Início</a>
        <a href="#pacotes">Pacotes</a>
        <a href="#contato">Contato</a>
    </nav>
    <main>
        <section id="inicio">
            <h2>Assista a qualquer hora, em qualquer lugar</h2>
            <p>Com nosso serviço de IPTV, você tem acesso aos melhores canais e conteúdos on-demand.</p>
            <!-- Imagem de 800x40 -->
            <img src="homem-assistindo-a-um-programa-na-tv_23-2149047401.jpg" alt="Banner promocional de IPTV">
        </section>

        <section id="pacotes">
            <h2>Escolha seu Pacote</h2>

            <div class="package">
                <h3>Mensal</h3>
                <p>Acesso a mais de 200 canais e conteúdos exclusivos.</p>
                <p class="price">R$ 29,90/mês</p>
                <button>Assinar Agora</button>
            </div>

            <div class="package">
                <h3>Trimestral</h3>
                <p>Economize e aproveite todos os benefícios.</p>
                <p class="price">R$ 79,90/3 meses</p>
                <button>Assinar Agora</button>
            </div>

            <div class="package">
                <h3>Anual</h3>
                <p>O melhor custo-benefício para você.</p>
                <p class="price">R$ 299,90/ano</p>
                <button>Assinar Agora</button>
            </div>
        </section>

        <section id="imagem-iptv">
            <h2>Experiência Premium</h2>
            <p>Confira a qualidade do nosso serviço de IPTV:</p>
            <img src="imagem iptv.jpg" alt="Imagem de IPTV">
        </section>

        <section id="contato">
            <h2>Entre em Contato</h2>
            <p>Tem dúvidas? Fale conosco pelo WhatsApp ou e-mail.</p>
            <p><strong>WhatsApp:</strong> (41) 98844-9256</p>
            <p><strong>E-mail:</strong> rochamariane0@gmail.com</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 IPTV PontalMais. Todos os direitos reservados.</p>
    </footer>
</body>
</html>

