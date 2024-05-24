<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Wonderful Studio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('data:image/jpeg;base64,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'); /* Substitua 'sua-imagem-de-fundo.jpg' pelo URL da sua imagem de fundo */
            background-size: cover;
            background-position: center;
        }
        header {
            background-color: rgba(0, 0, 0, 0.5);
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        nav {
            background-color: rgba(0, 0, 0, 0.7);
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
        }
        nav a:hover {
            background-color: rgba(255, 255, 255, 0.1);
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
        .portfolio {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .portfolio img {
            max-width: 100%;
            height: auto;
            border-radius: 50%;
        }
        form {
            margin-top: 20px;
        }
        input[type="text"],
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-sizing: border-box;
        }
        input[type="submit"] {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
        }
        input[type="submit"]:hover {
            background-color: #444;
        }
        .contact-info {
            margin-top: 20px;
        }
        .contact-info h3 {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>Digital Wonderful Studio</h1>
    <p>Seu destino para fotografias excepcionais</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#gestante">Fotos de Gestante</a>
    <a href="#criancas">Fotos de Crianças</a>
    <a href="#aniversario">Fotos de Aniversário</a>
    <a href="#casamento">Fotos de Casamento</a>
    <a href="#ar-livre">Fotos ao Ar Livre</a>
    <a href="#graduacao">Fotos de Graduação</a>
    <a href="#contact">Contato</a>
</nav>

<div class="container">
    <section id="home">
        <h2>Bem-vindo ao Digital Wonderful Studio</h2>
        <p>Explora nosso portfólio de fotografias excepcionais.</p>
    </section>

    <section id="gestante">
        <h2>Fotos de Gestante</h2>
        <div class="portfolio">
            <!-- Insira suas 10 imagens de gestante aqui -->
            <img src="gestante1.jpg" alt="Foto de Gestante 1">
            <img src="gestante2.jpg" alt="Foto de Gestante 2">
            <!-- Adicione mais imagens conforme necessário -->
        </div>
    </section>

    <!-- Adicione seções para cada categoria com 10 imagens -->

    <section id="contact">
        <h2>Entre em Contato</h2>
        <form action="#" method="post">
            <input type="text" name="name" placeholder="Seu Nome" required>
            <input type="text" name="email" placeholder="Seu E-mail" required>
            <textarea name="message" placeholder="Sua Mensagem" rows="4" required></textarea>
            <input type="submit" value="Enviar Mensagem">
        </form>
        <div class="contact-info">
            <h3>Contatos da Empresa</h3>
            <p>Email: contato@digitalwonderfulstudio.com</p>
            <p>Telefone: (11) 1234-5678</p>
            <p>WhatsApp: (11) 98765-4321</p>
            <h3>Funcionários</h3>
            <p>João Silva: (11) 91234-5678</p>
            <p>Maria Oliveira: (11) 97654-3210</p>
        </div>
    </section>
</div>

</body>
</html>
