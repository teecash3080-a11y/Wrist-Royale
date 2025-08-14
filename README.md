<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wrist Royale | Watches & Jewelry</title>
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            background-color: #fff;
            color: #333;
        }
        header {
            background-color: #111;
            color: white;
            text-align: center;
            padding: 20px;
        }
        header h1 {
            margin: 0;
            font-size: 28px;
            letter-spacing: 2px;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .product {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            background: #fff;
            text-align: center;
            box-shadow: 0 2px 6px rgba(0,0,0,0.05);
        }
        .product img {
            width: 100%;
            height: auto;
        }
        .product h3 {
            margin: 10px 0 5px;
        }
        .product p {
            margin: 0 0 10px;
            font-size: 14px;
            color: #555;
        }
        .price {
            font-size: 16px;
            font-weight: bold;
            color: #111;
        }
        .order-btn {
            display: block;
            padding: 10px;
            background-color: #111;
            color: white;
            text-decoration: none;
            border-radius: 0 0 8px 8px;
        }
        footer {
            background-color: #111;
            color: white;
            text-align: center;
            padding: 15px;
            font-size: 14px;
        }
    </style>
</head>
<body>

<header>
    <h1>Wrist Royale</h1>
    <p>Luxury Watches & Jewelry</p>
</header>

<section class="products">
    <div class="product">
        <img src="watch1.jpg" alt="Gold Classic Watch">
        <h3>Gold Classic Watch</h3>
        <p class="price">₦45,000</p>
        <a href="https://wa.me/234XXXXXXXXXX" class="order-btn">Order on WhatsApp</a>
    </div>

    <div class="product">
        <img src="watch2.jpg" alt="Silver Luxury Watch">
        <h3>Silver Luxury Watch</h3>
        <p class="price">₦50,000</p>
        <a href="https://wa.me/234XXXXXXXXXX" class="order-btn">Order on WhatsApp</a>
    </div>

    <div class="product">
        <img src="jewelry1.jpg" alt="Diamond Bracelet">
        <h3>Diamond Bracelet</h3>
        <p class="price">₦35,000</p>
        <a href="https://wa.me/234XXXXXXXXXX" class="order-btn">Order on WhatsApp</a>
    </div>
</section>

<footer>
    &copy; 2025 Wrist Royale | Follow us on Instagram: @wristroyale
</footer>

</body>
</html>
