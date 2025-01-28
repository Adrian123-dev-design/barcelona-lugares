# barcelona-lugares
YPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3 Lugares para visitar en Barcelona</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="https://www.shutterstock.com/image-vector/vector-illustration-lettering-composition-barcelona-600nw-1579983421.jpg" alt="Logo de Barcelona">
        </div>
        <nav>
            <a href="#">Inicio</a>
            <a href="#">Lugares</a>
            <a href="#">Contacto</a>
        </nav>
    </header>
    <main>
        <section class="hero">
            <h1>Descubre Barcelona</h1>
            <p>Explora tres de los lugares más emblemáticos de la ciudad.</p>
        </section>
        <section class="contenido">
            <h2>1. La Sagrada Familia</h2>
            <img src="https://images.adsttc.com/media/images/5ff4/88a7/63c0/17cd/f900/0527/medium_jpg/shutterstock_397537417.jpg?1609861261" alt="La Sagrada Familia">
            <p>Un templo icónico diseñado por Antoni Gaudí, famoso por su arquitectura única.</p>
        </section>
        <section class="contenido">
            <h2>2. Parque Güell</h2>
            <img src="https://images.adsttc.com/media/images/510c/5369/b3fc/4b7d/0100/0074/large_jpg/antoni-gaudi-spain-barcelona-Parc-Guell-05-samuel-ludwig.jpg?1414599916" alt="Parque Güell">
            <p>Un parque lleno de color y arte modernista, también obra de Gaudí.</p>
        </section>
        <section class="contenido">
            <h2>3. Barrio Gótico</h2>
            <img src="https://dynamic-media-cdn.tripadvisor.com/media/photo-o/1a/4a/a9/05/photo0jpg.jpg?w=900&h=500&s=1" alt="Barrio Gótico">
            <p>Un barrio histórico lleno de calles estrechas y edificios medievales.</p>
        </section>
    </main>
    <footer>
        <p>Contacto: info@barcelona.com</p>
        <p>Síguenos: Facebook | Instagram | Twitter</p>
    </footer>
</body>
</html>

:root {
    --color-primario: #0077b6;
    --color-secundario: #ffd60a;
    --color-terciario: #f77f00;
    --color-blanco: #ffffff;
    --color-negro: #000000;
}
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: var(--color-blanco);
    color: var(--color-negro);
}

header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: var(--color-primario);
    color: var(--color-blanco);
    padding: 1rem;
}

header .logo img {
    max-height: 50px;
}

nav a {
    margin: 0 1rem;
    color: var(--color-blanco);
    text-decoration: none;
}

.hero {
    text-align: center;
    padding: 2rem;
    background-color: var(--color-secundario);
    color: var(--color-negro);
}

.contenido {
    padding: 2rem;
    margin: 1rem auto;
    max-width: 800px;
    text-align: center;
}

.contenido img {
    width: 100%;
    max-width: 400px;
    border-radius: 8px;
}

footer {
    text-align: center;
    background-color: var(--color-terciario);
    color: var(--color-blanco);
    padding: 1rem;
}
