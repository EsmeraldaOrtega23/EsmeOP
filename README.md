<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículum Profesional</title>
    <style>
        /* Estilos generales */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f0f7;
            color: #333;
            display: flex;
            justify-content: center;
            padding: 20px;
        }
        
        .container {
            width: 800px;
            background-color: #ffffff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            overflow: hidden;
        }

        /* Cabecera */
        .header {
            background-color: #ffd1e8;
            padding: 20px;
            text-align: center;
        }

        .header img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 10px;
        }

        .header h1 {
            font-size: 28px;
            margin-bottom: 5px;
        }

        .header p {
            font-size: 18px;
            color: #555;
        }

        /* Secciones */
        .section {
            padding: 20px;
        }

        .section-title {
            font-size: 22px;
            color: #ff66a3;
            margin-bottom: 10px;
            border-bottom: 2px solid #ff66a3;
            padding-bottom: 5px;
        }

        .section-content {
            margin-top: 10px;
            line-height: 1.6;
        }

        /* Proyectos */
        .projects {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 15px;
        }

        .project {
            flex: 1 1 calc(33.333% - 10px);
            border: 2px solid #ffd1e8;
            border-radius: 8px;
            overflow: hidden;
        }

        .project img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }

        .project-title {
            text-align: center;
            padding: 10px;
            font-size: 16px;
            color: #ff66a3;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Cabecera con foto -->
        <div class="header">
            <img src="ruta_a_tu_foto.jpg" alt="Foto Profesional">
            <h1>Tu Nombre Completo</h1>
            <p>Desarrollador Web | GitHub: @tuusuario</p>
        </div>

        <!-- Sobre mí -->
        <div class="section">
            <h2 class="section-title">Sobre Mí</h2>
            <p class="section-content">
                Soy un desarrollador web con experiencia en tecnologías como HTML, CSS, JavaScript y frameworks modernos.
                Apasionado por crear aplicaciones funcionales y estéticas. Siempre en busca de nuevos retos y aprendizaje continuo.
            </p>
        </div>

        <!-- Experiencia -->
        <div class="section">
            <h2 class="section-title">Experiencia Profesional</h2>
            <div class="section-content">
                <p><strong>Desarrollador Frontend</strong> - Empresa XYZ (2022 - Presente)</p>
                <p>Descripción de tus tareas y logros en este rol.</p>
                <br>
                <p><strong>Pasante en Desarrollo Web</strong> - Empresa ABC (2021 - 2022)</p>
                <p>Descripción de tus tareas y logros en este rol.</p>
            </div>
        </div>

        <!-- Educación -->
        <div class="section">
            <h2 class="section-title">Educación</h2>
            <div class="section-content">
                <p><strong>Licenciatura en Ciencias de la Computación</strong> - Universidad Ejemplo (2018 - 2021)</p>
            </div>
        </div>

        <!-- Proyectos -->
        <div class="section">
            <h2 class="section-title">Proyectos</h2>
            <div class="projects">
                <!-- Proyectos individuales -->
                <div class="project">
                    <img src="ruta_a_imagen_proyecto_1.jpg" alt="Proyecto 1">
                    <div class="project-title">Proyecto 1</div>
                </div>
                <div class="project">
                    <img src="ruta_a_imagen_proyecto_2.jpg" alt="Proyecto 2">
                    <div class="project-title">Proyecto 2</div>
                </div>
                <div class="project">
                    <img src="ruta_a_imagen_proyecto_3.jpg" alt="Proyecto 3">
                    <div class="project-title">Proyecto 3</div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>

