Die Game
====

Deze subfolder bevat drie bestanden. Deze zijn verdeeld over twee opdrachten.

Opdracht 1 
----

Maak een eenvoudige dobbelsteen simulator. Als je een 6 hebt gegooid heb je gewonnen.

* Het programma laat een titel zien
* Het programma vraagt of je wil starten
* Het programma geeft aan hoeveel de worp is geworden
* Als er een zes is gegooid feliciteert het programma je en vraagt of je nog een keer wilt gooien
* Als er geen zes is gegooid vraagt het programma om nogmaals te gooien
* Het programma moet kunnen worden afgesloten

Bestanden: "Die Game.sb", "Die Game1.2.sb"

Werkwijze
----

Taal: Small Basic\
Libraries: n.v.t.

Het bestand "Die Game.sb" bevat de code voor een dobbesteen simulator zonder grafische weergave.\
In een textwindow is de eerste line de titel van het programma. \
Het programma vraagt of je wil gooien en hierop kan een line ingevoerd worden.\
Als er "Yes" in gevoerd wordt, wordt er door een random number generator een getal gekozen. \
en deze wordt weergegeven in de textwindow. Als er geen zes wordt gegooid vraagt het programma \
of je nog een keer wil gooien en wederom kan er text ingevoerd worden. Als er geen "Yes" ingevoerd \
wordt overleef je het spel niet. \
Als er wel zes wordt gegooid heb je het spel overleefd. Er wordt dan gevraagd of je nog een keer wilt \
gooien. Als er geen "Yes" wordt ingevoerd wordt het spel afgesloten.

Omdat dit een eerste opdracht was heb ik eerst deze gemaakt het principe van de opdracht werkend te krijgen. \
Dat betekent, het rollen van de dobbelsteen, het vragen of je (nog een keer) wilt gooien en het afsluiten van het spel. \
En dat deze dingen elkaar opvolgen en niet door elkaar of in de verkeerde volgorde gebeuren. Er is gekozen voor Goto \
statements om te navigeren in de code. \
Het bestand "Die Game1.2.sb" bevat eigenlijk hetzelfde spelletje maar dit keer met grafisch weergave. \
De titel staat dit keer in de bovenste balk van het programma. Er zijn buttons toegevoegd die worden\
weergegeven in een grafishde venster en deze geven ook een kleur wanneer er op geklikt wordt met de muis. \
Dit is gedaan door de x- en y-coordinaten van de muis te tracken. Wanneer er binnen een bepaald gebied met de \
muis wordt geklikt bepaald door x- en y-waarden, wordt bepaald code aangeroepen. Ditmaal wordt er gebruik \
gemaakt van subroutines. \
Er wordt bij de keuze spelen tien keer een random nummber tussen de waardes 1 en 6. Deze waardes zijn verbonden \
aan bepaald figuren die overeenkomen met de respectivelijke ogen op de dobbelsteen. Deze worden ook 10 keer snel \
achter elkaar afgebeeld zodat het lijkt alsof de dobbelsteen daadwerkelijk gerold wordt. 

Opdracht 2
----

* Meerdere dobbelstenen simulator
* Kunnen kiezen hoeveel dobbelstenen er gegooid worden
* Laten zien hoeveel ogen op de voorkant (aantal)
* Laten zien hoveel ogen op de achterkant (aantal)

Bestand: "Multiple Die Game.sb"

Werkwijze
---- 

Taal: Small Basic \
Libraries: LitDev

Er is hier wederom voor gekozen om een grafishce weergave te doen van de dobbelstenen. Dit keer zijn er images \
van het internet gehaald en deze gebonden aan het aantal ogen van de random number generator. Er wordt ook \
gebruik gemaakt van de LitDev library voor Small Basic omdat deze een aantal voordelen heeft. Deze heeft aanroepen \
voor buttons en text entries met basis functionaliteit zoals hover en click en bij de entry is er syntax waarbij je \
de ingevoerde text terug kan halen. \
In het venster kan er een nummer worden ingevoerd voor het aantal dobbelstenen dat gegooid moet worden. \
Deze worden weergegeven in rijen van 4x4. Er zal nooit onnodig veel ruimte tussen de dobbelstenen zitten omdat er \
geprogrammeerd is dat deze altijd in deze configuratie komen te staan. \
Voor de ogen voorkant en ogen achterkant is een knop toegevoed. Wanneer hier op geklikt wordt, worden de ogen \
opgeteld van de huidige worp. \
Er is ook een reset knop toegevoegd die alles weer terug zet in de initiele stand.
