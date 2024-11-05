<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loves - Ответы ОГЭ</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0078d7;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            background-color: white;
            border-radius: 15px;
            padding: 20px;
            text-align: center;
            width: 300px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            position: relative;
        }
        .avatar {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 15px;
            position: relative;
            z-index: 1;
        }
        .avatar-container {
            display: inline-block;
            position: relative;
        }
        .glow-ring {
            position: absolute;
            top: -10px;
            left: -10px;
            width: 120px;
            height: 120px;
            border-radius: 50%;
            background: radial-gradient(circle, rgba(255, 255, 255, 0.3), rgba(0, 120, 215, 0));
            animation: glow 2s infinite alternate;
            z-index: 0;
        }
        @keyframes glow {
            from {
                transform: scale(1);
                opacity: 0.7;
            }
            to {
                transform: scale(1.2);
                opacity: 1;
            }
        }
        .title {
            font-size: 24px;
            font-weight: bold;
            color: #333;
            margin-bottom: 10px;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 8px;
        }
        .heart {
            color: #ff4081;
            font-size: 24px;
        }
        .year {
            font-size: 18px;
            color: #555;
            margin-bottom: 20px;
        }
        .button {
            background: linear-gradient(90deg, #ff4081, #ff8e53);
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            display: inline-block;
            transition: box-shadow 0.3s ease, transform 0.3s ease;
        }
        .button:hover {
            box-shadow: 0 0 10px rgba(255, 64, 129, 0.6), 0 0 20px rgba(255, 142, 83, 0.6);
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="avatar-container">
            <img src="loves_avatar.jpg" alt="Loves Avatar" class="avatar">
            <div class="glow-ring"></div>
        </div>
        <div class="title">Loves <span class="heart">❤</span></div>
        <div class="year">Ответы ОГЭ 2025</div>
        <a href="https://t.me/otveti_loves" class="button">Открыть в Telegram</a>
    </div>
</body>
</html>
