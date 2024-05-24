<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Des crevettes en armure</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
        }
        header {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            background-color: #00509e;
            padding: 1em;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 1em;
            text-decoration: none;
        }
        section {
            padding: 2em;
            max-width: 800px;
            margin: 0 auto;
        }
        .gallery img {
            width: 100%;
            height: auto;
            margin: 1em 0;
        }
        footer {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: absolute;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Bienvenue dans le monde des Crevettes en Armure</h1>
</header>

<nav>
    <a href="#home">Accueil</a>
    <a href="#about">À propos</a>
    <a href="#gallery">Galerie</a>
    <a href="#blog">Blog</a>
    <a href="#contact">Contact</a>
</nav>

<section id="home">
    <h2>Accueil</h2>
    <p>Découvrez notre projet unique où l'art rencontre l'insolite. Plongez dans un univers sous-marin où les crevettes deviennent des chevaliers courageux.</p>
    <img src="image_accueil.jpg" alt="Crevette en armure héroïque">
</section>

<section id="about">
    <h2>À propos de nous</h2>
    <p>Nous sommes une équipe d'artistes passionnés par la fusion de la créativité et de la nature. Notre projet "Des crevettes en armure" est né de notre amour pour l'innovation et l'art.</p>
</section>

<section id="gallery">
    <h2>Galerie d'art</h2>
    <div class="gallery">
        <img src="image_galerie1.jpg" alt="Crevette en armure">
        <img src="image_galerie2.jpg" alt="Crevette en armure">
        <img src="image_galerie3.jpg" alt="Crevette en armure">
    </div>
</section>

<section id="blog">
    <h2>Blog</h2>
    <p>Lisez nos articles pour en savoir plus sur l'histoire, les inspirations et les techniques derrière nos créations.</p>
    <img src="image_blog.jpg" alt="Crevette en armure avec des outils d'artiste">
</section>

<section id="contact">
    <h2>Contactez-nous</h2>
    <p>Nous aimerions avoir de vos nouvelles. Que vous soyez un passionné d'art, un potentiel collaborateur ou simplement curieux, n'hésitez pas à nous contacter.</p>
    <form>
        <label for="name">Nom:</label><br>
        <input type="text" id="name" name="name"><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email"><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message"></textarea><br>
        <input type="submit" value="Envoyer">
    </form>
    <img src="image_contact.jpg" alt="Crevette en armure avec une bulle de message">
</section>

<footer>
    <p>&copy; 2024 Des crevettes en armure. Tous droits réservés.</p>
</footer>

</body>
</html>
