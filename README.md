<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Marketplace Cali</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Marketplace Cali</h1>
    <p>Encuentra las mejores empresas del centro de Cali</p>
  </header>

  <main>
    <section id="empresas">
      <h2>Empresas registradas</h2>
      <ul id="empresa-lista">
        <!-- Empresas se mostrarán aquí -->
      </ul>
    </section>

    <section id="mapa">
      <h2>Mapa de Ubicación</h2>
      <div id="mapa-cali" style="height: 400px;"></div>
    </section>
  </main>

  <script src="https://maps.googleapis.com/maps/api/js?key=TU_API_KEY"></script>
  <script src="src/app.js"></script>
</body>
</html>
