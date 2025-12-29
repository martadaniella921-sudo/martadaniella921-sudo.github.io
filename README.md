<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Aprende con Dani</title>

  <!-- Tipografía -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #f7f7f7;
      color: #1f2937;
      line-height: 1.6;
    }

    .container {
      max-width: 1100px;
      margin: auto;
      padding: 60px 20px;
    }

    h1 {
      font-size: 42px;
      font-weight: 700;
      margin-bottom: 20px;
    }

    h2 {
      font-size: 28px;
      margin-top: 60px;
      margin-bottom: 20px;
    }

    p {
      font-size: 16px;
      color: #374151;
    }

    .hero {
      background: white;
      border-radius: 16px;
      padding: 60px;
      text-align: center;
      box-shadow: 0 10px 30px rgba(0,0,0,0.05);
    }

    .hero a {
      display: inline-block;
      margin-top: 30px;
      background: #16a34a;
      color: white;
      padding: 14px 28px;
      border-radius: 999px;
      text-decoration: none;
      font-weight: 600;
    }

    .about {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 40px;
      margin-top: 80px;
    }

    .about img {
      width: 100%;
      border-radius: 16px;
      object-fit: cover;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 30px;
      margin-top: 40px;
    }

    .card {
      background: white;
      padding: 30px;
      border-radius: 16px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.04);
    }

    .card h3 {
      margin-top: 0;
      font-size: 18px;
    }

    .card a {
      color: #16a34a;
      font-weight: 600;
      text-decoration: none;
    }

    .cta {
      margin-top: 100px;
      background: #ecfdf5;
      padding: 50px;
      border-radius: 20px;
      text-align: center;
    }

    footer {
      text-align: center;
      padding: 40px;
      font-size: 14px;
      color: #6b7280;
    }

    @media (max-width: 768px) {
      .about {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>

  <div class="container">

    <!-- HERO -->
    <section class="hero">
      <h1>Aprende a generar ingresos online con orden</h1>
      <p>Guías gratuitas, procesos reales y caminos claros para empezar en 2026 sin repetir errores ni caer en promesas vacías.</p>
      <a href="#guias">Empieza aquí</a>
    </section>

    <!-- SOBRE MI -->
    <section class="about">
      <div>
        <h2>Soy Dani</h2>
        <p>
          Invertí buscando resultados rápidos y me equivoqué.
          Me saturé de cursos, información desordenada y falsas expectativas.
        </p>
        <p>
          Hoy organizo procesos reales para que otras personas no repitan esos errores.
          Aquí comparto lo que sí funciona, con claridad y sin presión.
        </p>
      </div>
      <div>
        <!-- AQUÍ LUEGO PONEMOS TU FOTO -->
        <img src="https://via.placeholder.com/500x600" alt="Dani">
      </div>
    </section>

    <!-- PARA QUIÉN -->
    <section>
      <h2>¿Para quién es esta página?</h2>
      <ul>
        <li>Personas que ya invirtieron y no vieron resultados</li>
        <li>Personas confundidas por demasiada información</li>
        <li>Quienes quieren empezar sin gastar más dinero</li>
        <li>Quienes buscan procesos reales y ordenados</li>
      </ul>
    </section>

    <!-- GUÍAS -->
    <section id="guias">
      <h2>Guías gratuitas – empieza con orden</h2>

      <div class="cards">
        <div class="card">
          <h3>1️⃣ Marca personal (antes de invertir)</h3>
          <p>Qué definir antes de gastar dinero o entrar a una academia.</p>
          <a href="#">Ver guía →</a>
        </div>

        <div class="card">
          <h3>2️⃣ Dónde está el dinero online en 2026</h3>
          <p>Opciones reales, sin humo ni promesas irreales.</p>
          <a href="#">Ver guía →</a>
        </div>

        <div class="card">
          <h3>3️⃣ Afiliaciones (Amazon, Target, Walmart)</h3>
          <p>Cómo empezar sin producto ni inversión.</p>
          <a href="#">Ver guía →</a>
        </div>
      </div>
    </section>

    <!-- CTA SUAVE -->
    <section class="cta">
      <h2>¿Quieres acompañamiento?</h2>
      <p>Si en algún momento quieres trabajar conmigo de forma más personalizada, aquí te explico cómo.</p>
      <a href="#" style="color:#16a34a;font-weight:600;">Ver opciones →</a>
    </section>

  </div>

  <footer>
    © 2026 · Aprende con Dani · Procesos reales, sin humo
  </footer>

</body>
</html>
