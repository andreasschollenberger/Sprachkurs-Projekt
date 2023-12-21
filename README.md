# Projekt Sprachkurs

## Index.html
Neben dem Text und Bild gibt es eine Navigation auf die Seite class.html

## class.html
Ist als Zwischenseite Gedacht um etwas Werbung für den Sprachkurs auszugeben. Mit der Navigation (Button grün) navigiert man auf die erste seite auf der man die eine Bestellung auslösen kann.


## buchen1.html
Hier auf dieser Seite ist auch gleich das JS mit aufgebeaut siehe unter script. Im html bereich sind drei form zur ausfüllung von Anrede, Vorname und Familienname aufgebaut.
Der Zurück Button navigiert auf die Index.html Seite.
Der Blaue Button ist ein input type="submit" mit der aufgabe auf die nächste seite zu Navigieren (buchen2.html).

Im JS, wird in der ersten Funktion die Form Inputfelder verbunden.
 in der (if) wird überprüft ob alle felder (Anrede, Vorname und Nachname) ausgefüllt sind und speichert jedes feld im Browser unter der App Session Storage wenn alle felder ausgefüllt wurden. Wenn alles ausgefüllt wurde ist mit dem Drücken auf den Blauen Button (Weiter) die Navigation auf die Seite buchen2.html. Ist ein Feld nicht ausgefüllt wird die else ausgeführt. In der else ist ein alert eingefühgt was ein Popup fenster eröffnet wenn nicht alles ausgefüllt wurde.

das JS wird auf jeder Seite gleich behandelt und hat die selben funktionen.

## buchen2.html bis buchen3.html
wie in buchen1.html beschrieben sind die grundelemente die seleben.

Hier unterscheidet sich das JS nur im anfang bei der let abfrage. Hier nimmt das JS zugriff auf die Session Storage App aus dem Browser und greifft auf die (Anrede) (Nachname) zu.
diese Zwei daten werden dann neben dem Hallo im H1 wiedergegeben.

Diese abfrage Anrede und Nachname werden auf den anderen Seiten Wiederholt und immer an oberster stelle ausgegen.

## buchen4.html
Der Button (Miteiling Senden) hat eine Animation bekommen der ein confetti regen auslösst.

## Button Zurück
Der Zürück Button hat die JS funktion bekommen auf die vorgängige Seite zu wechseln um allenfalls falsche einträge zu korigieren. 
