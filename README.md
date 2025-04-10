<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MacroMind News</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f9f9f9;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #0a0a23;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #1a1a40;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      display: grid;
      grid-template-columns: 3fr 1fr;
      gap: 30px;
      padding: 30px;
    }
    .main-news, .news-item {
      background-color: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .main-news h2, .news-item h3 {
      margin-bottom: 10px;
    }
    .main-news p, .news-item p {
      color: #555;
    }
    .side-news {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }
    .news-item a {
      text-decoration: none;
      color: #0a0a23;
      font-weight: bold;
    }
    .news-item a:hover {
      text-decoration: underline;
    }
    footer {
      background-color: #0a0a23;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>
  <header>
    <img src="img/logo.png" alt="Logo de MacroMind News" style="height: 60px;">
    <h1>MacroMind News</h1>
    <p>Tu fuente de análisis económico y financiero</p>
  </header>

  <nav>
    <a href="index.html">Inicio</a>
    <a href="#">Economía</a>
    <a href="#">Finanzas</a>
    <a href="#">Política</a>
    <a href="#">Internacional</a>
  </nav>

  <main>
    <section class="main-news">
      <h2><a href="noticia1.html">El dólar blue vuelve a subir: $1.365</a></h2>
      <img src="img/dolar.jpg" alt="Billete de dólar" style="width: 100%; max-width: 600px; border-radius: 8px; margin: 15px 0;">
      <p>En una jornada de alta tensión cambiaria, la cotización paralela del dólar alcanzó un nuevo máximo histórico, mientras crecen las expectativas por medidas del Gobierno.</p>
    </section>
    <aside class="side-news">
      <div class="news-item">
        <h3><a href="noticia2.html">Reunión clave con el FMI</a></h3>
        <p>El ministro de Economía confirmó que este viernes se cerraría el nuevo acuerdo con el Fondo.</p>
      </div>
      <div class="news-item">
        <h3><a href="noticia3.html">Plazos fijos: nueva tasa del BCRA</a></h3>
        <p>El Banco Central aumentó la tasa de interés al 90% para contener la inflación.</p>
      </div>
      <div class="news-item">
        <h3><a href="noticia4.html">Inflación de marzo: 11,5%</a></h3>
        <p>El INDEC confirmó un nuevo dato inflacionario preocupante, aunque menor al del mes anterior.</p>
      </div>
    </aside>
  </main>

  <footer>
    &copy; 2025 MacroMind News | Todos los derechos reservados
  </footer>
</body>
</html>
