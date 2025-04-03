<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lakshmi Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Lakshmi Store</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#cart">Cart</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header><section id="products">
    <h2>Our Products</h2>
    <div class="product" id="product1">
        <p>Product 1 - $10</p>
        <button onclick="addToCart('Product 1', 10)">Add to Cart</button>
    </div>
    <div class="product" id="product2">
        <p>Product 2 - $20</p>
        <button onclick="addToCart('Product 2', 20)">Add to Cart</button>
    </div>
</section>

<section id="cart">
    <h2>Shopping Cart</h2>
    <ul id="cart-items"></ul>
    <p>Total: $<span id="total">0</span></p>
</section>

<script src="script.js"></script>

</body>
</html>