<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple E-commerce</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
        nav { background: #333; color: white; padding: 15px; text-align: center; }
        nav a { color: white; margin: 0 15px; text-decoration: none; }
        .container { padding: 20px; text-align: center; }
        .product { display: inline-block; border: 1px solid #ddd; margin: 10px; padding: 10px; text-align: center; }
        .product img { width: 150px; height: 150px; object-fit: cover; }
        .button { background: green; color: white; padding: 10px; cursor: pointer; border: none; }
    </style>
</head>
<body>
    <nav>
        <a href="index.html">Home</a>
        <a href="products.html">Products</a>
        <a href="checkout.html">Checkout</a>
    </nav>
    <div class="container">
        <h1>Welcome to Our Store</h1>
        <p>Find the best products here.</p>
    </div>
    
    <!-- Products Page -->
    <div class="container" id="products">
        <h2>Our Products</h2>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="iPhone 13">
            <h3>iPhone 13</h3>
            <p>$799</p>
            <button class="button">Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Samsung Galaxy S22">
            <h3>Samsung Galaxy S22</h3>
            <p>$699</p>
            <button class="button">Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Sony WH-1000XM4">
            <h3>Sony WH-1000XM4 Headphones</h3>
            <p>$349</p>
            <button class="button">Add to Cart</button>
        </div>
    </div>
    
    <!-- Checkout Page -->
    <div class="container" id="checkout">
        <h2>Checkout</h2>
        <p>Your cart is empty.</p>
        <button class="button">Place Order</button>
    </div>
</body>
</html>
