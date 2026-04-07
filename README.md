<!DOCTYPE html>
<html>
<head>
  <title>Shop ACC Game</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: Arial;
      background: #0f172a;
      color: white;
    }

    header {
      background: #020617;
      padding: 15px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      color: cyan;
      font-size: 20px;
    }

    .menu {
      font-size: 14px;
    }

    .menu span {
      margin-left: 10px;
      cursor: pointer;
    }

    .banner {
      background: linear-gradient(45deg, purple, blue);
      padding: 30px;
      text-align: center;
    }

    .banner h2 {
      margin: 0;
    }

    .container {
      padding: 15px;
    }

    .grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 10px;
    }

    .card {
      background: #1e293b;
      padding: 10px;
      border-radius: 12px;
      text-align: center;
      box-shadow: 0 0 10px rgba(0,255,255,0.3);
    }

    .card img {
      width: 100%;
      border-radius: 10px;
    }

    .price {
      color: yellow;
      margin: 5px 0;
    }

    button {
      width: 100%;
      padding: 8px;
      border: none;
      border-radius: 8px;
      background: cyan;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 15px;
      color: gray;
    }
  </style>
</head>

<body>

<header>
  <h1>🔥 SHOP ACC 🔥</h1>
  <div class="menu">
    <span>Trang chủ</span>
    <span>Liên hệ</span>
  </div>
</header>

<div class="banner">
  <h2>SHOP GAME UY TÍN 😎</h2>
  <p>Mua acc giá rẻ - Nhanh - An toàn</p>
</div>

<div class="container">
  <div class="grid">

    <div class="card">
      <img src="https://i.imgur.com/8Km9tLL.png">
      <h3>ACC Roblox VIP</h3>
      <div class="price">100.000đ</div>
      <button onclick="buy()">Mua</button>
    </div>

    <div class="card">
      <img src="https://i.imgur.com/QkIa5tT.png">
      <h3>ACC Free Fire</h3>
      <div class="price">150.000đ</div>
      <button onclick="buy()">Mua</button>
    </div>

    <div class="card">
      <img src="https://i.imgur.com/3ZQ3ZQy.png">
      <h3>ACC Liên Quân</h3>
      <div class="price">120.000đ</div>
      <button onclick="buy()">Mua</button>
    </div>

    <div class="card">
      <img src="https://i.imgur.com/UYiroys.png">
      <h3>ACC Minecraft</h3>
      <div class="price">80.000đ</div>
      <button onclick="buy()">Mua</button>
    </div>

  </div>
</div>

<footer>
  Liên hệ Zalo / Discord để mua acc
</footer>

<script>
function buy() {
  alert("Liên hệ admin để mua acc 😎");
}
</script>

</body>
</html>
