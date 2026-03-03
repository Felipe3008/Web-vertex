<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>TEST iPhone</title>
  <style>
    body{font-family:system-ui;margin:16px}
    .row{display:flex;gap:14px;align-items:center;flex-wrap:wrap}
    img{border:1px solid #ccc;border-radius:12px;padding:8px;background:#fff}
    #bar{
      position:fixed;top:0;left:0;height:100vh;width:220px;
      background:#111;color:#fff;padding:16px;display:none;
    }
    #bar a{color:#fff;display:block;margin:10px 0}
    button{padding:12px 14px;border-radius:12px;border:1px solid #222;background:#111;color:#fff;font-weight:800}
    .note{margin-top:12px;color:#333}
  </style>
</head>
<body>
  <button onclick="document.getElementById('bar').style.display = (document.getElementById('bar').style.display==='block'?'none':'block')">
    ÍNDICE (TEST)
  </button>

  <div id="bar">
    <strong>Barra OK</strong>
    <a href="#a">Ir a A</a>
    <a href="#b">Ir a B</a>
  </div>

  <p class="note">
    Si esto NO funciona en iPhone, el problema no es tu código “bonito”, es el entorno (cache / Pages / viewer).
  </p>

  <h3>PNG directos</h3>
  <div class="row">
    <img src="logo-mark-v41.png" width="90" alt="mark png">
    <img src="logo-full-v41.png" width="240" alt="full png">
  </div>

  <h3>SVG directos</h3>
  <div class="row">
    <img src="logo-mark-v41.svg" width="90" alt="mark svg">
    <img src="logo-full-v41.svg" width="240" alt="full svg">
  </div>

  <h3>Secciones</h3>
  <div id="a" style="margin-top:600px;padding:20px;border:1px solid #ccc;border-radius:12px">Sección A</div>
  <div id="b" style="margin-top:600px;padding:20px;border:1px solid #ccc;border-radius:12px">Sección B</div>
</body>
</html>