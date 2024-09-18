<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Fotógrafo Profesional</title>
</head>
<body>

<!-- Encabezado principal: Incluye el título de la página y un menú de navegación -->
<header>
<h1>Bienvenido a Fotógrafo Profesional</h1>
<ul>
<li><a href="#inicio">Inicio</a></li>
<li><a href="#portafolio">Portafolio</a></li>
<li><a href="#contacto">Contacto</a></li>
</ul>
</header>

<!-- Sección de introducción: Incluye un párrafo de bienvenida y una imagen -->
<section id="inicio">
<h2>Capturando tus mejores momentos</h2>
<p>Especializado en fotografía de bodas, retratos y eventos. Cada imagen cuenta una historia, déjanos capturar la tuya.</p>
<img src="https://www.shutterstock.com/image-illustration/camera-lens-600w-2327645439.jpg" alt="Cámara fotográfica">
</section>

<!-- Sección de portafolio: Muestra algunos trabajos recientes del fotógrafo -->
<main>
<section id="portafolio">
<h2>Mi Portafolio</h2>

<article>
<h3>Sesión de Boda</h3>
<p>Un día tan especial debe ser inmortalizado con las mejores imágenes. Aquí puedes ver algunos ejemplos de nuestros trabajos en bodas.</p>
<a href="#">Ver más</a>
  <h2>Portafolio</h2>
        <div>
            <img src="foto1.jpg" alt="Foto 1">
            <img src="foto2.jpg" alt="Foto 2">
            <img src="foto3.jpg" alt="Foto 3">
        </div>
</article>

<article>
<h3>Retratos Profesionales</h3>
<p>Retratos que capturan la esencia y personalidad de nuestros clientes. Perfecto para profesionales y personales.</p>
<a href="#">Ver más</a>
</article>
</section>
</main>

<!-- Formulario de contacto: Permite a los clientes ponerse en contacto -->
<section id="contacto">
<h2>Contacto</h2>
<form action="/submit" method="POST">
<label for="nombre">Nombre:</label>
<input type="text" name="nombre" required>
<br><br>
<label for="email">Email:</label>
<input type="email" name="email" required>
<br><br>
<label for="mensaje">Mensaje:</label>
<textarea name="mensaje" required></textarea>
<br><br>
<button type="submit">Enviar</button>
</form>
</section>

<!-- Pie de página: Incluye los derechos de autor y enlaces a las redes sociales -->
<footer>
<div>
<p>&copy; 2024 Fotógrafo Profesional. Todos los derechos reservados.</p>
</div>
<div>
<a href="https://www.tiktok.com" target="_blank">Tiktok</a>
<a href="https://github.com/" target="_blank">GitHub</a>
<a href="https://x.com" target="_blank">X</a>
</div>
</footer>

</body>
</html>
