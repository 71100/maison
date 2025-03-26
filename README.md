<!DOCTYPE html>
<html lang="fr">
<head>
background-color: #e91e63;
    color: white;
    border:
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marketplace Futuriste</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #282c34;
            color: white;
            padding: 1em;
            text-align: center;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 2em;
        }
        .product {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 1em;
            padding: 1em;
            width: 200px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .product img {
            max-width: 100%;
            border-radius: 5px 5px 0 0;
        }
        .product h2 {
            font-size: 1.2em;
            margin: 0.5em 0;
        }
        .product p {
            margin: 0.5em 0;
        }
        .product .price {
            color: #e91e63;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <h1>Marketplace Futuriste</h1>
    </header>
    <div class="container">
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product Image">
            <h2>Produit 1</h2>
            <p>Description du produit 1.</p>
            <p class="price">€100</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product Image">
            <h2>Produit 2</h2>
            <p>Description du produit 2.</p>
            <p class="price">€200</p>
        </div>
        <!-- Ajoutez plus de produits ici -->
    </div>
</body>
</html>