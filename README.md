<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Profil Professionnel - [Ton Nom]</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        /* Reset CSS */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', sans-serif;
            line-height: 1.6;
            background-color: #f4f6f9;
            color: #2c3e50;
        }

        header {
            background-color: #2c3e50;
            color: white;
            padding: 60px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.3em;
        }

        nav {
            background-color: #34495e;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: white;
            padding: 15px 20px;
            display: inline-block;
            text-decoration: none;
            transition: background 0.3s;
        }

        nav a:hover {
            background-color: #2c3e50;
        }

        .container {
            max-width: 1000px;
            margin: auto;
            padding: 40px 20px;
        }

        section {
            margin-bottom: 60px;
        }

        h2 {
            margin-bottom: 20px;
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 5px;
        }

        p {
            margin-bottom: 15px;
        }

        .skills-list,
        .projects-list {
            list-style-type: square;
            padding-left: 20px;
        }

        .experience {
            background: #ecf0f1;
            padding: 20px;
            margin-bottom: 20px;
            border-left: 5px solid #3498db;
        }

        form {
            background: #ecf0f1;
            padding: 30px;
            border-radius: 5px;
        }

        form label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }

        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #bdc3c7;
            border-radius: 3px;
        }

        form button {
            background: #3498db;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
        }

        footer {
            text-align: center;
            background-color: #34495e;
            color: white;
            padding: 20px;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>[safwan]</h1>
    <p>Professionnel en <div programme=""></div></p>
</header>

<nav>
    <a href="#about">À propos</a>
    <a href="#skills">Compétences</a>
    <a href="#projects">Projets</a>
    <a href="#experience">Expérience</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    <section id="about">
        <h2>À propos</h2>
        <p>Bienvenue sur mon profil professionnel. Je suis [safwan lamkimel], passionné(e) par [math]. Fort(e) de plusieurs années d’expérience, je propose des services de qualité dans le domaine de [programmes].</p>
        <p>Je suis motivé(e) par l’innovation, la collaboration et le développement constant de mes compétences techniques et humaines.</p>
    </section>

    <section id="skills">
        <h2>Compétences</h2>
        <ul class="skills-list">
            <li>Développement Web : HTML, CSS, JavaScript</li>
            <li>Frameworks : React, Vue.js, Angular</li>
            <li>Backend : Node.js, PHP, Python</li>
            <li>Bases de données : MySQL, PostgreSQL, MongoDB</li>
            <li>Outils : Git, Docker, Figma</li>
            <li>Langues : Français, Anglais, Espagnol</li>
        </ul>
    </section>

    <section id="mon personnality">
        <h2>mon personnality</h2
        <ul class="projects-list">
            <li><strong>mon nom</strong> – safwan lamkimel</li>
            <li><strong>age</strong> – j ai 14 ans.</li>
            <li><strong>mon longeur</strong> – 171 cm</li>
        </ul>
    </section>

    <section id="experience">
        <h2>Expérience</h2>
        <div class="experience">
            <h3>Développeur Front-End – Société XYZ</h3>
            <p><em>Janvier 2022 - Présent</em></p>
            <p>Création d'interfaces web modernes, intégration de maquettes, optimisation de l'expérience utilisateur.</p>
        </div>

        <div class="experience">
            <h3>Stagiaire Développeur – Agence Web ABC</h3>
            <p><em>Juin 2021 - Décembre 2021</em></p>
            <p>Développement de sites vitrines, collaboration avec l’équipe de design, maintenance technique.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <form>
            <label for="name">Nom :</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email :</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message :</label>
            <textarea id="message" name="message" rows="6" required></textarea>

            <button type="submit">Envoyer</button>
        </form>
    </section>
</div>

<footer>
    <p>&copy; 2025 [Ton Nom] - Tous droits réservés.</p>
</footer>

</body>
</html>
