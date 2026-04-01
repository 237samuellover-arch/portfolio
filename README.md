<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>portfoliot</title> 
    <link rel="stylesheet" href="portfolio.css">
    <link rel="shortcut" href="4.jpg" type="image">
</head><link rel="stylesheet" href="portfolio.css">
<body>
    <header id="header"> 
        <h3 class="menu">NA</h3>
            <nav>
                <ol id="tout"> 
                    <a href="#accueil" id="accueil">accueil</a>
                    <a href="#à propos" id="à propos">à propos</a>
                    <a href="#competence" id=" Ce que je sais faire ">competances</a>
                    <a href="#contact" id="contact">contanct</a>
                </ol>
            </nav>
    </header>
    <section id="sectinner">
        <section class="sect">
        <div>
            <h5 class="menu"> dévelppeur web - étudiant en informatique </h5>
            <h1 class="main-title"> Nguetsa Assamb </h1>
            <h1 id="main">Ludovic Samuel</h1>
            <p>Passionner par la création d'expérience web</p>
            <p>moderne et accessible.En route vers le </p>
            <p id="para"> développement front-end</p><br>
            <button id="cont" type="button">ME CONTACTER</button>
        </div>
        <img src="4.jpg" id="photo" alt="" srcset="">
        </section>
    <section class="sect"> 
       <div> 
        <p class="menu">A PROPOS</p><br>
        <h1> Qui suis-je ?</h1>
        <p id="par"></p>
        </div>
        <div class="divis">
            <p>je suis etudiant en première année à l'université de yaoundé 1.animé par une vrai curiosité pour le web et ces diffelarentes technologies.Je m'intéresse particulièrement à la conception d'interface élégantes;à l'expérience utilisateur,et au bonne pratique du devéloppement front-end <br>
            mon objectif : devenir développeur frn-end capable de transfrmer des idées en expérience digitales mémorable </p>
           </p>
            <h1>1 <sup>ère</sup></h1>
            <p> ANNEE INFORMATIQUE</p>
        </div>
    </section>
    <section class="sect">
         <p class="menu">COMPETENCES</p>
            <h1> Ce que je sais faire </h1>
            <div id="divi">
             <div class="HTML">
                <h3> HTML</h3>
                <h5>Structure sémantique,accessibilité,bonne pratique</h5>
            </diV>
             <div class="HTML">
                <h3>Git</h3>
                <h5>versioning,branche,gestion de l'historique</h5>
            </div>
            <div class="HTML">
                <h3>GitHub</h3>
                <h5>Collaboration,pull requests,hébergementde projet</h5>
            </div>
            <div class="HTML">
                <h3>TravailA en équipe</h3>
                <h5>communication,organisation,méthode agiles</h5>
            </div>
            <div class="HTML">
                <h3>Resolution de problèmes</h3>
                <h5>Analyse;décomposition,logique algorithmique.</h5>
            </div>
            </div>
    </section>
    <section class="sect">
             <p class="menu">PARCOURT</p>
                <h1>Mon chemin</h1>
            2025 <div> DIPLOME
                    <li><h3>Bacclauréat scientifique </h3></li>
                    <li><p> Obtention du baccalauréat avec spécialité scientifique,premier pas vers l'informatique</p></li>
                </div>
            2026<div>FORMATION
                    <li><p>Première année de licence informatique,initialisation a l'algorithmique,aux language et aux système d'exploitation</p></li>
                </div>
            2026 <div>EN COURS
                    <li><h3>Formation en développement web</h3></li>
                    <li><p>apprentissage du HTML,des balise du développement front-end moderne,du CSS et Javascript,tout ceci à fin de sortir une page web avec un très jolie front-end</p></li>
                </div>
            2026<div>POUR LA SUITE
                    <h3>Mini projet de E-coommerce </h3></li>
                    <p>Je compte également apprendre à développer et déployer des mini site de E-commerce bien fnctionnels </p></li>
                </div>
    </section>
    <section id="fin">
        <P class="menu">CONTACT</P>
        <h1 class="main-title">Travaillons</h1>
        <h1> ensemble</h1>
        <p>Une question,une idée,un projet,ou simplement une envie d'échangé,d'apprendre,de ce concerté.</p>
        <p> Bref je suis l'homme qu'il vous faut.N'hésiter pas m'écrire
        </p>
         <form action="traitement.php" method="post" id="form">
            <li></li>NOM COMPLET<input type="text" name="Nom complet" placeholder="Votre nom complet">
            <li></li>ADRESSE EMAIL <input type="email" name="email" id="email" placeholder="votre@email.com">
            <li></li>MESSAGE <input type="text" name="message" size="40" placeholder="Bonjour Ludovic,je voulais...">
            <li></li><button id="cont" type="button">Envoyer le message</button>
            <button id="cont" type="button" >effacer</button>
        </form> 
    </section>
    </section>
     <script src="index.js"></script>
</body>
</html>
