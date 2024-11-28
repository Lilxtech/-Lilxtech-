<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lilxtech Toolkit </title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #4B2A1A;
            color: white;
            text-align: center;
        }

        .header {
            background-color: #F9A825;
            padding: 20px;
        }

        .header h1 {
            margin: 0;
        }

        .grid-container {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }

        .grid-item {
            background-color: #2C2F33;
            border: 2px solid #F9A825;
            border-radius: 10px;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            cursor: pointer;
            transition: transform 0.2s ease-in-out;
        }

        .grid-item:hover {
            transform: scale(1.05);
        }

        .grid-item img {
            width: 80px;
            height: 80px;
            margin-bottom: 10px;
        }

        .grid-item p {
            margin: 0;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Master Top Hacking Techniques</h1>
    </div>
    <div class="grid-container">
        <a href="cryptography.html" class="grid-item">
            <img src="https://via.placeholder.com/80" alt="Cryptography">
            <p>Cryptography</p>
        </a>
        <a href="vapt.html" class="grid-item">
            <img src="https://via.placeholder.com/80" alt="VAPT">
            <p>VAPT</p>
        </a>
        <a href="mobile_hacking.html" class="grid-item">
            <img src="https://via.placeholder.com/80" alt="Mobile Hacking">
            <p>Mobile Hacking</p>
        </a>
        <a href="website_hacking.html" class="grid-item">
            <img src="https://via.placeholder.com/80" alt="Website Hacking">
            <p>Website Hacking</p>
        </a>
    </div>
</body>
</html>
