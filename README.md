# <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Viaje de Fin de Curso a Alemania</title>
    <link rel="stylesheet" href="styles.css"> <!-- Enlace a tu archivo CSS -->
</head>
<body>
    <header>
        <h1>¡Bienvenidos al Viaje de Fin de Curso a Alemania!</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#itinerario">Itinerario</a></li>
                <li><a href="#informacion">Información útil</a></li>
                <li><a href="#galeria">Galería</a></li>
                <li><a href="#faq">FAQ</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio">
        <h2>Introducción</h2>
        <p>¡Este es el sitio web oficial del viaje de fin de curso a Alemania! Aquí encontrarán toda la información sobre el itinerario, actividades y consejos importantes para disfrutar al máximo de esta experiencia única.</p>
    </section>

    <section id="itinerario">
        <h2>Itinerario del Viaje</h2>
        <ul>
            <li>Día 1: Llegada a Berlín</li>
            <li>Día 2: Tour por el centro histórico de Berlín</li>
            <li>Día 3: Visita a Munich y al Parque Olímpico</li>
            <li>Día 4: Viaje a Hamburgo</li>
            <li>Día 5: Regreso a casa</li>
        </ul>
    </section>

    <section id="informacion">
        <h2>Información Útil</h2>
        <p>¡Prepárate para tu viaje con estos consejos!</p>
        <ul>
            <li><strong>Clima:</strong> Lleva ropa para clima variable (puede hacer frío por la noche). </li>
            <li><strong>Moneda:</strong> La moneda de Alemania es el Euro (€).</li>
            <li><strong>Transporte:</strong> Recomendamos usar el transporte público, muy eficiente y fácil de usar.</li>
        </ul>
    </section>

    <section id="galeria">
        <h2>Galería</h2>
        <p>Aquí podrás ver fotos de nuestros anteriores viajes.</p>
        <!-- Aquí puedes agregar imágenes -->
        <img src="foto1.jpg" alt="Imagen de viaje a Alemania">
        <img src="foto2.jpg" alt="Imagen de viaje a Alemania">
    </section>

    <section id="faq">
        <h2>Preguntas Frecuentes</h2>
        <ul>
            <li><strong>¿Qué debo llevar?</strong> Ropa cómoda, adaptadores de corriente, y una buena cámara.</li>
            <li><strong>¿Cuánto dinero debo llevar?</strong> Es recomendable llevar entre 100 y 150 euros por persona para gastos personales.</li>
        </ul>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>Si tienes preguntas adicionales, no dudes en escribirnos.</p>
        <form action="mailto:email@ejemplo.com" method="post" enctype="text/plain">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required><br><br>
            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email" required><br><br>
            <label for="mensaje">Mensaje:</label><br>
            <textarea id="mensaje" name="mensaje" rows="4" required></textarea><br><br>
            <input type="submit" value="Enviar">
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Viaje de Fin de Curso a Alemania. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
/* Estilos para el cuerpo de la página */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

h2 {
    color: #333;
}

/* Estilos de las secciones */
section {
    margin: 20px;
    padding: 20px;
    background-color: white;
    border-radius: 8px;
}

/* Estilo de las imágenes */
img {
    max-width: 100%;
    height: auto;
    margin: 10px 0;
}

/* Estilo del formulario */
form {
    background-color: #e2e2e2;
    padding: 15px;
    border-radius: 5px;
}

form input, form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
}

footer {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
