<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        /* Ensure all styles are reset */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        /* Body and background setup */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-image: url('background.jpg'); /* Background image */
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-position: center;
            background-size: cover;
            color: white;
            font-weight: bold;
        }

        /* Header style */
        header {
            background-color: #b6f1ff !important; /* Header background color */
            color: white;
            padding: 15px 0;
            display: flex;
            align-items: center; /* Align items vertically */
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 10;
        }

        /* Container for logo and nav button */
        .header-container {
            display: flex;
            align-items: center; /* Align logo and text vertically */
            margin-left: 20px; /* Add some margin to the left side of the header */
        }

        /* Round logo styles */
        .logo {
            width: 50px; /* Set the width of the logo */
            height: 50px; /* Set the height of the logo */
            border-radius: 50%; /* Makes the logo round */
            object-fit: cover; /* Ensures the image fills the circle properly without distortion */
            margin-right: 15px; /* Adds space between the logo and the text */
        }

        /* Text next to the logo */
        .logo-text {
            font-size: 24px; /* Set the size of the text */
            font-weight: bold; /* Make the text bold */
            color: #fff; /* Text color white */
            margin-right: 10px; /* Reduced space between the text and the nav button */
        }

        .nav-button {
            background-color: #8ce5fa;
            color: white;
            font-size: 18px;
            padding: 10px 15px; /* Reduced padding to make the button smaller */
            border-radius: 15px;
            text-decoration: none;
            font-weight: bold;
            transition: background-color 0.3s ease;
            margin-right: 10px; /* Add space between buttons */
        }

        .nav-button:hover {
            background-color: #84a8b0;
        }

        /* Content styles */
        .content {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            height: 100vh;
            margin-top: 80px; /* Adjusted for fixed header */
            text-align: center;
            z-index: 10;
        }

        .button {
            display: inline-block;
            background-color: #7289da;
            color: white;
            font-size: 18px;
            padding: 15px 30px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }

        .button:hover {
            background-color: #84a8b0;
        }

        p {
            font-family: Arial, sans-serif;
            font-weight: bold;
            font-size: 18px;
            margin-top: 20px;
        }

        /* Info box style */
        .info-box {
            background-color: rgba(255, 255, 255, 0.2); /* Light transparency */
            padding: 15px;
            border-radius: 10px;
            margin-top: 30px;
            max-width: 600px;
            text-align: center;
            line-height: 1.5;
        }
    </style>
</head>
<body>

    <!-- Header with logo, text, and nav buttons -->
    <header>
        <div class="header-container">
            <!-- Add your logo here -->
            <img src="LOGO.jpg" alt="Logo" class="logo"> <!-- Replace 'LOGO.jpg' with your actual logo file path -->
            <!-- Text next to the logo -->
            <span class="logo-text">Bea's Bee's</span>
            <!-- Updated href to point to Rules.html -->
            <a href="home.html" class="nav-button">Home</a>
            <!-- New About button -->
            <a href="rules.html" class="nav-button">Rules</a> <!-- New button next to Rules -->
        </div>
    </header>

    <!-- Main content -->
    <div class="content">
        <p>Join the Discord</p>
        <a href="https://discord.gg/2kQybjShPU" class="button">Join Now</a>

        <div class="info-box">
            <p>Bea’s Bees is a server dedicated to the British singer-songwriter, Beabadoobee. Come join us to play our daily games, catch up on the latest news, and talk to other fans!</p>
        </div>
    </div>

</body>
</html>

