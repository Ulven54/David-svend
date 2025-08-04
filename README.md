<!DOCTYPE html>
<html lang="da">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Davidsvend - Håndlavede træhalskæder</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #1a1a1a;
            color: #f5f5f5;
        }
        header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 20px;
            background-color: #111;
            position: sticky;
            top: 0;
        }
        header img {
            height: 50px;
        }
        nav a {
            color: #f5f5f5;
            text-decoration: none;
            margin-left: 20px;
            font-weight: bold;
        }
        section {
            padding: 60px 20px;
            max-width: 1000px;
            margin: auto;
        }
        .hero {
            text-align: center;
            padding: 80px 20px;
        }
        .hero h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 1.2em;
            margin-bottom: 20px;
        }
        .hero a {
            background-color: #8B4513;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .gallery div {
            background: #333;
            height: 200px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #aaa;
        }
        footer {
            background: #111;
            text-align: center;
            padding: 20px;
            font-size: 0.9em;
        }
        footer a {
            color: #f5f5f5;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <img src="LOGO-URL-HER" alt="Davidsvend Logo">
        <nav>
            <a href="#shop">Shop</a>
            <a href="#about">Om mig</a>
            <a href="#contact">Kontakt</a>
        </nav>
    </header>

    <section class="hero">
        <h1>Davidsvend</h1>
        <p>Håndlavede halskæder i træ og læder</p>
        <a href="#shop">Se mine designs</a>
    </section>

    <section id="shop">
        <h2>Mine produkter</h2>
        <div class="gallery">
            <div>Produktbillede 1</div>
            <div>Produktbillede 2</div>
            <div>Produktbillede 3</div>
            <div>Produktbillede 4</div>
        </div>
    </section>

    <section id="about">
        <h2>Om mig</h2>
        <p>Hej, jeg er David, og jeg laver håndlavede halskæder af træ og læder. Hvert smykke er unikt og designet med kærlighed til naturen og de naturlige materialer. Jeg brænder for at skabe noget, der er enkelt, bæredygtigt og personligt.</p>
        <h3>English (short version)</h3>
        <p>Hello, I am David. I create handmade wooden necklaces with leather cord. Each piece is unique and inspired by nature and simple design.</p>
    </section>

    <section id="contact">
        <h2>Kontakt</h2>
        <p><strong>E-mail:</strong> <a href="mailto:david@vejbred.dk">david@vejbred.dk</a></p>
        <p><strong>SMS:</strong> 20856141 <br><em>(Venligst ingen opkald)</em></p>
        <p><strong>Instagram:</strong> <a href="https://instagram.com/DIT_INSTAGRAM" target="_blank">@DIT_INSTAGRAM</a></p>
    </section>

    <footer>
        <p>&copy; 2025 Davidsvend | Håndlavet med kærlighed | <em>Venligst ingen opkald</em></p>
    </footer>
</body>
</html>
