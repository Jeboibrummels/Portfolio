Biljetten en Muntenteller
========

Deze opdracht is een uitbreiding van de Muntenteller van de vorige opdracht. Nu worden ook biljetten toegevoed. \
Het gemiddelde wordt bijgehouden evenals het aantal ingevoerde bedragen en de het totale bedrag van alle tellingen.\

Opdracht
------

* Breid de Muntjes App uit nu ook voor bankbiljetten
* Het maximale bedrag is 2021 euro
* Maximaal één biljet van 500 euro
* Biljetten van 5 euro komen niet voor boven de honderd euro
* Bijhouden hoeveel berekeningen
* Bijhouden totale bedrag
* Bijhouden gemiddelde bedrag
* Inloggen met wachtwoord, max 3x invoeren, bij 3x fout programma wordt gesloten


Werkwijze 
-----

Taal: Small Basic\
Libraries: LitDev

Het inlogsysteem wordt weergegeven in een apart grafisch venster. Hierbij wordt bijghouden hoevaak \
er een fout wachtwoord is ingevoerd. Dit doormiddel van een counter die bijhoudt hoe vaak er ingevoerd wordt. \
Er wordt ook text weergegeven wanneer het wachtwoord fout is. Wanneer het wachtwoord goed is gaat het naar \
het volgende venster. \
Dezelfde images voor de munten zijn gebruikt, voor de biljetten zijn nieuwe images toegevoeged. \
Dezelfde constructie met floor functie en remainder wordt gebruikt als in de munten teller, nu uitgebreid \
met biljetten. Als het bedrag hoger is dan 100 worden briefjes van 5 niet meegenomen in de telling. \
Omdat 1000 het laagste bedrag is waarbij er twee briefjes 500 euro kunnen zijn, wordt vanaf 1000 euro \
het aantal briefjes standaard op 1 gezet. Vervolgens trekken we 500 euro van het bedrag af en doen daarna \
de rest van de berekening. Als het bedrag hoger is dan 2021 euro verschijnt er een pop-up dat het bedrag \
niet uitgerekend kan worden. \
Om er zeker van te zijn dat er alleen getallen worden ingevoerd wordt een check gedaan welke charachters \
ingevoerd zijn in de invoerbox. \
Het aantal berekningen wordt bijgehouden telkens 1 erbij op te tellen wanneer er een bedrag wordt berekend. \
Dit gebeurt alleen als het bedrag voldoet aan bovenstaande eisen en wanneer het invoervenster niet leeg is. \
Het totale bedrag wordt bijgehouden door het ingevoerde bedrag op te tellen bij de vorige bedragen. \
Het gemiddelde wordt bijgehouden door het totale bedrag te delen door het aantal berekeningen. \
Overigens worden deze waarden bijgehouden in een textbestand. Wanneer het programma wordt opgestart wordt \
dit bestand geladen zodat alle vorige berekeningen worden bijgehouden. \
Wanneer er op de resetknop wordt gedrukt zal alles weer terug gaan naar de intitele stand. Dus ook het gemiddelde, \
totale en aantal berekeningen. \
De grafishe weergave wordt op dezelfde manier gedaan als de munten teller. Het verchil is dat de biljetten nu links \
worden weergegeven in een 3x3 configuratie en de munten rechts in een 3x3 configuratie.

