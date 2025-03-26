<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Blog Pessoal</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    width: 80%;
    margin: 0 auto;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
}

header h1 {
    text-align: center;
    font-size: 2.5rem;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    margin-top: 10px;
}

nav ul li {
    margin: 0 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

nav ul li a:hover {
    color: #ddd;
}

section {
    padding: 40px 0;
    background-color: #fff;
    margin-bottom: 20px;
}

h2 {
    text-align: center;
    font-size: 2rem;
    margin-bottom: 20px;
}

.sobre-conteudo {
    display: flex;
    align-items: center;
    justify-content: space-around;
}

.sobre-conteudo img {
    border-radius: 50%;
    margin-right: 20px;
}

.artigo {
    background-color: #f9f9f9;
    padding: 20px;
    margin: 15px 0;
    border-radius: 5px;
}

.artigo h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
}

.galeria-conteudo {
    display: flex;
    gap: 15px;
    justify-content: center;
}

.foto img {
    width: 100%;
    height: auto;
    border-radius: 5px;
}

form {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

form label {
    font-weight: bold;
}

form input, form textarea {
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 1rem;
}

form button {
    background-color: #333;
    color: #fff;
    padding: 10px;
    border: none;
    cursor: pointer;
    font-size: 1rem;
    border-radius: 15px;
}

form button:hover {
    background-color: #444;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}

</style>
<body>
    <header>
        <div class="container">
            <h1>Bem-vindo ao meu Blog!</h1>
            <nav>
                <ul>
                    <li><a href="#sobre">Sobre Mim</a></li>
                    <li><a href="#artigos">Artigos</a></li>
                    <li><a href="#galeria">Galeria</a></li>
                    <li><a href="#contato">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="sobre">
        <div class="container">
            <h2>Sobre Mim</h2>
            <div class="sobre-conteudo">
                <img src="https://github.com/Alexander148662/blog-pessoal/issues/1#issue-2949997751" alt="Minha Foto">
                <p><b>Olá! Meu nome é Alexandre Freancisco Adula. Sou apaixonado por tecnologia, viagens, fotografia e, claro, escrever sobre minha vida. Neste blog, compartilho minhas experiências, aventuras e aprendizados. Espero que você se inspire e se divirta enquanto lê!</b></p>
            </div>
        </div>
    </section>

    <section id="artigos">
        <div class="container">
            <h2>Meus Artigos</h2>

            <div class="artigo">
                <h3>Meu Primeiro Artigo</h3>
                <p><b>Esse é o meu primeiro artigo no blog. Aqui, conto um pouco sobre minhas experiências iniciais com a programação e como isso mudou minha forma de pensar. Fique à vontade para ler e comentar!</b></p>
            </div>

            <div class="artigo">
                <h3>Viagens Inesquecíveis</h3>
                <p><b>Viajar é uma das coisas que mais amo fazer. Neste artigo, falo sobre algumas viagens que marcaram a minha vida e como elas moldaram meu jeito de ver o mundo.</b></p>
            </div>

            <div class="artigo">
                <h3>Fotografia e a Arte de Capturar Momentos</h3>
                <p>A fotografia sempre foi uma paixão. Aqui, compartilho um pouco sobre como a fotografia se tornou uma forma de expressar minhas emoções e capturar momentos especiais da vida.</p>
            </div>
        </div>
    </section>

    <section id="galeria">
        <div class="container">
            <h2>Galeria de Fotos</h2>
            <div class="galeria-conteudo">
                <div class="foto">
                    <img src="cadeiradelmar.png"Foto 1">
                </div>
                <div class="foto">
                    <img src="casa.png" alt="Foto 2">
                </div>
                <div class="foto">
                    <img src="delmar.png"Foto 3">
                </div>
            </div>
        </div>
    </section>

    <section id="contato">
        <div class="container">
            <h2>Contato</h2>
            <form action="#" method="post">
                <label for="nome">Nome:</label>
                <input type="text" id="nome" name="nome" required>

                <label for="email">E-mail:</label>
                <input type="email" id="email" name="email" required>

                <label for="mensagem">Mensagem:</label>
                <textarea id="mensagem" name="mensagem" rows="4" required></textarea>

                <button type="submit">Enviar</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 Meu Blog Pessoal. Todos os direitos reservados.</p>
        </div>
    </footer>
</body>
</html>

