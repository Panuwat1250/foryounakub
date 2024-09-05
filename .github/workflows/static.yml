<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>คุณชอบหมาหรือแมว?</title>
    <link href="https://fonts.googleapis.com/css2?family=Prompt:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Prompt', sans-serif;
            background-color: #f0e6f6;
            color: #333;
            text-align: center;
            padding: 20px;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .button {
            display: inline-block;
            margin: 10px;
            padding: 10px 20px;
            font-size: 16px;
            color: #fff;
            background-color: #ff69b4;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
            transition: background-color 0.3s ease;
        }
        .button:hover {
            background-color: #ff1493;
        }
        #answer, #gif {
            display: none;
            margin-top: 20px;
            font-size: 18px;
            opacity: 0;
            transition: opacity 1s ease-in-out;
        }
        #gif {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        @media (max-width: 600px) {
            .container {
                padding: 10px;
            }
            .button {
                font-size: 14px;
                padding: 8px 16px;
            }
            #answer {
                font-size: 16px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>คุณชอบหมาหรือแมว?</h1>
        <a href="#" class="button" onclick="showAnswer()">หมา</a>
        <a href="#" class="button" onclick="showAnswer()">แมว</a>
        <p id="answer">เราชอบแก</p>
        <img id="gif" src="https://drive.google.com/uc?export=view&id=12k8Ui_RBS_e-bJOaaG-OqiNdLWV1Z0MS" alt="ยื่นดอกไม้">
    </div>

    <script>
        function showAnswer() {
            document.getElementById('answer').style.display = 'block';
            document.getElementById('gif').style.display = 'block';
            setTimeout(function() {
                document.getElementById('answer').style.opacity = 1;
                document.getElementById('gif').style.opacity = 1;
            }, 10);
        }
    </script>
</body>
</html>
