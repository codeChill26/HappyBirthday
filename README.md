# HappyBirthday
Róp rẻn làm
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chúc Mừng Sinh Nhật</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background: linear-gradient(to bottom, #ffe259, #ffa751);
            color: #333;
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }

        h1 {
            font-size: 3rem;
            margin: 0;
            animation: glow 1.5s infinite;
        }

        @keyframes glow {
            0% { text-shadow: 0 0 5px #ff9, 0 0 10px #ff9, 0 0 15px #ff9; }
            50% { text-shadow: 0 0 10px #ff0, 0 0 20px #ff0, 0 0 30px #ff0; }
            100% { text-shadow: 0 0 5px #ff9, 0 0 10px #ff9, 0 0 15px #ff9; }
        }

        .cake {
            width: 200px;
            height: 200px;
            background: #fff;
            border-radius: 10px;
            position: relative;
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.2);
            margin: 20px 0;
        }

        .cake::before {
            content: '';
            width: 60px;
            height: 80px;
            background: #ff6f61;
            position: absolute;
            top: -60px;
            left: 70px;
            border-radius: 30px;
            box-shadow: 0 3px 5px rgba(0, 0, 0, 0.2);
        }

        .cake::after {
            content: '';
            width: 20px;
            height: 20px;
            background: yellow;
            position: absolute;
            top: -75px;
            left: 90px;
            border-radius: 50%;
            animation: flicker 0.5s infinite alternate;
        }

        @keyframes flicker {
            0% { background: orange; }
            100% { background: yellow; }
        }

        p {
            font-size: 1.2rem;
            margin: 0;
        }

        button {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 1rem;
            color: white;
            background-color: #ff6f61;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
        }

        button:hover {
            background-color: #ff5733;
        }
    </style>
</head>
<body>
    <h1>🎉 Chúc Mừng Sinh Nhật! 🎉</h1>
    <div class="cake"></div>
    <p>Chúc bạn có một ngày sinh nhật thật tuyệt vời và hạnh phúc!</p>
    <button onclick="alert('Hãy luôn vui vẻ và tràn đầy năng lượng nhé! 🥳')">Nhấn để nhận lời chúc</button>
</body>
</html>
