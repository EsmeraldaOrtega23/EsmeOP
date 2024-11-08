<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículum Profesional</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f2f2f2;
        }

        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #ff66a3;
        }

        .profile {
            text-align: center;
            margin-bottom: 20px;
        }

        .profile img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 10px;
        }

        h2 {
            color: #ff66a3;
            margin-bottom: 10px;
        }

        .section {
            margin-bottom: 20px;
        }

        .projects {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
        }

        .project {
            flex: 1 1 calc(33% - 10px);
            border: 1px solid #ff66a3;
            border-radius: 8px;
            overflow: hidden;
        }

        .project img {
            width: 100%;
            height: 100px;
            object-fit: cover;
        }

        .project-title {
            text-align: center;
            padding: 10px;
            background: #f2f2f2;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Cabecera con foto -->
        <div class="profile">
            <img src="images/tu_foto.jpg" alt="Foto Profesional">
            <h1>Tu Nombre Completo</h1>
            <p>Desarrollador Web | GitHub: @tuusuario</p>
        </div>

        <!-- Sobre mí -->
        <div class="section">
            <h2>Sobre Mí</h2>
            <p>
                Soy un desarrollador web con experiencia en HTML, CSS, y JavaScript. Me apasiona crear aplicaciones funcionales y elegantes.
            </p>
        </div>

        <!-- Experiencia -->
        <div class="section">
            <h2>Experiencia Profesional</h2>
            <p><strong>Desarrollador Frontend</strong> - Empresa XYZ (2022 - Presente)</p>
            <p>Descripción breve de tus tareas y logros en este rol.</p>
        </div>

        <!-- Educación -->
        <div class="section">
            <h2>Educación</h2>
            <p><strong>Licenciatura en Ciencias de la Computación</strong> - Universidad Ejemplo (2018 - 2021)</p>
        </div>

        <!-- Proyectos -->
        <div class="section">
            <h2>Proyectos</h2>
            <div class="projects">
                <div class="project">
                    <img src="images/proyecto1.jpg" alt="Proyecto 1">
                    <div class="project-title">Proyecto 1</div>
                </div>
                <div class="project">
                    <img src="images/proyecto2.jpg" alt="Proyecto 2">
                    <div class="project-title">Proyecto 2</div>
                </div>
                <div class="project">
                    <img src="images/proyecto3.jpg" alt="Proyecto 3">
                    <div class="project-title">Proyecto 3</div>
                </div>
            </div>
        </div>
    </div>

</body>
</html>
         
     
