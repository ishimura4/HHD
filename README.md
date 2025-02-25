<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Магазин смартфонов</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .product {
            background: #fff;
            padding: 15px;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .product img {
            max-width: 100%;
            border-radius: 10px;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            background: #28a745;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Магазин смартфонов</h1>
    </header>
    <div class="container">
        <div class="products">
            <div class="product">
                <img src="phone1.jpg" alt="Смартфон 1">
                <h2>Смартфон 1</h2>
                <p>Описание смартфона 1</p>
                <a href="#" class="button">Купить</a>
            </div>
            <div class="product">
                <img src="phone2.jpg" alt="Смартфон 2">
                <h2>Смартфон 2</h2>
                <p>Описание смартфона 2</p>
                <a href="#" class="button">Купить</a>
            </div>
        </div>
    </div>
</body>
</html>
