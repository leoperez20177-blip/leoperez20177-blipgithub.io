# leoperez20177-blipgithub.io
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Emprendimiento de Maquillaje</title>
  <style>
    /* Reset básico */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Helvetica Neue', sans-serif;
      background: #fafafa;
      color: #333;
      line-height: 1.6;
    }

    /* Navbar */
    header {
      position: fixed;
      top: 0;
      width: 100%;
      background: white;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      z-index: 1000;
    }

    nav {
      display: flex;
      justify-content: space-around;
      padding: 1rem;
    }

    nav a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #d86ba8;
    }

    /* Secciones */
    section {
      min-height: 100vh;
      padding: 6rem 2rem 2rem 2rem;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    section h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
      color: #d86ba8;
    }

    section p {
      max-width: 600px;
      margin-bottom: 2rem;
    }

    /* Botón */
    .btn {
      padding: 0.7rem 1.5rem;
      border: none;
      background: #d86ba8;
      color: white;
      border-radius: 25px;
      cursor: pointer;
      transition: background 0.3s;
    }

    .btn:hover {
      background: #b45488;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 2rem;
      background: #fff;
      box-shadow: 0 -2px 5px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <a href="#inicio">Inicio</a>
      <a href="#labios">Labios</a>
      <a href="#ojos">Ojos</a>
      <a href="#skincare">Skin Care</a>
      <a href="#cara">Cara</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section id="inicio">
    <h1>Bienvenid@s</h1>
    <p>Descubrí la mejor colección de maquillaje para resaltar tu belleza natural.</p>
    <button class="btn">Ver productos</button>
  </section>

  <section id="labios">
    <h1>Labios</h1>
    <p>Lipsticks, glosses y bálsamos para darle color y vida a tu sonrisa.</p>
  </section>

  <section id="ojos">
    <h1>Ojos</h1>
    <p>Sombras, delineadores y máscaras de pestañas para una mirada intensa.</p>
  </section>

  <section id="skincare">
    <h1>Skin Care</h1>
    <p>Productos pensados para cuidar y nutrir tu piel antes y después del maquillaje.</p>
  </section>

  <section id="cara">
    <h1>Cara</h1>
    <p>Bases, rubores e iluminadores para un acabado perfecto.</p>
  </section>

  <section id="contacto">
    <h1>Contacto</h1>
    <p>¿Querés saber más sobre nuestros productos? Escribinos.</p>
    <button class="btn">Enviar mensaje</button>
  </section>

  <footer>
    <p>© 2025 Emprendimiento de Maquillaje - Todos los derechos reservados</p>
  </footer>
</body>
</html>
