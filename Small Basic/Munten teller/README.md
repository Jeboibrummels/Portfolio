# Munten teller

De bedoeling van deze opdracht was om een muntenteller te maken die in gepast in zo \
weinig mogelijk munten het ingevoerde bedrag kan weergeven.


Opdracht
--------

* Invoer voor een bedrag
* Bedrag uitrekenen in aantal munten
* Programma heeft de mogelijkheid om vaker en bedrag uit te rekenen.


Werkwijze
---------

Taal: Small Basic \
Libraries: LitDev

Bij dit porgrammaatje word gebruik gemaakt van de LitDev library voor Small Basic. \
Als eerste heb ik een aantal images van euromunten gedownload. Deze worden in de code geload.\
Er is een button waarop geklikt kan worden nadat er een bedrag is ingvoerd om door te gaan \
naar de berekening en er is een reset button die alles terug brengt naar de initele stand. \
De button events worden gehandled in een subroutine. \
Wanneer er een bedrag is ingevoer word deze x100 gedaan om het bedrag in centen te krijgen. \
Daarna wordt de Floor van het bedrag gedeeld door de waarde van de munten x 100. De uitkomst\
hiervan is het aantal munten van het ene soort. De Remainder van het zelfde bedrag wordt uitgerekend\
en deze gaat door naar de volgende floor functie met de waarde van de volgende munt. Dit gaat \
zo door t/m de 1 cent munt. Als dat gedaan is wordt gecheckt of het aantal twee euro munten niet\
hoger is dan 99. Zo ja dan worden de munten en hun aantalen grafisch weergegeven. Zo niet dan verschijnt \
er een pop up window dat het bedrag niet uitgerekend kan worden. \
De weergave van de munten wordt zo gedaan dat wanneer er nooit onnodig veel ruimte zit tussen de munten. \
De waarde van de hoogste munt van het te berekenen getal komt altijd op de eerst positie en de volgende \
hoogste waarde komt altijd op de tweede positie. \
De reset knop zorgt er voor dat de weergave van de munten verdwijnt en het invoervenster van het bedrag \
weer leeg is zodat een nieuw getal ingevoerd kan worden. Ook zonder de reset knop kan een nieuw bedrag \
ingevoerd worden en deze zal uitgerekend worden.





