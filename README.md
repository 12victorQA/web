<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Perfil Profesional</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
   <div class="contenedor-header">
    <img src="captura.jpg" alt="Foto de Ana López" class="foto-perfil">
    <div class="info-header">
     <h1>Ana López</h1>
     <p>Ingeniera Industrial | Especialista en Logística</p>
    </div>
  </div>
  </header>

  <nav>
    <ul>
      <li><a href="#perfil">Perfil</a></li>
      <li><a href="#experiencia">Experiencia</a></li>
      <li><a href="#contacto">Contacto</a></li>
    </ul>
  </nav>

  <section id="perfil">
    <h2>Perfil Profesional</h2>
    <p>Soy una ingeniera industrial con 5 años de experiencia en optimización de procesos logísticos y análisis de datos para la mejora continua.</p>
  </section>

  <section id="experiencia">
    <h2>Experiencia</h2>
    <ul>
      <li>2021–2025: Coordinadora de Logística - Transportes del Sur</li>
      <li>2018–2021: Analista de Procesos - Fábrica Eficiente</li>
    </ul>
  </section>
   
    <section id="habilidades"> <!-- Nueva sección -->
    <h2>Habilidades</h2>
    <ul>
      <li>Gestión de la cadena de suministro</li>
      <li>Optimización de procesos</li>
      <li>Manejo de SAP y Excel avanzado</li>
      <li>Trabajo en equipo y liderazgo</li>
    </ul>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p>Correo: ana.lopez@example.com</p>
    <p>Teléfono: +52 555 123 4567</p>
  </section>

  <footer>
    <p>&copy; 2025 Ana López</p>
  </footer>

  <style>
   /* Estilo general */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background-color: #f4f4f4;
  color: #333;
}

header {
  background-color: #808000;
  color: white;
  padding: 20px;
  text-align: center;
}

nav {
  background-color: #34495e;
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  text-align: center;
}

nav ul li {
  display: inline-block;
  margin: 0 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  padding: 15px;
  display: inline-block;
}

nav ul li a:hover {
  background-color: #1abc9c;
  border-radius: 5px;
}

section {
  padding: 20px;
  margin: 10px;
  background-color: white;
  border-radius: 10px;
}

footer {
  text-align: center;
  padding: 15px;
  background-color: #2c3e50;
  color: white;
  position: fixed;
  bottom: 0;
  width: 100%;
}
  .contenedor-header {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap; /* Se apila en pantallas pequeñas */
  gap: 20px;
}

.foto-perfil {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  object-fit: cover;
  border: 3px solid white;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
}

.info-header {
  text-align: center;
}

@media (min-width: 600px) {
  .info-header {
    text-align: left;
  }
}
   </style>

</body>
</html>
