<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UI Layout</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
        }
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px;
            background-color: #111;
            border-bottom: 2px solid #333;
        }
        .header .menu, .header .icons {
            display: flex;
            align-items: center;
        }
        .header .menu img,
        .header .icons img {
            width: 25px;
            height: 25px;
            margin-right: 10px;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            padding: 20px;
        }
        .grid-item {
            text-align: center;
        }
        .grid-item img {
            width: 80px;
            height: 80px;
            margin-bottom: 10px;
        }
        .footer {
            display: flex;
            justify-content: space-around;
            padding: 10px;
            background-color: #111;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .footer img {
            width: 25px;
            height: 25px;
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="menu">
            <img src="star-icon.png" alt="Star Icon">
            <span>HQ</span>
        </div>
        <div class="icons">
            <img src="search-icon.png" alt="Search">
            <img src="notification-icon.png" alt="Notification">
            <img src="user-icon.png" alt="User">
        </div>
    </div>
    <div class="grid">
        <div class="grid-item">
            <img src="pak-icon.png" alt="Pak e-Services">
            <p>Pak e-Services</p>
        </div>
        <div class="grid-item">
            <img src="tv-icon.png" alt="Live TV">
            <p>Live TV</p>
        </div>
        <div class="grid-item">
            <img src="chat-icon.png" alt="Chatting">
            <p>Chatting</p>
        </div>
        <div class="grid-item">
            <img src="user-icon.png" alt="Users">
            <p>Users</p>
        </div>
        <div class="grid-item">
            <img src="tips-icon.png" alt="Tips & Tricks">
            <p>Tips & Tricks</p>
        </div>
        <div class="grid-item">
            <img src="hacking-icon.png" alt="Hacking">
            <p>Hacking</p>
        </div>
        <div class="grid-item">
            <img src="tools-icon.png" alt="Online Tools">
            <p>Online Tools</p>
        </div>
        <div class="grid-item">
            <img src="courses-icon.png" alt="Free Courses">
            <p>Free Courses</p>
        </div>
        <div class="grid-item">
            <img src="assets-icon.png" alt="1TB Digital Assets">
            <p>1TB Digital Assets</p>
        </div>
        <div class="grid-item">
            <img src="social-icon.png" alt="Our Social Media">
            <p>Our Social Media</p>
        </div>
    </div>
    <div class="footer">
        <img src="world-icon.png" alt="World">
        <img src="whatsapp-icon.png" alt="WhatsApp">
        <img src="home-icon.png" alt="Home">
        <img src="chat-icon.png" alt="Chat">
        <img src="telegram-icon.png" alt="Telegram">
    </div>
</body>
</html>
