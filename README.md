<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>My Musics</title>
</head>
<body>
    <header>
        <h1>Meu Site de Músicas</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">Início</a></li>
            <li><a href="#">Músicas</a></li>
            <li><a href="#">Artistas</a></li>
            <li><a href="#">Sobre</a></li>
        </ul>
    </nav>
    <main>
        <section class="featured-songs">
            <h2>Músicas em Destaque</h2>
            <!-- Aqui você pode listar algumas músicas em destaque -->
        </section>
        <section class="recently-added">
            <h2>Adicionadas Recentemente</h2>
            <!-- Aqui você pode listar músicas adicionadas recentemente -->
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Meu Site de Músicas</p>
    </footer>
</body>
</html>
/* Estilos gerais */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header, nav, main, footer {
    padding: 20px;
}

/* Estilos para o cabeçalho */
header {
    background-color: #333;
    color: white;
    text-align: center;
}

/* Estilos para a barra de navegação */
nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    background-color: #444;
}

nav li {
    margin: 0 15px;
}

nav a {
    text-decoration: none;
    color: white;
}

/* Estilos para as seções principais */
.featured-songs, .recently-added {
    margin-bottom: 30px;
}

/* Estilos para o rodapé */
footer {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 10px 0;
}
