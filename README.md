<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>RIVA CELL - Exu-PE</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
      color: #000;
    }

    header {
      background-color: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }

    .container {
      padding: 20px;
      max-width: 1200px;
      margin: auto;
    }

    h1 {
      color: #333;
    }

    .map-container {
      margin-top: 20px;
      border: 2px solid #ccc;
      border-radius: 8px;
      overflow: hidden;
    }

    iframe {
      width: 100%;
      height: 400px;
      border: none;
    }

    footer {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }

    /* Google Translate positioning */
    #google_translate_element {
      position: fixed;
      top: 10px;
      right: 10px;
      z-index: 1000;
    }
  </style>
</head>
<body>

  <!-- Google Translate -->
  <div id="google_translate_element"></div>

  <script type="text/javascript">
    function googleTranslateElementInit() {
      new google.translate.TranslateElement({pageLanguage: 'pt', layout: google.translate.TranslateElement.InlineLayout.SIMPLE}, 'google_translate_element');
    }
  </script>
  <script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

  <header>
    <h1>RIVA CELL</h1>
    <p>Rua Padre Medeiros N°40 - Exu, Pernambuco</p>
  </header>

  <div class="container">
    <h2>Bem-vindo à RIVA CELL</h2>
    <p>Especialistas em tecnologia, manutenção e acessórios para celulares. Visite nossa loja física em Exu-PE.</p>

    <div class="map-container">
      <!-- Google Maps -->
      <iframe 
        src="https://www.google.com/maps?q=Rua%20Padre%20Medeiros%2040,%20Exu-PE&output=embed"
        allowfullscreen
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade">
      </iframe>
    </div>
  </div>

  <footer>
    <p>&copy; 2025 RIVA CELL - Todos os direitos reservados.</p>
  </footer>

</body>
</html>
