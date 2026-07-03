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

body{
    margin:0;
    font-family:Arial, Helvetica, sans-serif;
    background:#f4f4f4;
    color:#333;
}

header{
    background:#4f46e5;
    color:white;
    text-align:center;
    padding:60px;
}

section{
    max-width:800px;
    margin:40px auto;
    background:white;
    padding:30px;
    border-radius:10px;
    box-shadow:0 5px 15px rgba(0,0,0,.1);
}

button{
    background:#4f46e5;
    color:white;
    border:none;
    padding:12px 24px;
    border-radius:6px;
    cursor:pointer;
    font-size:16px;
}

button:hover{
    background:#3730a3;
}

footer{
    text-align:center;
    padding:20px;
    margin-top:40px;
}
