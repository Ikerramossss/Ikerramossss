<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estudio de Tatuajes</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="Logo del Estudio de Tatuajes">
        </div>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#artistas">Artistas</a></li>
                <li><a href="#galeria">Galería</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio">
        <h1>Bienvenidos a Nuestro Estudio de Tatuajes</h1>
        <p>Creando arte en la piel desde [Año de Fundación].</p>
    </section>

    <section id="artistas">
        <h2>Nuestros Artistas</h2>
        <div class="artista">
            <img src="artista1.jpg" alt="Artista 1">
            <h3>Artista 1</h3>
            <p>Descripción del Artista 1.</p>
        </div>
        <div class="artista">
            <img src="artista2.jpg" alt="Artista 2">
            <h3>Artista 2</h3>
            <p>Descripción del Artista 2.</p>
        </div>
        <!-- Añadir más artistas según sea necesario -->
    </section>

    <section id="galeria">
        <h2>Galería de Trabajos</h2>
        <div class="galeria">
            <img src="tattoo1.jpg" alt="Tatuaje 1">
            <img src="tattoo2.jpg" alt="Tatuaje 2">
            <!-- Añadir más imágenes según sea necesario -->
        </div>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <form action="enviar_mensaje.php" method="post">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; [Año Actual] Estudio de Tatuajes. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
