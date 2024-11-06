<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loves - Ответы ОГЭ</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0078d7;
            background-image: radial-gradient(circle at 50% 50%, rgba(255, 255, 255, 0.3), transparent),
                              radial-gradient(circle at 30% 30%, rgba(255, 192, 203, 0.2), transparent),
                              radial-gradient(circle at 70% 70%, rgba(255, 105, 180, 0.2), transparent);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
        }
        .container {
            background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 100%);
            border-radius: 20px;
            padding: 25px;
            text-align: center;
            width: 320px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
            position: relative;
            animation: fadeIn 1s ease;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: scale(0.95); }
            to { opacity: 1; transform: scale(1); }
        }
        .avatar-container {
            position: relative;
            display: inline-block;
        }
        .avatar {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border: 3px solid #fff;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            z-index: 1;
        }
        .glow-ring {
            position: absolute;
            top: -12px;
            left: -12px;
            width: 124px;
            height: 124px;
            border-radius: 50%;
            background: radial-gradient(circle, rgba(255, 255, 255, 0.5), rgba(0, 120, 215, 0));
            animation: pulse 2s infinite alternate;
            z-index: 0;
        }
        @keyframes pulse {
            from { transform: scale(1); opacity: 0.7; }
            to { transform: scale(1.1); opacity: 1; }
        }
        .title {
            font-size: 28px;
            font-weight: bold;
            color: #fff;
            margin: 15px 0;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 8px;
            text-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
        }
        .heart {
            color: #ff4081;
            font-size: 28px;
        }
        .year {
            font-size: 20px;
            color: #fff;
            margin-bottom: 20px;
            text-shadow: 0 1px 3px rgba(0, 0, 0, 0.2);
        }
        .button {
            background: linear-gradient(90deg, #ff4081, #ff8e53);
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            display: inline-block;
            transition: box-shadow 0.3s ease, transform 0.3s ease;
            box-shadow: 0 4px 10px rgba(255, 64, 129, 0.5);
        }
        .button:hover {
            box-shadow: 0 0 15px rgba(255, 64, 129, 0.7), 0 0 25px rgba(255, 142, 83, 0.7);
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
