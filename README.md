# British-Master
Language school
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>British Master - Szkoła Językowa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }
        header {
            background: url('https://upload.wikimedia.org/wikipedia/commons/a/ae/Union_flag_1606_%28Kings_Colors%29.svg') no-repeat center/cover;
            color: white;
            text-align: center;
            padding: 50px 20px;
            position: relative;
        }
        header img {
            width: 120px;
            position: absolute;
            top: 10px;
            left: 10px;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #002147;
            padding: 15px;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 20px;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #ffcc00;
        }
        .container {
            max-width: 900px;
            margin: auto;
            padding: 20px;
            animation: fadeIn 1s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .section {
            background: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        .section:hover {
            transform: scale(1.02);
        }
        .image-container {
            text-align: center;
            margin: 20px 0;
        }
        .image-container img {
            width: 100%;
            max-width: 600px;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            background: #002147;
            color: white;
            padding: 15px;
            margin-top: 20px;
            font-size: 14px;
        }
        a {
            color: #002147;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <img src="/mnt/data/ENGLISH.jpg" alt="British Master Logo">
        <h1>British Master - Szkoła Językowa</h1>
        <p>Profesjonalne lekcje języka angielskiego online i w Łodzi</p>
    </header>
    <nav>
        <a href="#o-mnie">O mnie</a>
        <a href="#oferta">Oferta</a>
        <a href="#koszta">Koszta</a>
        <a href="#kontakt">Kontakt</a>
    </nav>
    <div class="container">
        <div id="o-mnie" class="section">
            <h2>O mnie</h2>
            <p>Nazywam się <strong>Maciej Dybała</strong> i od lat pomagam uczniom w nauce języka angielskiego. Nauczanie to moja pasja – uwielbiam wspierać innych w przełamywaniu barier językowych i osiąganiu sukcesów.</p>
            <p>Jeśli Twoje dziecko zmaga się z angielskim, dobrze trafiłeś! Moje metody dostosowuję do indywidualnych potrzeb ucznia, aby nauka była skuteczna i przyjemna.</p>
        </div>
        <div class="image-container">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d8/Big_Ben%2C_London%2C_England_3_-_June_2009.jpg/800px-Big_Ben%2C_London%2C_England_3_-_June_2009.jpg" alt="Big Ben">
        </div>
        <div id="oferta" class="section">
            <h2>Oferta</h2>
            <ul>
                <li>Korepetycje dla uczniów klas 4-8</li>
                <li>Przygotowanie do egzaminu ósmoklasisty</li>
                <li>Przygotowanie do matury podstawowej i rozszerzonej</li>
                <li>Zajęcia online i stacjonarne w Łodzi</li>
            </ul>
        </div>
        <div id="koszta" class="section">
            <h2>Koszta</h2>
            <p>Cennik ustalany indywidualnie – skontaktuj się, aby dowiedzieć się więcej!</p>
        </div>
        <div id="kontakt" class="section">
            <h2>Kontakt</h2>
            <p>Email: <a href="mailto:british.master.lodz@gmail.com">british.master.lodz@gmail.com</a></p>
            <p>Telefon: <a href="tel:+48888199195">+48 888-199-195</a></p>
        </div>
    </div>
    <footer>
        <p>&copy; 2025 British Master - Wszelkie prawa zastrzeżone.</p>
    </footer>
</body>
</html>
