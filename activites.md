---
layout: default
title: "Activités"
---

<header class="header-container">
    <img class="logo" src="assets/logo.jpg" alt="Logo Code Collectif">
    <h1>Code Collectif</h1>
    <nav class="menu">
        <ul>
            <li><a href="#">Accueil</a></li>
            <li><a href="projets.html">Projets</a></li>
            <li><a href="activites.html">Activités</a></li>
            <li><a href="#">Partenaires</a></li>
            <li><a href="https://www.helloasso.com/associations/code-collectif">Adhérer</a></li>
        </ul>
    </nav>
</header>

<main>
{% include activite_section.html title="Les activités de Code Collectif" description="Une petite description rapide des activités de l'association sans entrer dans les détails..." %}

{% include activite_section.html title="Initiation au code" description="L'association vous propose des ateliers pour vous initier au code. Si vous avez envie de découvrir cet univers, vous trouverez nos événements plus bas sur cette page. Nous vous proposons également des dojos poru apprendre en s'amusant. Il est aussi possible de faire le test de compétences en programmation." %}

{% include activite_section.html title="Les rendez-vous Bidouilles" description="Qu'est-ce que les rendez-vous Bidouilles ? 
Où et quand ont-ils lieux ? Tous les premiers mardi du mois à l'espace Saint Ex à Reims.
A qui s'adressent-ils ?" %}

{% include activite_section.html title="Les autres rendez-vous" description="Vous pouvez trouver des clash of codes et des discussions autour des technologies sur le discord de l'association. Il y a aussi des ateliers pour les anfants pendant les vacances. " %}


</main>
<footer class="footer-container">
    <p class="footer-text">&copy; 2025 Code Collectif</p>
    <p class="footer-link">Site hébergé sur un VPS IKOULA
        <a target="_blank" href="https://www.ikoula.com/fr">
            <img src="https://www.ikoula.com/img/hosted_by_ikoula_150_blanc.png" alt="site hébergeur">
        </a>
    </p>
    <p class="footer-link2"><a href="#">Nous contacter</a></p>
</footer>
