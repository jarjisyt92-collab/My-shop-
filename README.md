<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Shop</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
    }
    header {
      background: #007bff;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    .products {
      display: flex;
      justify-content: space-around;
      margin: 20px;
      flex-wrap: wrap;
    }
    .product {
      background: #fff;
      padding: 15px;
      margin: 10px;
      border-radius: 8px;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
      width: 250px;
      text-align: center;
    }
    .product img {
      max-width: 100%;
      border-radius: 5px;
    }
    .product h3 {
      margin: 10px 0;
    }
    .product button {
      background: #28a745;
      color: white;
      border: none;
      padding: 10px;
      border-radius: 5px;
      cursor: pointer;
    }
    .product button:hover {
      background: #218838;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Shop</h1>
    <p>Best Products at Best Prices</p>
  </header>

  <section class="products">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1511707171634-5f897ff02aa9" alt="Smartphone">
      <h3>Smartphone</h3>
      <p>$299</p>
      <button>Buy Now</button>
    </div>

    <div class="product">
      <img src="https://images.unsplash.com/photo-1581291519195-ef11498d1cf5" alt="Headphones">
      <h3>Headphones</h3>
      <p>$99</p>
      <button>Buy Now</button>
    </div>

    <div class="product">
      <img src="https://images.unsplash.com/photo-1512499617640-c2f999098cf0" alt="Watch">
      <h3>Smart Watch</h3>
      <p>$199</p>
      <button>Buy Now</button>
    </div>
  </section>
</body>
</html>
