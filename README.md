<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timur Karabalaev - Bitcoin Account</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #1a1a1d;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            text-align: center;
            background-color: #2c2f33;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            width: 400px;
            transition: transform 0.3s ease;
        }
        .container:hover {
            transform: translateY(-10px);
        }
        h1 {
            color: #ffffff;
            font-size: 28px;
            margin-bottom: 20px;
            font-weight: 600;
        }
        p {
            font-size: 18px;
            color: #dcdde1;
            margin-bottom: 10px;
        }
        .btc-amount {
            font-size: 36px;
            color: #fbc531;
            font-weight: bold;
            margin-bottom: 20px;
        }
        .btc-logo {
            width: 80px;
            margin-bottom: 20px;
        }
        .balance-label {
            font-size: 16px;
            color: #888;
        }
        .cta-button {
            background-color: #fbc531;
            border: none;
            padding: 12px 24px;
            border-radius: 8px;
            font-size: 16px;
            font-weight: 600;
            color: #1a1a1d;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .cta-button:hover {
            background-color: #e1a01f;
        }
    </style>
</head>
<body>
    <div class="container">
        <img class="btc-logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/46/Bitcoin.svg/1200px-Bitcoin.svg.png" alt="Bitcoin Logo">
        <h1>Bitcoin Account - Timur Karabalaev</h1>
        <p class="balance-label">Your current balance is:</p>
        <p class="btc-amount">3.03649 BTC</p>
        <button class="cta-button">View Transactions</button>
    </div>
</body>
</html>
