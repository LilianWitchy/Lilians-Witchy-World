---
title: Über mich
permalink: /about/
---
<!DOCTYPE html>
<html lang="de">
<head>
    <link rel="icon" type="image/x-icon" href="favicon.ico">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Über mich | Lilian´s Witchy World</title>
    <style>
       body {
             font-family: Garamond, serif;
             color: white; /* Textfarbe für den gesamten Body */
             background-color: #4e0261; /* Hintergrundfarbe für den gesamten Body */
             margin: 0;
             padding: 0;
             text-align: center;
         }

        .navbar {
            background-color: #0aa667;
            padding: 15px;
        }

        .navbar button {
            background-color: white;
            color: #660082;
            border: none;
            padding: 10px 20px;
            font-size: 18px;
            cursor: pointer;
        }

        .menu {
            display: none;
            margin-top: 20px;
        }

        .menu a {
            display: block;
            color: white;
            text-decoration: none;
            font-size: 20px;
            padding: 10px;
        }

        .about-section {
            padding: 20px;
            text-align: left;
            max-width: 800px;
            margin: 0 auto;
            color: black; /* Textfarbe geändert auf schwarz */
            background-color: #f4f4f4; /* Hellgrauer Hintergrund für den Abschnitt */
        }

        h2 {
            color: #f4c542; /* Gelbe Farbe für Überschrift */
        }

        h3 {
            color: #f4c542; /* Gelbe Farbe für Unterüberschrift */
        }
    </style>
</head>
<body>
    <h1>
        <img src="/witchylogo.png" alt="Witchy Logo">
        Lilian’s Witchy World
    </h1>

    <p>Willkommen auf meiner Seite! Mein Name ist Lilian. Das ist die Kurzform von Elisabeth-Ann.</p>

    <div class="navbar">
        <button onclick="toggleMenu()">Menü anzeigen</button>
    </div>

    <div class="menu" id="menu">
        <a href="/">Startseite</a>
        <a href="/about/">Über mich</a>
        <a href="#">Weiterbildungen</a>
        <a href="#">Meine Bücher</a>
        <a href="#">Meine Rezepte</a>
        <a href="#">Social Media</a>
        <a href="#">Bücher, die ich empfehle</a>
        <a href="/kontakt/">Kontakt</a>
    </div>

    <div class="about-section">
        <h2>Über mich</h2>
        <p>Willkommen auf meiner Seite! Mein Name ist Lilian. Das ist die Kurzform von Elisabeth-Ann.</p>
        <p>Mit dieser Homepage teile ich meine Gedanken und Projekte.</p>
        <p>Ich bin staatlich anerkannte Erzieherin mit Bachelor und gelernte Erlebnispädagogin. Lange Zeit habe ich in verschiedenen Kindergärten in verschiedenen Bundesländern gearbeitet.</p>

        <p>Die Umstände in den Kindergärten machten mich immer kränker. Heute bin ich an dem Punkt, dass ich diesen Beruf nicht mehr ausüben kann und werde. Dennoch möchte ich noch immer Gutes tun und den Menschen helfen.</p>

        <p>Es gab jedoch einen Kindergarten, in dem so gut wie alles stimmte und passte. Dort fing ich dann an, mit dem Geschichten schreiben. Ich habe auch früher schon sehr viele Geschichten oder ganze Bücher geschrieben, doch diese waren mehr ein Hobby und eher für mich.</p>

        <p>So fing ich an, eine Traumreise nach der anderen für die Kinder zu schreiben und wenn es hieß, ich lese diese vor, wurde mein Raum voller und voller. All den Kindern dieses Leuchten in die Augen zu zaubern, war für mich das größte Geschenk.</p>

        <p>Vor ein paar Jahren wurde ich dann richtig krank und es wurde klar, dass ich nicht mehr als Erzieherin arbeiten kann und werde. Doch es machte mich traurig, dass meine Geschichten nun einstauben. Ich hatte sie damals noch per Hand geschrieben, auf jedes Stück Papier, das ich finden konnte.</p>

        <p>Deshalb setzte ich mich dran und fing an, alles abzutippen. Und der Flow begann. Es wurden mehr und mehr und mehr Geschichten. Heute sind schon Band 1 und Band 2 von meinen "Traumreisen mit Baldur" erhältlich. Und ich fing an, auch ein Buch für Erwachsene zu schreiben. Auch dies ist seit Kurzem kaufbar.</p>

        <p>All meine Bücher soll es mit der Zeit sowohl hier als auch bei YouTube als Audio geben.</p>

        <p>Da ich leider keinen Verlag habe, der mich bei meiner Arbeit unterstützt, habe ich bisher all meine Bücher mit der Hilfe und dem Technik-Know-How von meinem Mann über Amazon veröffentlicht.</p>

        <p>Und das ist noch lange nicht alles. Schon seit vielen Jahren interessiere ich mich für Kräuter und all ihre Vielfalt. Ich nutze Kräuter und Gewürze, um meine Kosmetikprodukte selbst herzustellen, da ich früher auch mal sehr starke Probleme mit meiner Haut hatte. Auch in diesem Bereich habe ich schon anderen geholfen und möchte das weiter tun, deshalb werde ich meine Rezepte online stellen.</p>

        <p>Ich mache mit den Kräutern eigene Teemischungen, Salben und stelle auch natürliche Medikamente wie pflanzliches Antibiotikum, Apfelsaft mit Kräutern bei Erkältungen, Hustensaft, Limonade, etc. her.</p>

        <h3>Was mir wichtig ist:</h3>
        <ul>
            <li>Yoga</li>
            <li>Die Natur – ein bewusster und achtsamer Umgang mit ihr</li>
            <li>Chemiefreie Alternativen für Kosmetik-, Hygieneprodukte, Nahrungsmittel und Medizin</li>
            <li>Alles, was mit Entspannung und zu sich selbst finden zu tun hat</li>
        </ul>

        <p>Aktuell arbeite ich noch an weiteren Projekten, wie den Audioaufnahmen und weiteren Büchern zu anderen Themen.</p>

        <p>Danke, dass du hier bist und meine Seite besuchst.</p>
    </div>

    <script>
        function toggleMenu() {
            var menu = document.getElementById("menu");
            if (menu.style.display === "none" || menu.style.display === "") {
                menu.style.display = "block";
            } else {
                menu.style.display = "none";
            }
        }
    </script>
</body>
</html>
