<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Lavado de Autos</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #00B8D4;
      --accent: #00796B;
      --light: #f0f0f0;
      --dark: #1a1a1a;
      --white: #fff;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background-color: var(--light);
      color: var(--dark);
    }

    header {
      background: linear-gradient(to right, var(--primary), var(--accent));
      color: var(--white);
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
    }

    nav {
      background-color: var(--dark);
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px 0;
    }

    nav a {
      color: var(--white);
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s;
    }

    nav a:hover {
      color: var(--primary);
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }

    .card {
      background-color: var(--white);
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card h3 {
      margin-bottom: 10px;
      color: var(--accent);
    }

    .contact {
      background-color: var(--primary);
      color: var(--white);
      padding: 40px 20px;
      text-align: center;
    }

    footer {
      background-color: #111;
      color: #ccc;
      text-align: center;
      padding: 20px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Lavado de Autos Profesional</h1>
    <p>Tu auto limpio, como nuevo. Calidad, rapidez y confianza.</p>
  </header>

  <nav>
    <a href="#servicios">Servicios</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="servicios">
    <h2 style="text-align:center; margin-bottom:30px;">Nuestros Servicios</h2>
    <div class="services">
      <div class="card">
        <h3>Lavado Básico</h3>
        <p>Incluye lavado exterior con productos premium y secado manual.</p>
      </div>
      <div class="card">
        <h3>Lavado Completo</h3>
        <p>Limpieza interior y exterior, aspirado y aromatizante incluido.</p>
      </div>
      <div class="card">
        <h3>Lavado Premium</h3>
        <p>Descontaminado, cera, pulido ligero y limpieza profunda del interior.</p>
      </div>
      <div class="card">
        <h3>Detalle de Motor</h3>
        <p>Lavado cuidadoso del motor con productos especiales sin dañar componentes.</p>
      </div>
    </div>
  </section>

  <section class="contact" id="contacto">
    <h2>Contáctanos</h2>
    <p>Estamos listos para atenderte. Visítanos o escríbenos por WhatsApp o redes sociales.</p>
  </section>

  <footer>
    <p>&copy; 2025 Lavado de Autos. Todos los derechos reservados.</p>
  </footer>

</body>
</html>
