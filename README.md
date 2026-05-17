<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio - Nestor</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #0f172a;
            color: #fff;
        }

        header {
            background: #020617;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            color: #38bdf8;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #fff;
        }

        section {
            padding: 40px;
            max-width: 900px;
            margin: auto;
        }

        .card {
            background: #1e293b;
            padding: 20px;
            margin-top: 20px;
            border-radius: 10px;
            transition: 0.3s;
        }

        .card:hover {
            transform: scale(1.03);
        }

        .btn {
            display: inline-block;
            padding: 10px 15px;
            background: #38bdf8;
            color: #000;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 10px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #020617;
            margin-top: 40px;
        }
    </style>
</head>

<body>

<header>
    <h1>👨‍💻 Nestor Assunção</h1>
    <p>Estudante de Ciência da Computação</p>

    <nav>
        <a href="#sobre">Sobre</a>
        <a href="#projetos">Projetos</a>
        <a href="#contato">Contato</a>
    </nav>
</header>

<section id="sobre">
    <h2>Sobre mim</h2>
    <p>
        Sou estudante de Ciência da Computação, interessado em programação,
        desenvolvimento web e tecnologia. Estou construindo meu portfólio
        com projetos acadêmicos e pessoais.
    </p>
</section>

<section id="projetos">
    <h2>Projetos</h2>

    <div class="card">
        <h3>🧮 Calculadora em Python</h3>
        <p>Projeto com operações básicas usando Python.</p>
        <a class="btn" href="#">Ver Projeto</a>
    </div>

    <div class="card">
        <h3>🌐 Site HTML</h3>
        <p>Projeto de site simples para portfólio.</p>
        <a class="btn" href="#">Ver Projeto</a>
    </div>

</section>

<section id="contato">
    <h2>Contato</h2>
    <p>Email: nestorbrpro@email.com</p>
    <p>LinkedIn: https://www.linkedin.com/in/nestor-assunção-33aa53401/</p>
</section>

<footer>
    <p>© 2026 - Nestor Assunção</p>
</footer>

</body>
</html>
