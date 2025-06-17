<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Магазин</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: white;
      padding: 1em;
      text-align: center;
    }
    main {
      padding: 2em;
      display: flex;
      justify-content: center;
    }
    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 1.5em;
      width: 100%;
      max-width: 1200px;
    }
    .product-card {
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 1em;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.2s ease;
    }
    .product-card:hover {
      transform: translateY(-5px);
    }
    .product-card img {
      max-width: 100%;
      border-radius: 4px;
    }
    .product-name {
      font-size: 1.1em;
      margin: 0.5em 0;
    }
    .product-price {
      color: green;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <header>
    <h1>Добро пожаловать в наш магазин</h1>
  </header>

  <main>
    <div class="product-grid">
      <div class="product-card">
        <img src="https://via.placeholder.com/200x150" alt="Товар 1">
        <div class="product-name">Товар 1</div>
        <div class="product-price">1 000 ₽</div>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/200x150" alt="Товар 2">
        <div class="product-name">Товар 2</div>
        <div class="product-price">1 500 ₽</div>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/200x150" alt="Товар 3">
        <div class="product-name">Товар 3</div>
        <div class="product-price">2 000 ₽</div>
      </div>
    </div>
  </main>

</body>
</html>
# epic
