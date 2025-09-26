<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YoungStylez</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <div class="logo">YoungStylez</div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Trends</a></li>
                <li><a href="#">Shop</a></li>
                <li><a href="#">Kontakt</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Luxury Streetstyle für die Next Generation</h1>
        <p>Wo Eleganz auf Jugendkultur trifft.</p>
        <a href="#" class="cta-button">Jetzt entdecken</a>
    </section>

    <footer>
        <p>&copy; 2025 YoungStylez. Alle Rechte vorbehalten.</p>
    </footer>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Montserrat', sans-serif;
    background-color: #111;
    color: #fff;
    line-height: 1.6;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 50px;
    background-color: #000;
    border-bottom: 2px solid gold;
}

.logo {
    font-size: 28px;
    font-weight: bold;
    color: gold;
    letter-spacing: 1px;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: gold;
}

.hero {
    height: 90vh;
    background: url('https://images.unsplash.com/photo-1618354691210-76a91b2d48a2') no-repeat center center/cover;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 0 20px;
}

.hero h1 {
    font-size: 3em;
    margin-bottom: 20px;
    color: #fff;
    text-shadow: 2px 2px 5px #000;
}

.hero p {
    font-size: 1.2em;
    margin-bottom: 30px;
    color: #ddd;
}

.cta-button {
    padding: 15px 30px;
    background-color: gold;
    color: #000;
    text-decoration: none;
    font-weight: bold;
    border-radius: 30px;
    transition: background 0.3s;
}

.cta-button:hover {
    background-color: #e6c200;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #000;
    border-top: 1px solid gold;
    font-size: 0.9em;
    color: #aaa;
}
