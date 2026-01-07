<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Joyería & Tatuajes | Tu Marca</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0f0f0f;
      color: #f5f5f5;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(135deg, #000, #1c1c1c);
      padding: 3rem 1rem;
      text-align: center;
    }
    header h1 {
      font-size: 3rem;
      letter-spacing: 2px;
    }
    header p {
      margin-top: 1rem;
      font-size: 1.2rem;
      color: #ccc;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
      background-color: #111;
      position: sticky;
      top: 0;
    }
    nav a {
      color: #f5f5f5;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover { color: #d4af37; }
    section {
      padding: 4rem 1.5rem;
      max-width: 1100px;
      margin: auto;
    }
    section h2 {
      font-size: 2.2rem;
      margin-bottom: 1.5rem;
      color: #d4af37;
      text-align: center;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    .card {
      background-color: #1a1a1a;
      padding: 2rem;
      border-radius: 12px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.5);
      transition: transform 0.3s;
    }
    .card:hover { transform: translateY(-5px); }
    .card h3 { margin-bottom: 1rem; }
    .card p { color: #ccc; }
    .cta {
      text-align: center;
      margin-top: 3rem;
    }
    .cta a {
      background-color: #d4af37;
      color: #000;
      padding: 1rem 2rem;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
    }

    /* BOTONES FLOTANTES */
    .float-btn {
      position: fixed;
      right: 20px;
      width: 60px;
      height: 60px;
      border-radius: 50%;
      display: flex;
      justify-content: center;
      align-items: center;
      text-decoration: none;
      box-shadow: 0 4px 10px rgba(0,0,0,0.4);
      z-index: 999;
      transition: transform 0.2s;
    }
    .float-btn:hover {
      transform: scale(1.1);
    }
    .float-btn img {
      width: 35px;
      height: 35px;
    }

    /* WhatsApp */
    .whatsapp {
      bottom: 20px;
      background: #25D366;
    }

    /* Instagram */
    .instagram {
      bottom: 90px;
      background: #E1306C;
    }

    footer {
      background-color: #000;
      padding: 2rem 1rem;
      text-align: center;
      color: #777;
    }
  </style>
</head>
<body>
  <header>
    <h1>Joyería & Tatuajes</h1>
    <p>Arte eterno en piel y metal</p>
  </header>

  <nav>
    <a href="#joyeria">Joyería</a>
    <a href="#tatuajes">Tatuajes</a>
    <a href="#sobre">Sobre Nosotros</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="joyeria">
    <h2>Joyería</h2>
    <div class="grid">
      <div class="card">
        <h3>Piezas Personalizadas</h3>
        <p>Anillos, collares y pulseras diseñadas a tu medida con materiales de alta calidad.</p>
      </div>
      <div class="card">
        <h3>Diseño Artesanal</h3>
        <p>Cada pieza es única, creada con atención al detalle y pasión por el arte.</p>
      </div>
    </div>
  </section>

  <section id="tatuajes">
    <h2>Tatuajes</h2>
    <div class="grid">
      <div class="card">
        <h3>Diseños Originales</h3>
        <p>Tatuajes personalizados que cuentan tu historia y reflejan tu identidad.</p>
      </div>
      <div class="card">
        <h3>Estudio Profesional</h3>
        <p>Ambiente seguro, higiénico y artístico con profesionales experimentados.</p>
      </div>
    </div>
  </section>

  <section id="sobre">
    <h2>Sobre Nosotros</h2>
    <p style="text-align:center; max-width:800px; margin:auto; color:#ccc;">
      Somos un estudio creativo que une la joyería y el tatuaje como formas de arte permanente. 
      Creemos en la expresión personal, la calidad y el diseño exclusivo.
    </p>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>

    <div class="cta">
      <p style="margin-bottom:1.5rem; color:#ccc;">Agenda tu cita o consulta sin compromiso</p>

      <!-- BOTÓN EMAIL -->
      <a href="mailto:contacto@tumarca.com">Escríbenos</a>
    </div>
  </section>

  <!-- BOTÓN WHATSAPP -->
  <a class="float-btn whatsapp" 
     href="https://wa.me/34655665363?text=Hola%2C%20quiero%20informaci%C3%B3n%20sobre%20joyer%C3%ADa%20o%20tatuajes." 
     target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
  </a>

  <!-- BOTÓN INSTAGRAM -->
  <a class="float-btn instagram" 
     href="https://instagram.com/elisa.e.m" 
     target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram">
  </a>

  <footer>
    <p>© 2026 Joyería & Tatuajes · Todos los derechos reservados</p>
  </footer>
</body>
</html>
