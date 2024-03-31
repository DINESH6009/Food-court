<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Food Court</title>
    <style>
        /* Add your CSS styles here */
        body {
            font-family: 'Times New Roman', Times, serif, sans-serif;
        }
        header {
            background-color: violet;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        .menu-item {
            border: 1px solid red;
            padding: 10px;
            margin: 10px 0;
            display: flex;
            justify-content: space-between;
        }
        .menu-item button {
            background-color: red;
            color: #fff;
            border: none;
            padding: 5px 10px;
            cursor: pointer;
        }
        .cart {
            border: 1px solid blue;
            padding: 20px;
        }
        .cart h2 {
            text-align: center;
        }
        .cart-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
        }
        .cart-item button {
            background-color: red;
            color: #fff;
            border: none;
            padding: 5px 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>online food court</h1>
    </header>
    <div class="container">
        <h2>Menu</h2>
        <div class="menu-item">
            <span>Springroll</span>
            <span>$5.99</span>
            <button>Add to Cart</button>
        </div>
        <div class="menu-item">
            <span>Butter Chicken</span>
            <span>$8.99</span>
            <button>Add to Cart</button>
        </div>
        <div class="menu-item">
            <span>Barbecue</span>
            <span>$10.99</span>
            <button>Add to Cart</button>
        </div>
            <div class="menu-item">
                <span>Tandoori</span>
                <span>$11.99</span>
                <button>Add to Cart</button>
            </div>
            <div class="menu-item">
                <span>Chicken Manchurin</span>
                <span>$12.99</span>
                <button>Add to Cart</button>
            </div>
            <div class="menu-item">
                <span>Rotti</span>
                <span>$6.99</span>
                <button>Add to Cart</button>
            </div>
        <!-- Add more menu items here -->
        <h2>combo offer</h2>
        <div class="menu-item">
            <span>Panner butter masala - 2Pepsi</span>
            <span>$15.99</span>
            <button>Add to Cart</button>
        </div>

        <h2>Cart</h2>
        <div class="cart">
            <h2>Your Cart</h2>
            <div class="cart-item">
                <span>Springroll</span>
                <span>$5.99</span>
                <button>Remove</button>
            </div>
            <div class="cart-item">
                <span>Tandoori</span>
                <span>$11.99</span>
                <button>Remove</button>
            </div>
            <div class="cart-item">
                <span>Chicken Manchurin</span>
                <span>$12.99</span>
                <button>Remove</div>
            <div class="cart-item">
                <span>Rotti</span>
                <span>$6.99</span>
                <button>Remove</button>
            </div></button>
            </div>
            <!-- Add more cart items here -->
            <div>
                <strong>Total:</strong> $27.96 <!-- Calculate and display the total cost -->
            </div>
        </div>
    </div>
</body>
</html>
