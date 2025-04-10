<!DOCTYPE html>
<html lang="sk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>NFCSHOP</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
    }
    header {
      background: #222;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
      padding: 2rem;
      max-width: 1200px;
      margin: auto;
    }
    .product {
      background: white;
      border-radius: 10px;
      padding: 1rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      max-width: 100%;
      height: 200px;
      object-fit: contain;
      margin-bottom: 1rem;
    }
    .price {
      font-weight: bold;
      color: #28a745;
    }
    .buy-btn {
      display: inline-block;
      margin-top: 0.5rem;
      padding: 0.5rem 1rem;
      background: #007bff;
      color: white;
      border: none;
      border-radius: 5px;
      text-decoration: none;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #222;
      color: white;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>NFCSHOP</h1>
    <p>Šikovné NFC tagy pre každodenné použitie</p>
  </header>

  <section class="products">
    <div class="product">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9b/NFC_tag_icon.svg/2048px-NFC_tag_icon.svg.png" alt="NFC Tag 1" />
      <h2>NFC Tag Mini</h2>
      <p>Malý a praktický NFC tag ideálny na kľúče alebo nálepky.</p>
      <p class="price">3,99 €</p>
      <a href="mailto:tvojemail@example.com?subject=Objednávka NFC Tag Mini" class="buy-btn">Objednať</a>
    </div>

    <div class="product">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/45/NFC-logo.svg/2048px-NFC-logo.svg.png" alt="NFC Tag 2" />
      <h2>NFC Tag Sticker</h2>
      <p>Nálepka s NFC čipom – ideálna na marketing alebo domáce automatizácie.</p>
      <p class="price">3,99 €</p>
      <a href="mailto:tvojemail@example.com?subject=Objednávka NFC Tag Sticker" class="buy-btn">Objednať</a>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 NFCSHOP. Všetky práva vyhradené.</p>
  </footer>
</body>
</html>
