<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <title>Moto Store</title>
  <style>
    body {
      margin: 0;
      font-family: Arial;
      background: black;
      color: white;
    }

    header {
      background: #111;
      padding: 15px;
      text-align: center;
    }

    header .logo {
      color: red;
      font-size: 24px;
      font-weight: bold;
    }

    nav a {
      margin: 0 10px;
      text-decoration: none;
      color: white;
    }

    nav a:hover {
      color: red;
    }

    .hero {
      text-align: center;
      padding: 50px;
      position: relative;
    }

    .hero h1 {
      font-size: 40px;
    }

    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 10px 20px;
      background: red;
      color: white;
      text-decoration: none;
      border-radius: 20px;
    }

    .sticker {
      font-size: 120px;
      text-shadow: 0 0 15px red;
      margin-top: 30px;
    }

    .line {
      position: absolute;
      width: 200px;
      height: 100px;
      border: 2px solid;
      border-radius: 50%;
      opacity: 0.7;
      animation: move 4s infinite alternate;
    }

    .red { border-color: red; box-shadow: 0 0 10px red; }
    .green { border-color: lime; box-shadow: 0 0 10px lime; }

    .l1 { top: 20%; left: 10%; }
    .l2 { bottom: 20%; right: 15%; }
    .l3 { top: 40%; right: 5%; }

    @keyframes move {
      from { transform: rotate(0deg); }
      to { transform: rotate(15deg); }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">🏍️ Moto Store</div>
    <nav>
      <a href="#">Home</a>
      <a href="#">Products</a>
      <a href="#">About</a>
    </nav>
  </header>

  <section class="hero">
    <h1><span style="color:red">Moto</span> Shop</h1>
    <p>Купуй стильні та надійні мотоцикли та дивись не розбийся бо це на нашій совіісті(шуткаааа НЄЄЄЄЄ).<br>Відчуй свободу та швидкість!</p>
    <a href="#" class="btn">Get Started</a>

    <div class="sticker">🏍️</div>

    <!-- прості неонові лінії -->
    <div class="line red l1"></div>
    <div class="line green l2"></div>
    <div class="line red l3"></div>
  </section>
</body>
</html>
