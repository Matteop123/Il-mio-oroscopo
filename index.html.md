<!DOCTYPE html>  
<html lang="it">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>AstroApp - Segno e Ascendente</title>  
    <link rel="stylesheet" href="style.css">  
</head>  
<body>  
    <div class="container">  
        <h1>✨ Il Tuo Destino ✨</h1>  
        <p>Inserisci i tuoi dati per scoprire segno, ascendente e oroscopo.</p>  
          
        <div class="form-group">  
            <label>Giorno e Mese di Nascita</label>  
            <input type="date" id="birthdate" required>  
        </div>  
  
        <div class="form-group">  
            <label>Ora di Nascita (per l'Ascendente)</label>  
            <input type="time" id="birthtime" required>  
        </div>  
  
        <button onclick="calcolaAstro()">Scopri il Tuo Segno</button>  
  
        <div id="result" class="hidden">  
            <h2 id="user-sign"></h2>  
            <h3 id="user-ascendant"></h3>  
            <p id="horoscope-text"></p>  
        </div>  
    </div>  
    <script src="script.js"></script>  
</body>  
</html>  
