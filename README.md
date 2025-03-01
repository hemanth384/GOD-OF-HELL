# GOD-OF-HELL
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>
    <style>
    /* Global Styles */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 0;
}

/* Header */
header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px 0;
}

/* Navigation */
nav ul {
    list-style-type: none;
    padding: 0;
    text-align: center;
    background-color: #444;
    margin: 0;
}

nav ul li {
    display: inline;
    margin: 0 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

nav ul li a:hover {
    text-decoration: underline;
}

/* Main Content */
main {
    padding: 20px;
    text-align: center;
}

section {
    margin-bottom: 40px;
}

footer {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
</style>
<link rel="stylesheet" href="style.css">

</head>
<body>
    <header>
        <h1>Welcome to My Website!</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#7075996791">Contact</a></li>
            <li><a href="D:\python\download (1).jpg">Preview</a></li>
        </ul>
    </nav>

    <main>
        <section id="home">
            <h2>Home Section</h2>
            <p>This is the home page content.</p>
        </section>

        <section id="about">
            <h2>About Section</h2>
            <p>Here you can learn more about the website.</p>
        </section>

        <section id="contact">
            <h2>Contact Section</h2>
            <p>Contact us at info@example.com</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 My First Website</p>
    </footer>
    <button id="clickButton">Click Me!</button>
<p id="message"></p>

<script>
    document.getElementById('clickButton').addEventListener('click', function() {
        document.getElementById('message').textContent = 'You clicked the button!';
    });
</script>

</body>
</html>
