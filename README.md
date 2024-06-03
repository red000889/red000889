git clone 
https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenidos a Mi Página Web</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#about">Acerca de</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>
    <main>
        <section id="inicio">
            <h2>Inicio</h2>
            <p>Contenido de inicio...</p>
        </section>
        <section id="about">
            <h2>Acerca de</h2>
            <p>Contenido acerca de...</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Mi Página Web</p>
    </footer>
</body>
</html>
git add .
git commit -m "Añadir archivos de la página web"
git push origin main
