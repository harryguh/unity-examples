# Story des Spiels

**Titel:** Atlentos

## Figur

Die Spielfigur ist der Raiffeisen Club Hecht. (-> Asset kaufen)
Man sieht die Figur eigentlich nicht, blickt man jedoch zurück, sieht man die Schwanzflosse.

## Landschaft/Umgebung

Man schwimmt unter Wasser in Linz rund um die Landstraße zwischen Volksgarten und Hauptplatz bzw. teilweise auch durch Hinterhöfe und Plätze. (-> erledigt)
Generell wird am Himmel immer die Sonne angezeigt, ggf. kann die Landschaft über Wasser der aktuellen Jahreszeit angepasst werden, wobei die Sunne immer sichtbar sein muss. (-> Sonne existiert)
Auf der Landstraße wird die neue, moderne Bankfiliale dargestellt, zu der man das gesammelte Geld bringen muss. (-> offen)

## Spielverlauf

### Spielstart

Der Start des Spiels erfolgt immer von der Position aus, bei der das vorige Spiel beendet wurde. (-> immer vom Hauptplatz aus)

### Verlauf

Man schwimmt unter Wasser in der Stadt herum auf der Suche nach Geld. (-> Schwimmen unter Wasser erledigt)
Dieses Geld schwebt auf unterschiedlichen Niveaus, die teilweise unter Wasser, teilweise aber auch in der Luft sein können. (-> erledigt)
In der Luft schwebendes Geld kann man durch leuchtende Reflexionen unter Wasser erkennen. (-> variable Punkteberechnung erledigt)
Unter Wasser kann Geld durch einfaches Durchschwimmen eingesammelt werden, über Wasser muss man versuchen dieses durch einen Sprung aus dem Wasser zu erwischen. (-> Sprung aus Wasser möglich, Collision mit Geldobjekten erledigt)
Das Geld erscheint in bestimmten Intervallen an zufälligen Orten am Spielfeld und bleibt dort bestehen. (-> erledigt)

### Spielende

Ist die definierte Spielzeit abgelaufen, wird das Spiel beendet. (-> Zeit läuft, Spielende erledigt)

## Punkte

Punkte können durch folgende Aktionen erreicht werden:
* Einsammeln von Geld (unter bzw. über Wasser) (-> erledigt)
* Bringen des eingesammelten Geldes zur Bank (Zinsen) (-> erledigt)
* Bringen des eingesammelten Geldes zur Bank am Weltspartag (zusätzliche Zinsen) (-> erledigt)

Die aktuelle Punkteanzahl wird an mehreren Stellen in der Stadt auf Displays angezeigt (z.B. Passage). (-> offen)

Wie man die erzielten Punkte gegen reale Waren umtauschen kann, ist noch offen! (-> offen)

## Besonderheiten

### Weltspartag

Die Sonne am Himmel strahlt immer, zu manchen Zeitpunkten wird in der Sonne ein Raiffeisen-Giebelkreuz angezeigt, welches den Weltspartag anzeigt. (-> erledigt)
Wird das gesammelte Geld zu diesen Zeiten in der Bankstelle abgeliefert, erhält man nicht nur die Zinsen, sondern zusätzlich ein Power-up. (-> gestrichen)

#### Power-ups

* Schneller schwimmen
* Höher springen
* Wasserspiegel steigen lassen
* ...

### Wasserspiegel

Der Wasserspiegel hat einen definierten Tiefststand, kann jedoch vom Spieler beeinflusst werden.
Schwimmt man bis zur Donau, kann man dort einen Damm aktivieren, der das Wasser aufstaut und Linz mehr und mehr bis zu einem definierten Höchststand flutet.
Dadurch sind mehr Geldstücke unter Wasser und können kontrollierter eingesammelt werden.
Der Damm hält eine definierte Anzahl von Spielen (z.B. 3) und wird danach wieder abgebaut.
Da das Einsammeln von Geld bei höherem Wasserspiegel leichter ist als bei niedrigem, soll es ein Anreiz für den Spieler sein, vor Ende seines Spiels den Damm wieder abzubauen, denn dieser Zustand bleibt beim nächsten Spiel erhalten. So kann er die Ausgangssituation des Folgespielers beeinflussen.

(-> offen)

### Gegner

#### Fischer

Auf der Wasseroberfläche fährt ein Fischerboot, das immer wieder Fangnetze ins Wasser wirft.
Wird man von den Fischern erwischt, ist das bisher gesammelte Geld weg und man wird einige Sekunden im Netz festgehalten.
Danach kann man dem Netz entkommen und das Spiel fortsetzen. (-> offen)

Fischerboot + Netz Asset (-> erledigt)

#### Zeit

Die Spieldauer wird mit 5 Minuten begrenzt. Nach dieser Zeit wird die Punkteanzahl in der Hiscore-Liste festgeschrieben und das nächste Spiel beginnt wieder bei 0.
Gesammeltes, jedoch nicht abgeliefertes Geld wird nach Spielende sofort wieder am Spielfeld verteilt.

## Sonstiges

### Menü

(-> erledigt)

### Schwierigkeitsgrade

(-> kein Thema für den Hackathon)

### Gewicht

Je mehr Münzen man sammelt, desto schwerer wird man. Dadurch langsamer und man kann nicht mehr so hoch aus dem Wasser springen.
Erst wenn man bei der Bank abliefert, wird man wieder leichter. (-> erledigt)

### Anleitung

Sprachausgabe zur Anleitung des Spiels.

* Es ist schönes Wetter, du solltest öfter mal einen Blick in die Sonne wagen.
  Wenn sie sich verändert, kannst du mehr Zinsen für das gesammelte Geld bekommen.
* Auch über dem Wasserspiegel kannst du Geld sammeln.
  Tauche ab um Schwung zu holen und springe dann aus dem Wasser.
* Du hast schon sehr viel Geld gesammelt, das ist schwer.
  Am besten du lieferst es bei der Bank ab um wieder leichter zu werden.
* Wenn es dir schwer fällt, Geld über dem Wasserspiegel zu sammeln, kannst du versuchen den Wasserspiegel steigen zu lassen.
  Schwimme dazu Richtung Donau.
* Ansage der verbleibenden Zeit.
  * Los gehts! Sammle in den folgenden 5 Minuten soviel Geld wie möglich und bringe es zur Bank.
  * Die Hälfte deiner Spielzeit ist nun verstrichen.
  * Noch 30 Sekunden bis zum Spielende.
  * Die Spielzeit ist zuende. Hecht geil, dass du gespielt hast!

(-> erledigt)

### Sonstiges für Pitch

* andere Fische
* evtl. Gegner in anderer Bankstelle über Netzwerk einbinden
