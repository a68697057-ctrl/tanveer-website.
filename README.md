<!DOCTYPE html>
<html>
<head>
  <title>Tanveer Shop</title>

  <style>
    body{
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      text-align: center;
      background: linear-gradient(135deg, #ff6ec4, #7873f5, #4facfe);
      background-size: 400% 400%;
      animation: bg 10s infinite alternate;
      color: white;
    }

    @keyframes bg{
      0%{background-position: left;}
      100%{background-position: right;}
    }

    h1{
      font-size: 55px;
      margin-top: 30px;
      text-shadow: 3px 3px 10px black;
    }

    p{
      font-size: 20px;
    }

    .container{
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 25px;
      margin-top: 40px;
    }

    .box{
      background: rgba(255,255,255,0.2);
      backdrop-filter: blur(10px);
      border: 2px solid white;
      color: white;
      padding: 25px;
      width: 280px;
      border-radius: 20px;
      box-shadow: 0px 0px 20px rgba(0,0,0,0.4);
      transition: 0.4s;
    }

    .box:hover{
      transform: scale(1.08);
      box-shadow: 0px 0px 25px yellow;
    }

    h2{
      font-size: 30px;
    }

    .price{
      font-size: 25px;
      color: yellow;
      font-weight: bold;
    }

    button{
      background: linear-gradient(to right, orange, red);
      color: white;
      border: none;
      padding: 12px 25px;
      border-radius: 30px;
      cursor: pointer;
      font-size: 18px;
      font-weight: bold;
      transition: 0.3s;
    }

    button:hover{
      background: linear-gradient(to right, limegreen, green);
      transform: scale(1.1);
    }

    footer{
      margin-top: 50px;
      padding: 20px;
      font-size: 18px;
      color: #fff;
    }
  </style>
</head>

<body>

  <h1>🌈 Tanveer Class Shop 😎</h1>

  <p>🔥 Best paper items in the class 🔥</p>

  <div class="container">

    <div class="box">
      <h2>✈ Paper Aeroplane</h2>
      <p class="price">₹10</p>
      <button>Buy Now</button>
    </div>

    <div class="box">
      <h2>🗡 Paper Sword</h2>
      <p class="price">₹20</p>
      <button>Buy Now</button>
    </div>

    <div class="box">
      <h2>📄 A4 Sheets</h2>
      <p class="price">₹5</p>
      <button>Buy Now</button>
    </div>

  </div>

  <footer>
    ⭐ Made  By  Tanveer ⭐
  </footer>

</body>
</html>
