<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Fashion Store</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f8f8f8;
      color: #333;
    }
    header {
      background: #000;
      color: #fff;
      padding: 20px;
      text-align: center;
      font-size: 28px;
      letter-spacing: 2px;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 30px;
      background: #fff;
      padding: 15px 0;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    nav a {
      text-decoration: none;
      color: #000;
      font-size: 18px;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1521335629791-ce4aec67dd47') no-repeat center/cover;
      height: 70vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 0 2px 6px rgba(0,0,0,0.6);
      font-size: 48px;
      font-weight: bold;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px;
    }
    .product {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform .3s;
    }
    .product:hover {
      transform: scale(1.03);
    }
    .product img {
      width: 100%;
      height: 300px;
      object-fit: cover;
    }
    .product h3 {
      padding: 15px;
      margin: 0;
      font-size: 20px;
    }
    .footer {
      text-align: center;
      padding: 20px;
      background: #000;
      color: #fff;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>FASHION STORE</header>

  <nav>
    <a href="#">Новинки</a>
    <a href="#">Жінки</a>
    <a href="#">Чоловіки</a>
    <a href="#">Аксесуари</a>
  </nav>

  <div class="hero">NEW COLLECTION 2025</div>

  <section class="products">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab" alt="dress" />
      <h3>Елегантна сукня</h3>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1523381210434-271e8be1f52b" alt="coat" />
      <h3>Зимове пальто</h3>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1542273917363-3b1817f69a2d" alt="shoes" />
      <h3>Стильні черевики</h3>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1539109136881-3be0616acf4f" alt="bag" />
      <h3>Сумка преміум класу</h3>
    </div>
  </section>

  <footer class="footer">© 2025 Fashion Store</footer>
</body>
</html>
