<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pequeños Innovadores</title>
    <style>
        /* Estilos Generales */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            text-align: center;
        }

        /* Estilos del Encabezado */
        header {
            background-color: #0073e6;
            color: white;
            padding: 20px;
        }

        .header-content {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px; /* Espacio entre la imagen y el texto */
        }

        .logo {
            width: 80px; /* Ajusta el tamaño según necesites */
            height: auto;
        }

        h1 {
            margin: 0;
            font-size: 28px;
        }

        /* Estilos de la Línea del Tiempo */
        .timeline {
            position: relative;
            max-width: 800px;
            margin: 40px auto;
        }

        .timeline::after {
            content: '';
            position: absolute;
            width: 6px;
            background-color: #0073e6;
            top: 0;
            bottom: 0;
            left: 50%;
            margin-left: -3px;
        }

        .event {
            position: relative;
            background-color: white;
            width: 45%;
            padding: 20px;
            border-radius: 10px;
            margin: 10px 0;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.2);
        }

        .event img {
            width: 100%;
            border-radius: 10px;
        }

        .event:nth-child(odd) {
            left: 0;
        }

        .event:nth-child(even) {
            left: 55%;
        }

        .event h2 {
            color: #0073e6;
        }

        /* Puntos de la Línea del Tiempo */
        .event::before {
            content: '';
            position: absolute;
            width: 20px;
            height: 20px;
            background-color: #0073e6;
            border-radius: 50%;
            top: 20px;
            left: 100%;
            margin-left: -10px;
        }

        .event:nth-child(even)::before {
            left: -10%;
        }

        /* Estilos Responsivos */
        @media screen and (max-width: 600px) {
            .event {
                width: 90%;
                left: 5% !important;
            }
            .event::before {
                left: 50% !important;
                margin-left: -10px;
            }
        }
    </style>
</head>
<body>

    <!-- Encabezado con Logo y Nombre -->
    <header>
        <div class="header-content">
            <img src="imagen.jpg" alt="Logo Pequeños Innovadores" class="logo">
            <div>
                <h1>Pequeños Innovadores</h1>
                <p>Explorando el mundo con curiosidad, creatividad y pasión.</p>
            </div>
        </div>
    </header>

    <!-- Línea del Tiempo -->
    <div class="timeline">
        <div class="event">
            <h2>📅 Año 2000 - Nace la Tecnología Moderna</h2>
            <p>Las computadoras y el internet comienzan a cambiar la forma en que aprendemos.</p>
            <img src="img1.jpg" alt="Computadora antigua">
        </div>

        <div class="event">
            <h2>📅 Año 2010 - La Era de los Smartphones</h2>
            <p>Los teléfonos inteligentes se convierten en herramientas clave para la educación.</p>
            <img src="img2.jpg" alt="Niños usando tabletas">
        </div>

        <div class="event">
            <h2>📅 Año 2023 - Inteligencia Artificial</h2>
            <p>Los niños comienzan a aprender programación e inteligencia artificial en la escuela.</p>
            <img src="img3.jpg" alt="Robot educativo">
        </div>
    </div>

</body>
</html>
