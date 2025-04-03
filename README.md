
       <!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Products - Lakshmi Store</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/js/all.min.js" defer></script>
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <h1>Our Products</h1>
        <nav>
            <ul>
                <li><a href="index.html"><i class="fa fa-home"></i> Home</a></li>
                <li><a href="products.html"><i class="fa fa-box"></i> Products</a></li>
                <li><a href="cart.html"><i class="fa fa-shopping-cart"></i> Cart</a></li>
                <li><a href="checkout.html"><i class="fa fa-credit-card"></i> Checkout</a></li>
                <li><a href="contact.html"><i class="fa fa-envelope"></i> Contact</a></li>
                <li><a href="register.html"><i class="fa fa-user-plus"></i> Register</a></li>
                <li><a href="login.html"><i class="fa fa-sign-in-alt"></i> Login</a></li>
                <li><a href="referral.html"><i class="fa fa-share"></i> Referral</a></li>
                <li><a href="orders.html"><i class="fa fa-list"></i> Orders</a></li>
            </ul>
        </nav>
    </header><section id="product-list">
    <h2>Featured Products</h2>
    <div class="product">
        <img src="images/product1.jpg" alt="Product 1">
        <h3>Product 1</h3>
        <p>$10.00</p>
        <button onclick="addToCart('Product 1', 10)">Add to Cart</button>
    </div>
    <div class="product">
        <img src="images/product2.jpg" alt="Product 2">
        <h3>Product 2</h3>
        <p>$20.00</p>
        <button onclick="addToCart('Product 2', 20)">Add to Cart</button>
    </div>
    <div class="product">
        <img src="images/product3.jpg" alt="Product 3">
        <h3>Product 3</h3>
        <p>$15.00</p>
        <button onclick="addToCart('Product 3', 15)">Add to Cart</button>
    </div>
    <div class="product">
        <img src="images/product4.jpg" alt="Product 4">
        <h3>Product 4</h3>
        <p>$25.00</p>
        <button onclick="addToCart('Product 4', 25)">Add to Cart</button>
    </div>
</section>

</body>
</html>