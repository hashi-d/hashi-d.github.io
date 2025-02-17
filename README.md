<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1em;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        main {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Webpage</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
    <main>
        <h2 id="home">Home</h2>
        <p>This is the home section of the webpage.</p>

        <h2 id="about">About</h2>
        <p>This is the about section of the webpage.</p>

        <h2 id="services">Services</h2>
        <p>This is the services section of the webpage.</p>

        <h2 id="contact">Contact</h2>
        <p>This is the contact section of the webpage.</p>
    </main>
    <footer>
        <p>&copy; 2025 My Webpage. All rights reserved.</p>
    </footer>
    <script>
        // Add any JavaScript functionality here
    </script>
</body>
</html>
