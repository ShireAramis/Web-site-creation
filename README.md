
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <!-- Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans&display=swap" rel="stylesheet">
    <!-- Styles -->
    <style>
        body {
            font-family: 'Open Sans', sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #3498db; /* Primary Color */
            color: white;
            padding: 20px;
        }
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }
        /* Add more styles as needed */
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <h1>My Website</h1>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="container">
        <!-- Home Page Content -->
        <h2>Home Page</h2>
        <p>Welcome to our website! Here you can find...</p>
    </div>

    <!-- About Page Content -->
    <div class="container">
        <h2>About Page</h2>
        <p>Learn more about us...</p>
    </div>

    <!-- Contact Page Content -->
    <div class="container">
        <h2>Contact Page</h2>
        <p>Get in touch with us...</p>
    </div>

    <footer>
        <div class="container">
            <p>&copy; 2024 My Website. All rights reserved.</p>
            <ul>
                <li><a href="#">Privacy Policy</a></li>
                <li><a href="#">Terms of Service</a></li>
            </ul>
        </div>
    </footer>
</body>
</html>
