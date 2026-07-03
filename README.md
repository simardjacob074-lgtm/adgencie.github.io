# adgencie.github.io

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon premier site</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Bienvenue !</h1>
    <p>Mon premier site hébergé sur GitHub Pages.</p>
</header>

<section>
    <h2>À propos</h2>
    <p>Je suis en train d'apprendre à créer des sites web.</p>

    <button id="btn">Clique-moi</button>

    <p id="message"></p>
</section>

<footer>
    © 2026 Mon Site
</footer>

<script src="script.js"></script>

</body>
</html>

const bouton = document.getElementById("btn");
const message = document.getElementById("message");

bouton.addEventListener("click", () => {
    message.textContent = "🎉 Bravo ! JavaScript fonctionne.";
});

