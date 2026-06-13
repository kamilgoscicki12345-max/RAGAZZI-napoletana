<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pizza Eventowa</title>

<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    color:#111;
}

nav{
    background:#111;
    padding:15px;
    position:sticky;
    top:0;
}

nav a{
    color:white;
    text-decoration:none;
    margin-right:20px;
}

.hero{
    height:70vh;
    display:flex;
    justify-content:center;
    align-items:center;
    flex-direction:column;
    background:#f5f5f5;
}

.button{
    background:#c62828;
    color:white;
    padding:12px 24px;
    text-decoration:none;
    border-radius:5px;
}

section{
    padding:60px 20px;
    max-width:1200px;
    margin:auto;
}

h2{
    color:#c62828;
}
</style>
</head>

<body>

<nav>
    <a href="#start">Start</a>
    <a href="#oferta">Oferta</a>
    <a href="#galeria">Galeria</a>
    <a href="#omnie">O mnie</a>
    <a href="#kontakt">Kontakt</a>
</nav>

<section id="start" class="hero">
    <h1>Pizza Neapolitańska na Twój Event</h1>
    <p>Wesela • Urodziny • Eventy Firmowe</p>
    <a class="button" href="#kontakt">Zapytaj o termin</a>
</section>

<section id="oferta">
    <h2>Oferta</h2>
    <p>
        Obsługa wesel, poprawin, eventów firmowych,
        imprez prywatnych i plenerowych.
    </p>
</section>

<section id="galeria">
    <h2>Galeria</h2>
    <p>Tutaj później dodamy zdjęcia.</p>
</section>

<section id="omnie">
    <h2>O mnie</h2>
    <p>
        Kilka zdań o Tobie i Twojej pasji do pizzy.
    </p>
</section>

<section id="kontakt">
    <h2>Kontakt</h2>
    <p>Telefon: XXX XXX XXX</p>
    <p>Email: kontakt@twojadomena.pl</p>
</section>

</body>
</html>
