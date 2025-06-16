<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AntiUčitel 3000 - Objednávka</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }
    .container {
      max-width: 800px;
      margin: 30px auto;
      background-color: #fff;
      padding: 20px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      border-radius: 8px;
    }
    h1, h2 {
      margin-top: 0;
    }
    .product-info {
      margin-bottom: 20px;
    }
    .price {
      font-size: 1.5em;
      color: #e74c3c;
      margin-bottom: 10px;
    }
    form label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }
    form input, form textarea, form select {
      width: 100%;
      padding: 8px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 4px;
      box-sizing: border-box;
    }
    form button {
      background-color: #27ae60;
      color: #fff;
      padding: 10px 20px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-size: 1em;
    }
    form button:hover {
      background-color: #219150;
    }
    footer {
      text-align: center;
      padding: 20px 0;
      font-size: 0.9em;
      color: #777;
    }
  </style>
</head>
<body>
  <header>
    <h1>AntiUčitel 3000</h1>
    <p>Učitel za rohem? TikTok zmizel!</p>
  </header>
  <div class="container">
    <section class="product-info">
      <h2>Malé chytré zařízení pro každý školní den</h2>
      <p>AntiUčitel 3000 je nenápadná krabička, která rozezná příchod učitele a během vteřiny přepne mobil z TikToku nebo her na kalkulačku.</p>
      <p class="price">Cena: 349 Kč</p>
      <p><strong>Dostupné funkce:</strong></p>
      <ul>
        <li>Detekce zvuku učitele (kroky, hlas, typické fráze)</li>
        <li>Automatické přepnutí aplikace</li>
        <li>Nenápadný design (vypadá jako guma nebo USB)</li>
        <li>Režim "Panika" – jedním klikem schová všechno podezřelé</li>
      </ul>
    </section>
    <section class="order-form">
      <h2>Objednávkový formulář</h2>
      <form action="https://formsubmit.co/z18106@santoska.cz" method="POST">
        <label for="name">Jméno a příjmení:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">E-mail:</label>
        <input type="email" id="email" name="email" required>

        <label for="quantity">Počet kusů:</label>
        <select id="quantity" name="quantity">
          <option value="1">1</option>
          <option value="2">2</option>
          <option value="3">3</option>
          <option value="4">4</option>
          <option value="5">5</option>
        </select>

        <label for="address">Adresa pro doručení:</label>
        <textarea id="address" name="address" rows="3" required></textarea>

        <!-- Skryté nastavení -->
        <input type="hidden" name="_subject" value="Nová objednávka AntiUčitel 3000!">
        <input type="hidden" name="_captcha" value="false">
        <input type="hidden" name="_autoresponse" value="Děkujeme za objednávku AntiUčitel 3000! Brzy se vám ozveme. Pokud máte otázky, napište nám.">

        <button type="submit">Odeslat objednávku</button>
      </form>
    </section>
  </div>
  <footer>
    &copy; 2025 AntiUčitel 3000. Všechna práva vyhrazena.
  </footer>
</body>
</html>
