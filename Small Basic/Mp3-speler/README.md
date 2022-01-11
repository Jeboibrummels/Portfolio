Mp3-speler
====

De opdracht was om een mp3-speler te maken in Small Basic. Dit was een team opdracht en is \
met twee mensen gemaakt. De mp3-speler moest een aantal functies hebben zoals bijvoorbeeld het \
aanmaken van een playlist en het printen van deze playlist. 

Opdracht
----

* Mooie, nette GUI
* Een mp3-bestand kunnen afspelen, pauzeren en stoppen
* Voor- en achteruit kunnen bladeren
* Eenvoudig kunnen angeven in welke map zich de af te spelen mp3's zich bevinden
* Een lijst kunnen  printen met de aanwezige muziekbestanden in deze map
* Vastlegeen hoe vaak een nummer wordt afgespeeld in een top 10
* Top 10 kunnen afspelen
* Zelf een playlist kunnen samenstellen
* Een shuffle-functie
* Muziekbestanden importeren uit een specifieke folder
* Een nummer of een complete playlist verwijderen
* Volume regeling

Werkwijze
----

Taal: Small Basic\
Libraries: LitDev

Eerst is de GUI ontworpen. De images die gebruikt zijn, zijn gemaakt in Word, omdat je hier mooie simpele vormen \
kan maken die te gebruiken zijn voor buttons. Deze images zijn vervolgens online gehost zodat het niet afhaneklijk \
is van een folder op een pc. \
Sommige buttons roepen over de layout van het scherm andere schermen op waarop bijvoorbeeld de nummers van een \
bepaalde playlist staan. Omdat het niet mogelijk is om lagen te maken in de layout moest hier een oplossing voor \
komen aangezien de mouseklikken afhanekelijk zijn van de x- en y-positie. Dit hebben we opgelost door wanneer er \
een scherm over het layout verschijnt deze te binden aan een letter met een waarde. Bijvoorbeeld wanneer het scherm \
verschijnt voor het naam invoeren van een nieuwe playlist dan c = 1. De rest van de buttons is zo geprogrammeerd dat \
wanneer c = 1 er niks gebeurt. \
LitDev heeft een functie om de muziekfolder aan te roepen als de folder waar muziekbestanden vanuit kunnen worden \
afgespeeld. Er is voor gekozen om van deze functionaliteit gebruikt te maken om het simpel te houden. \
LitDev heeft ook de mogelijkheid om mp3-files af te spelen, te pauzeren of te stoppen. Deze hebben we ook gebruikt \
voor dit project. Wanneer mp3-files worden aangeroepen uit de folder worden deze in een array gestopt. Daardoor \
kunnen we makkelijk voor en achteruit bladeren door de index + 1 of -1 aan te roepen en de huidige file te stoppen \
met afspelen. Shuffle is gemaakt door een random number generator een nummer te laten kiezen tussen 1 en het aantal \
files in de folder en deze vervolgens af te spelen. \
De playlists kunnen worden aangemaakt en naam worden gegeven. Deze worden opgeslagen in "PlayData.txt". Door op de knop \
musiclist te drukken verschijnt er een lijst met de muziekfiles uit de muziekfolder. Afhaneklijk van het aantal playlists \
dat is aangemaakt verschijnt onderaan deze lijst een aantal buttons gekoppeld aan deze playlists. Als de button  eenmaal \
wordt ingedrukt (wordt hij groen) en is het nummer toegevoed aan de playlist. Wordt de button nogmaals ingedrukt, dan wordt \
hij weer zwart en is het nummer uit de playlist verwijderd. De playlist is ook weer een aparte array \
daardoor kunnen de shuffle functie en vooruit en achteruit bladeren op dezelfde manier worden toegespast. \







