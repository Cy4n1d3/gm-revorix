# Greasemonkey Revorix Scriptsammlung
Eine Sammlung von Greasemonkey-Scripten f�r das Browserspiel
[Revorix](www.revorix.de). Die Scripte erweitern in der Regel das Interface,
schalten unpraktische Dinge ab oder integrieren externe Tools wie etwa
Schiffsplaner. F�r die Benutzung wird eines der folgenden Addons ben�tigt:

* [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)
* [Tampermonkey](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)

Der Einfachkeit halber ist im Folgenden nur von Greasemonkey die Rede, es sind
aber immer beide Addons gemeint.

## Installation
Die Scripte sind grob nach Themen sortiert, ohne Anspruch auf Richtigkeit oder
Vollst�ndigkeit. Um ein Script zu installieren, w�hlt man dieses in der
Github-Ordner�bersicht aus, sodass der Quellcode zu sehen ist. In der Leiste
oberhalb des Codes f�hrt der Schalter `Raw` zu einem Link, den Greasemonkey als
Scriptquelle erkennt und zur Installation anbietet.

Hinweis: F�r Scripte mit einer `.meta.js`-Variante muss das Original, welches
auf `.user.js` endet, f�r die initiale Installation ausgew�hlt werden. Die
Meta-Varianten sind lediglich f�r (automatische) Updates bestimmt.

## Updates
Die Scripte sind aus diesem Repository heraus per integrierter Update-URL
aktualisierbar. Standardm��ig werden Scripte automatisch aktualisiert.

## Entwicklung
Neue Scripte werden gerne gesehen, dazu einfach einen Pull Request in diesem
Repository erstellen. Folgende Regeln gilt es zu beachten:

* Das Script **muss** legal in Revorix benutzbar sein. Das bedeutet vor allem,
das keine automatisierten Aktionen (Mausklicks etc.) durchgef�hrt werden
d�rfen. Wenn Zweifel �ber die Legalit�t aufkommen, muss vom Revorix-Team die
Unbedenklichkeit best�tigt werden (Ansprechpartner: toasten).

* Das Script **darf nicht** Daten an externe Server senden. Anbindungen an
Clan-Datenbanken etc. sind Sache der Clans, da wir nicht nachvollziehen k�nnen,
was am Ende mit den Daten geschieht.

* Das Script sollte in einem thematisch passenden Unterordner abgelegt werden.
Dabei bitte bestehende Verzeichnisse nutzen, soweit m�glich.

Ansonsten sind der Kreativit�t keine Grenzen gesetzt ;)
