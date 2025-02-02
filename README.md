# project3
//html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navigation Bar -->
    <nav>
        <div class="logo">ShopEasy</div>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Shop</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <!-- Product Section -->
    <div class="product-container">
        <div class="product-image">
            <img src="images/product.jpg" alt="Product Image">
        </div>
        <div class="product-details">
            <h1>Wireless Headphones</h1>
            <p class="price">$99.99</p>
            <p class="description">
                High-quality wireless headphones with noise cancellation and long battery life. Perfect for music lovers and travelers.
            </p>
            <button class="add-to-cart">Add to Cart</button>
        </div>
    </div>


//css

/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f8f8;
}

/* Navigation Bar */
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #333;
    padding: 15px;
}

nav .logo {
    color: white;
    font-size: 1.5rem;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-size: 1rem;
}

nav ul li a:hover {
    text-decoration: underline;
}

/* Product Section */
.product-container {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 50px;
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.product-image img {
    width: 300px;
    border-radius: 5px;
}

.product-details {
    margin-left: 30px;
    max-width: 400px;
}

.product-details h1 {
    font-size: 2rem;
    color: #333;
}

.price {
    font-size: 1.5rem;
    color: #e60023;
    font-weight: bold;
}

.description {
    font-size: 1rem;
    color: #666;
    margin: 15px 0;
}

.add-to-cart {
    background-color: #e60023;
    color: white;
    padding: 10px 20px;
    font-size: 1rem;
    border: none;
    cursor: pointer;
    border-radius: 5px;
}

.add-to-cart:hover {
    background-color: #b5001a;
}

/* Responsive Design */
@media (max-width: 768px) {
    .product-container {
        flex-direction: column;
        text-align: center;
    }

    .product-details {
        margin-left: 0;
    }

    .product-image img {
        width: 80%;
    }
}
</body>
</html>


