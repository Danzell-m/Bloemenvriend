<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="BloemenVriend - Altijd verse bloemen uit de bloemenautomaat">
    <title>BloemenVriend - Bloemenautomaat</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f7f7f7;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #f1c6d1;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            text-align: center;
            background-color: #f9d5d3;
            padding: 10px;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
            font-size: 1.2em;
        }
        .banner {
            background-image: url('https://via.placeholder.com/1600x600?text=BloemenAutomaat');
            background-size: cover;
            background-position: center;
            padding: 100px 0;
            text-align: center;
            color: white;
        }
        .banner h2 {
            font-size: 3em;
            margin: 0;
        }
        section {
            padding: 50px 20px;
            text-align: center;
        }
        section h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }
        .flower-list img {
            width: 200px;
            margin: 10px;
        }
        footer {
            background-color: #f1c6d1;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>BloemenVriend</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#over">Over Ons</a>
            <a href="#bloemen">Bloemen</a>
            <a href="#locaties">Locaties</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Banner -->
    <div class="banner">
        <h2>Altijd verse bloemen, direct uit de automaat!</h2>
        <p>Geen tijd om naar de bloemist te gaan? Wij brengen bloemen naar jou!</p>
    </div>

    <!-- Home -->
    <section id="home">
        <h2>Welkom bij BloemenVriend!</h2>
        <p>Onze bloemenautomaten bieden een breed scala aan verse bloemen. Geen gedoe, geen wachttijden, gewoon bloemen wanneer je ze nodig hebt.</p>
    </section>

    <!-- Over Ons -->
    <section id="over">
        <h2>Wie zijn wij?</h2>
        <p>BloemenVriend is een innovatief bedrijf dat bloemenautomaten plaatst op strategische locaties. Wij maken het eenvoudig voor iedereen om op elk moment van de dag bloemen te kopen.</p>
    </section>

    <!-- Bloemen -->
    <section id="bloemen">
        <h2>Onze Bloemen</h2>
        <p>Wij bieden een verscheidenheid aan bloemen, van rozen tot tulpen. Bekijk onze actuele collectie hieronder!</p>
        <div class="flower-list">
            <img src="https://via.placeholder.com/200x200?text=Rozen" alt="Rozen">
            <img src="https://via.placeholder.com/200x200?text=Tulpen" alt="Tulpen">
            <img src="https://via.placeholder.com/200x200?text=Orchideeën" alt="Orchideeën">
        </div>
    </section>

    <!-- Locaties -->
    <section id="locaties">
        <h2>Waar vind je ons?</h2>
        <p>Onze bloemenautomaten zijn te vinden op verschillende locaties in de stad. Zoek naar een automaat bij jou in de buurt!</p>
        <div>
            <p>Locatie 1: Centraal Station</p>
            <p>Locatie 2: Parkplein</p>
            <p>Locatie 3: Winkelcentrum</p>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact">
        <h2>Neem contact met ons op</h2>
        <p>Heb je vragen? Stuur ons een bericht!</p>
        <form>
            <label for="naam">Naam:</label><br>
            <input type="text" id="naam" name="naam" required><br><br>
            <label for="email">E-mail:</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label for="bericht">Bericht:</label><br>
            <textarea id="bericht" name="bericht" rows="4" cols="50" required></textarea><br><br>
            <input type="submit" value="Verstuur">
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>Volg ons op social media!</p>
        <p>&copy; 2025 BloemenVriend. Alle rechten voorbehouden.</p>
    </footer>
</body>
</html>

