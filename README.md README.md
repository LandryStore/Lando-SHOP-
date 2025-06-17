<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lando SHOP</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    header {
      background-color: #0099cc;
      color: white;
      padding: 20px;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin: 20px;
    }
    .product {
      background: white;
      border: 1px solid #ddd;
      margin: 10px;
      padding: 15px;
      width: 250px;
    }
    .buy-button {
      display: inline-block;
      padding: 10px 20px;
      background-color: #0099cc;
      color: white;
      text-decoration: none;
      margin-top: 10px;
      border-radius: 5px;
    }
    footer {
      background-color: #0099cc;
      color: white;
      padding: 10px;
      margin-top: 30px;
    }
    form {
      margin: 30px auto;
      padding: 20px;
      background: white;
      width: 300px;
      border-radius: 8px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bienvenue sur LandoSHOP</h1>
    <p>Des produits tendances, pratiques et livrés rapidement.</p>
  </header>

  <div class="products">
    <div class="product">
      <h3>Keshuyou H9 Pro Max</h3>
      <p>Nouvelle montre intelligente</p>
      <a class="buy-button" href="#">Acheter</a>
    </div>
    <div class="product">
      <h3>Disney Snoopy</h3>
      <p>Sac cartoon grande capacité</p>
      <a class="buy-button" href="#">Acheter</a>
    </div>
    <div class="product">
      <h3>Pantalon casual homme</h3>
      <p>Coupe droite, taille élastique</p>
      <a class="buy-button" href="#">Acheter</a>
    </div>
  </div>

  <form>
    <h3>Contactez-nous</h3>
    <input type="text" placeholder="Votre nom" required><br><br>
    <input type="email" placeholder="Votre email" required><br><br>
    <textarea placeholder="Votre message"></textarea><br><br>
    <button type="submit">Envoyer</button>
  </form>

  <footer>
    <p>Suivez-nous : 
      <a href="#">Facebook</a> | 
      <a href="#">Instagram</a> | 
      <a href="#">TikTok</a>
    </p>
    <p>© 2025 LandoShop.com</p>
  </footer>
</body>
</html>
