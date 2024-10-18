# palomitadyva.github.io
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Loja Virtual</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: white;
      padding: 10px;
      text-align: center;
    }
    nav {
      background-color: #444;
      padding: 10px;
    }
    nav ul {
      list-style: none;
      padding: 0;
    }
    nav ul li {
      display: inline;
      margin-right: 20px;
    }
    nav ul li a {
      color: white;
      text-decoration: none;
    }
    .container {
      padding: 20px;
    }
    .product {
      border: 1px solid #ddd;
      padding: 10px;
      margin: 10px;
      display: inline-block;
    }
    .product img {
      width: 100px;
      height: 100px;
    }
    .product h3 {
      margin: 10px 0;
    }
    .product p {
      color: #888;
    }
  </style>
</head>
<body>

  <header>
    <h1>Minha Loja Virtual</h1>
  </header>

  <nav>
    <ul>
      <li><a href="#">Início</a></li>
      <li><a href="#">Produtos</a></li>
      <li><a href="#">Contato</a></li>
    </ul>
  </nav>

  <div class="container">
    <h2>Produtos em Destaque</h2>
    <div class="product">
      <img src="produto1.jpg" alt="Produto 1">
      <h3>Produto 1</h3>
      <p>R$ 100,00</p>
    </div>
    <div class="product">
      <img src="produto2.jpg" alt="Produto 2">
      <h3>Produto 2</h3>
      <p>R$ 150,00</p>
    </div>
    <div class="product">
      <img src="produto3.jpg" alt="Produto 3">
      <h3>Produto 3</h3>
      <p>R$ 200,00</p>
    </div>
  </div>

</body>
</html>
