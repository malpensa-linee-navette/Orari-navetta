<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <title>Orari Navetta Malpensa</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background-color: #f4f4f9;
      margin: 20px;
    }
    h1 {
      font-size: 2em;
      color: #2c3e50;
    }
    p {
      font-size: 1.1em;
    }
    .pdf-container {
      margin-top: 20px;
      width: 100%;
      height: 70vh; /* usa il 70% dell’altezza visibile */
    }
    iframe {
      width: 100%;
      height: 100%;
      border: none;
    }

    /* Regole speciali per schermi piccoli */
    @media (max-width: 600px) {
      h1 {
        font-size: 1.6em;
      }
      .pdf-container {
        height: 60vh; /* più basso su smartphone */
      }
    }
  </style>
</head>
<body>
  <h1>Orari Navetta Malpensa</h1>
  <p>Consulta direttamente gli orari qui sotto 👇</p>

  <div class="pdf-container">
    <iframe src="linee navetta.pdf"></iframe>
  </div>
</body>
</html>
