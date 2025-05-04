# Final Project and Deployment

## Objectives
Build a fully functional web application.
Apply HTML, CSS, and JavaScript concepts learned.
Deploy the project using GitHub Pages, Netlify, or Vercel.

## Instructions
Choose one of the following project ideas:
Blog Website: Implement a multi-page site with navigation.
Ecommerce Website: Implement a multi-page site with navigation.

>[!NOTE]
> - Include at least:
> - A responsive design.
> - JavaScript interactivity.
> - A deployment link.

## Tasks

Create a well-structured HTML5 document.
Use at least 5 different HTML elements.
Ensure semantic correctness.

Good luck and happy coding! 🚀💻



ndex.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ecommerce Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="cart.html">Cart</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h1>Welcome to our ecommerce website</h1>
            <p>This is a sample ecommerce website built using HTML, CSS, and JavaScript.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Ecommerce Website</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
```

products.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Products</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="cart.html">Cart</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h1>Our Products</h1>
            <ul id="product-list">
                <li>
                    <h2>Product 1</h2>
                    <p>Price: $10</p>
                    <button>Add to Cart</button>
                </li>
                <li>
                    <h2>Product 2</h2>
                    <p>Price: $20</p>
                    <button>Add to Cart</button>
                </li>
                <li>
                    <h2>Product 3</h2>
                    <p>Price: $30</p>
                    <button>Add to Cart</button>
                </li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Ecommerce Website</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
```

cart.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cart</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="cart.html">Cart</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h1>Your Cart</h1>
            <ul id="cart-list">
                <!-- Cart items will be displayed here -->
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Ecommerce Website</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
```

styles.css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display:

