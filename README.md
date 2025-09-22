# leoperez20177-blipgithub.io
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Emprendimiento de Maquillaje</title>
  <style>
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
      text-align: center;
    }

    section h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
      color: #d86ba8;
    }

    section p {
      max-width: 600px;
      margin: 0 auto 2rem;
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

    /* Tarjetas de productos */
    .productos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }

    .card {
      background: white;
      border-radius: 15px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .card h3 {
      margin: 1rem;
      color: #d86ba8;
    }

    .card p {
      margin: 0 1rem 1rem;
      font-size: 0.9rem;
    }

    .card .btn {
      margin: 1rem;
      width: calc(100% - 2rem);
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

  <!-- Inicio -->
  <section id="inicio">
    <h1>Bienvenid@s</h1>
    <p>Descubrí nuestra línea de maquillaje y cuidado de la piel pensada para vos.</p>
    <button class="btn">Explorar productos</button>
  </section>

  <!-- Labios -->
  <section id="labios">
    <h1>Labios</h1>
    <p>Colores vibrantes y fórmulas hidratantes para resaltar tu sonrisa.</p>
    <div class="productos">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1589998059171-988d887df646" alt="Labial">
        <h3>Labial Mate</h3>
        <p>Acabado intenso y larga duración.</p>
        <button class="btn">Comprar</button>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1600185365926-3e4dfc8de5ba" alt="Gloss">
        <h3>Gloss Brillante</h3>
        <p>Un toque de brillo con efecto volumen.</p>
        <button class="btn">Comprar</button>
      </div>
    </div>
  </section>

  <!-- Ojos -->
  <section id="ojos">
    <h1>Ojos</h1>
    <p>Sombras, delineadores y máscaras de pestañas para una mirada cautivadora.</p>
    <div class="productos">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1612101212215-6c8848b6fb0f" alt="Sombras">
        <h3>Paleta de Sombras</h3>
        <p>Colores versátiles para todo tipo de looks.</p>
        <button class="btn">Comprar</button>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1620912189860-6ce3dc48d870" alt="Máscara de pestañas">
        <h3>Máscara Voluminizadora</h3>
        <p>Pestañas más largas y definidas.</p>
        <button class="btn">Comprar</button>
      </div>
    </div>
  </section>

  <!-- Skin Care -->
  <section id="skincare">
    <h1>Skin Care</h1>
    <p>Cuidá tu piel con nuestra línea especializada en hidratación y nutrición.</p>
    <div class="productos">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1596755389378-c31d21fd1273" alt="Crema hidratante">
        <h3>Crema Hidratante</h3>
        <p>Nutrición profunda y rápida absorción.</p>
        <button class="btn">Comprar</button>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1585238342029-2a46e19d0fda" alt="Serum">
        <h3>Sérum Facial</h3>
        <p>Regeneración y luminosidad para tu piel.</p>
        <button class="btn">Comprar</button>
      </div>
    </div>
  </section>

  <!-- Cara -->
  <section id="cara">
    <h1>Cara</h1>
    <p>Bases, rubores e iluminadores para un acabado perfecto.</p>
    <div class="productos">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1612817159949-1dfdc22f8d64" alt="Base líquida">
        <h3>Base Líquida</h3>
        <p>Cobertura uniforme y natural.</p>
        <button class="btn">Comprar</button>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1612817158427-51a4a05a9861" alt="Iluminador">
        <h3>Iluminador</h3>
        <p>Brillo sutil para realzar tu look.</p>
        <button class="btn">Comprar</button>
      </div>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto">
    <h1>Contacto</h1>
    <p>¿Querés saber más sobre nuestros productos? ¡Escribinos!</p>
    <button class="btn">Enviar mensaje</button>
  </section>

  <footer>
    <p>© 2025 Emprendimiento de Maquillaje - Todos los derechos reservados</p>
  </footer>
</body>
</html>
