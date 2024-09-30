<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bitcoin Account - Карабалаев Тимур</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background: url('https://i.imgur.com/jcnErTS.jpg') no-repeat center center fixed;
            background-size: cover;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: #fff;
        }

        .container {
            text-align: center;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 15px;
            padding: 30px;
            width: 400px;
            box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.18);
        }

        h1 {
            font-size: 24px;
            margin-bottom: 10px;
        }

        .btc-logo {
            font-size: 50px;
            color: #f2a900;
            margin-bottom: 20px;
        }

        .btc-amount {
            font-size: 36px;
            font-weight: 600;
            margin-bottom: 10px;
        }

        .btc-usd {
            font-size: 18px;
            color: #ccc;
            margin-bottom: 30px;
        }

        .btn {
            background-color: #f2a900;
            color: #000;
            padding: 10px 20px;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }

        .btn:hover {
            background-color: #d18c00;
        }

        .transaction-history {
            margin-top: 30px;
        }

        .transaction-history h2 {
            font-size: 20px;
            margin-bottom: 10px;
        }

        .transaction {
            background: rgba(255, 255, 255, 0.1);
            padding: 15px;
            border-radius: 10px;
            margin-bottom: 15px;
            text-align: left;
        }

        .transaction .details {
            font-size: 16px;
            color: #ddd;
        }

        .transaction .time {
            font-size: 14px;
            color: #aaa;
        }
    </style>
</head>
<body>

    <div class="container">
        <i class="fab fa-bitcoin btc-logo"></i>
        <h1>Биткоин-счет Тимура</h1>
        <div class="btc-amount">3.03649 BTC</div>
        <div class="btc-usd">~ $82,000 USD</div>
        <button class="btn">Перевести средства</button>

        <!-- Раздел транзакций -->
        <div class="transaction-history">
            <h2>История транзакций</h2>

            <!-- Транзакция покупки -->
            <div class="transaction">
                <div class="details">
                    Куплено 3.03649 BTC за $81,500
                </div>
                <div class="time">
                    Время: 21:35, 30 сентября 2024 года
                </div>
            </div>
        </div>
    </div>

</body>
</html>
