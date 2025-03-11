# index.htmt
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>San Joaquin Valley Town Hall</title>
    <!-- Link to the external CSS file -->
    <link rel="stylesheet" href="styles/main.css">
</head>
<body>
    <!-- Logo Section -->
    <header>
        <img src="images/logo.png" alt="San Joaquin Valley Town Hall Logo" id="logo">
    </header>

    <!-- Main Content Section -->
    <h1>Welcome to San Joaquin Valley Town Hall</h1>
    <p>This is the main page for the event.</p>

    <!-- Speaker Images with Links -->
    <section>
        <h2>Speakers</h2>
        <a href="underconstruction.html">
            <img src="images/speaker1.jpg" alt="Speaker 1">
        </a>
        <a href="underconstruction.html">
            <img src="images/speaker2.jpg" alt="Speaker 2">
        </a>
        <a href="underconstruction.html">
            <img src="images/speaker3.jpg" alt="Speaker 3">
        </a>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; Copyright Your Name, 2025</p>
    </footer>
</body>
</html>
/* main.css */

/* Basic Styling */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    margin: 0;
    padding: 0;
}

h1, h2 {
    color: #005a87; /* Town Hall brand color */
}

header {
    background-color: #fff;
    padding: 20px;
    text-align: center;
}

#logo {
    max-width: 200px;
}

/* Styling the Speaker Images */
section img {
    width: 200px;
    margin: 10px;
    border: 3px solid #ddd;
    border-radius: 8px;
}

section a:hover img {
    opacity: 0.7; /* Hover effect */
}

/* Footer Styling */
footer {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 10px;
    position: absolute;
    width: 100%;
    bottom: 0;
}
