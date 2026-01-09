# Product-Card
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Card</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            height: 100vh;
            background: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRQbaGrPaHa1mNPScJy9fheAjv_OHBmYt-BUw&s") no-repeat center center/cover;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        
        .card {
            background: rgba(255, 255, 255, 0.95);
            width: 300px;
            border-radius: 10px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
            overflow: hidden;
            text-align: center;
        }

        .card img {
            width: 100%;
            height: auto;
        }

        .card-content {
            padding: 15px;
        }

        .card-content h2 {
            margin-bottom: 10px;
            color: #333;
        }

        .card-content p {
            font-size: 14px;
            color: #555;
            margin-bottom: 12px;
        }

        .price {
            font-size: 18px;
            font-weight: bold;
            color: #2c3e50;
            margin-bottom: 15px;
        }

        .btn {
            width: 100%;
            padding: 10px;
            background: #869efa;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            transition: background 0.3s;
        }

        .btn:hover {
            background: #6b84e6;
        }
    </style>
</head>
<body>

    <div class="card">
        <img src="https://www.iclarified.com/images/news/94911/94911/94911-1280.jpg" alt="iPhone">

        <div class="card-content">
            <h2>iPhone 15 Pro</h2>
            <p>Experience next-level performance with our latest iPhone, designed for speed, style, and security.</p>
            <div class="price">₹1,29,999</div>
            <button class="btn">Buy Now</button>
        </div>
    </div>

</body>
</html>
