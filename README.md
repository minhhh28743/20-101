<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thiệp Chúc Mừng Ngày Phụ Nữ Việt Nam</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(135deg, #ff80ab, #ff4081);
            margin: 0;
            overflow: hidden;
        }
        .card {
            background-color: #ffffff;
            width: 400px;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.3);
            text-align: center;
            position: relative;
            overflow: hidden;
            animation: fadeIn 2s ease-in-out;
        }

        /* Hiệu ứng fade-in */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: scale(0.8);
            }
            to {
                opacity: 1;
                transform: scale(1);
            }
        }

        /* Hoa bay lượn */
        .flower {
            position: absolute;
            top: -50px;
            left: 50%;
            width: 100px;
            animation: floating 6s infinite ease-in-out;
            transform: translateX(-50%);
        }
        @keyframes floating {
            0% {
                transform: translateX(-50%) translateY(0);
            }
            50% {
                transform: translateX(-50%) translateY(-20px);
            }
            100% {
                transform: translateX(-50%) translateY(0);
            }
        }

        /* Hiệu ứng chữ lớn dần */
        .card h1 {
            color: #e91e63;
            font-size: 28px;
            margin-bottom: 20px;
            animation: zoomIn 1.5s ease-in-out;
        }
        @keyframes zoomIn {
            from {
                transform: scale(0.8);
                opacity: 0;
            }
            to {
                transform: scale(1);
                opacity: 1;
            }
        }

        /* Hiệu ứng cho đoạn văn */
        .card p {
            color: #333333;
            font-size: 18px;
            opacity: 0;
            animation: slideIn 2s forwards 1.5s;
        }
        @keyframes slideIn {
            from {
                transform: translateY(20px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        /* Hiệu ứng nút */
        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 25px;
            background-color: #e91e63;
            color: white;
            text-decoration: none;
            border-radius: 50px;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
            transition: background-color 0.3s, box-shadow 0.3s;
        }
        .btn:hover {
            background-color: #d81b60;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.4);
            transform: translateY(-3px);
        }

        /* Hiệu ứng hoa rơi */
        .falling-flower {
            position: absolute;
            width: 40px;
            opacity: 0.8;
            animation: fall 10s infinite linear;
        }
        .falling-flower:nth-child(odd) {
            animation-duration: 12s;
            opacity: 0.6;
        }
        @keyframes fall {
            0% {
                transform: translateY(-100px) rotate(0deg);
            }
            100% {
                transform: translateY(100vh) rotate(360deg);
            }
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>Chúc Mừng Ngày Phụ Nữ Việt Nam</h1>
        <img class="flower" src="https://i.imgur.com/5jM5P2x.png" alt="Hoa" />
        <p>Chúc em một ngày 20/10 thật vui vẻ, hạnh phúc và tràn đầy yêu thương!</p>
      
    </div>
</body>
<title>Chúc Mừng Ngày Phụ Nữ Việt Nam</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #fce4ec;
            margin: 0;
        }
        .container {
            text-align: center;
        }
        .btn {
            padding: 10px 20px;
            background-color: #e91e63;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s ease;
        }
        .btn:hover {
            background-color: #d81b60;
        }
        .message {
            margin-top: 20px;
            font-size: 18px;
            color: #000000;
            opacity: 0; /* Lời chúc bị ẩn ban đầu */
            transition: opacity 0.5s ease; /* Hiệu ứng mờ dần khi hiển thị */
        }
        .message.show {
            opacity: 1; /* Lời chúc hiện ra khi lớp 'show' được thêm */
        }
    </style>
</head>
<body>
    <div class="container">
        <button class="btn" onclick="showMessage()">Bấm vào đi hihi</button>
        <div class="message" id="message">Anh yêu em nhiều lắm.Mong rằng em luôn vui vẻ, xinh đẹp và ở bên anh mãi mãi.</div>
    </div>

    <script>
        function showMessage() {
            var messageElement = document.getElementById("message");
            messageElement.classList.add("show"); // Thêm lớp 'show' để hiện lời chúc
        }
    </script>
</html>
ntitled-12.html…]()
