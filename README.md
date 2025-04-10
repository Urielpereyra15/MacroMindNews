<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MacroMind News</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
    }
    header {
      background-color: #001f3f;
      color: white;
      padding: 15px 30px;
    }
    header h1 {
      font-size: 40px;
    }
    nav {
      background-color: #003366;
      padding: 10px 30px;
      display: flex;
      gap: 20px;
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
      padding: 30px;
      display: grid;
      grid-template-columns: 2fr 1fr;
      gap: 30px;
    }
    .noticia-principal {
      background-color: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .noticia-principal h2 {
      margin-bottom: 10px;
    }
    .noticia-principal p {
      color: #444;
    }
    .noticias-secundarias {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }
    .noticia-mini {
      background-color: white;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    }
    footer {
      background-color: #001f3f;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>MacroMind News</h1>
  </header>
  <nav>
    <a href="#">Inicio</a>
    <a href="#">Economía</a>
    <a href="#">Finanzas</a>
    <a href="#">Política</a>
    <a href="#">Internacional</a>
  </nav>
  <main>
    <div class="noticia-principal">
      <h2>Dólar blue alcanza nuevo récord: $1.365</h2>
      <p>El mercado cambiario muestra tensiones crecientes en la previa del posible acuerdo con el FMI.</p>
    </div>
    <div class="noticias-secundarias">
      <div class="noticia-mini">
        <h3>Acuerdo con el FMI: se tratará este viernes</h3>
        <p>Argentina busca cerrar un paquete de asistencia financiera por USD 20.000 millones.</p>
      </div>
      <div class="noticia-mini">
        <h3>Paro general del 10 de abril</h3>
        <p>La CGT paralizará sectores clave, incluido el sistema bancario.</p>
      </div>
      <div class="noticia-mini">
        <h3>Sube la tasa de plazos fijos</h3>
        <p>El BCRA ajusta la tasa para contener la inflación y fomentar el ahorro en pesos.</p>
      </div>
    </div>
  </main>
  <footer>
    &copy; 2025 MacroMind News - Todos los derechos reservados
  </footer>
</body>
</html>
