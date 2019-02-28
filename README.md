# Wo leben welche Nutztiere in der Schweiz

Die Schweiz, das Land der Kühe, Schweine und Hühner. Rund 15 Millionen Nutztiere gibt es hier. Doch in welchen Gemeinden hat es mehr Tiere als Einwohner, wo ist die Tier-/Mensch-Quote am höchsten und wo sind die Hotspots der Tierarten?

## Link zum Artikel

Sobald publiziert (wohl in der Woche ab dem 4. März:
https://www.watson.ch/!781895938

Vor der Publikation gibts den Artikel hier in der Vorschau. Allerdings läuft dieser Link immer nach 24 Stunden wieder ab und muss erneuert werden. Zudem sind hier noch diverse mögliche Titel drin:
https://www.watson.ch/!781895938?revkey=9--Poki-Papotakukokipupi-Takobuto-Kipaba-Tiki-Tubakubi-Bopuba-Patibopa-Ku-Koto-Tu-Tupi-Papituti

## Ausgangsthese

Welche Gemeinde hat eigentlich absolut und relativ am meisten Nutztiere (Rinder, Pferde, Schafe, Ziegen, Schweine, Geflügel). Und woher kommen die regionalen Hotspots?

## Idee

Die (watson-)User lieben es, wenn sie bis auf Gemeindeebene vergleichen können. Gerne wird auch gewitztelt, dass Dorf xy ländlicher sei als yz. Ich untersuche dies anhand der Nutztiere. Und schaue auch auf die Entwicklung über die Jahre.

## Einschätzung von Aufwand / Ertrag vor Beginn

Datenbeschaffung, Bearbeitung und Auswertung: 
Die Daten sind beim Bundesamt für Statistik, müssen aber zusammengeführt werden (Anzahl Nutztiere und Bevölkerung). Die Auswertung düfte einige Zeit in Anspruch nehmen. Ich hoffe, vor allem mit Geopandas noch die eine oder andere spannende Information zu finden. 

Umsetzung: 
Der Artikel lebt wohl von (interaktiven) Schweizergrafiken. Die Frage ist: Reicht eine oder braucht es am Ende mehrere? Umsetzung wohl mit Datawrapper. Zudem sicher eine Übersicht mit Eckpunkten. Diese dürften aufwendig sein. Quotes von Gemeinden mit auffallenden Resultaten einholen, sollte problemlos sein.




## Knackpunkte

Entwicklung über die Jahre mit den Gemeindefusionen und sagt die wirklich was aus: Ich entschied mich am Ende, dies wegzulassen. Mit Ausnahme der Gesamtanzahl. 

Die Frage nach der Anzahl Grafiken im Artikel. Erst dachte ich, eine mit der Gesamtnutztierzahl und vielleicht noch Rinder dürfte schon reichen. Da die Verteilung der Tiere aber je nach Art sehr unterschiedlich war und Geflügel und mit Abstrichen Schweine grundsätzlich in viel grösseren, Pferde und ZIegen in viel kleineren Mengen gehalten werden, machten einzelne Grafiken auf Gemeindeebene Sinn. Darunter gelitten haben die kantonalen Auswertungen, welche wegfielen.

Kategorie “übrige Tiere”. Die Spanne ist da sehr gross. Römerswil stach mit 170’000 Übrigen deutlich heraus. Erst glaubten alle an einen Erfassungsfehler, stellte sich dann aber heraus, dass hier Fische mitgezählt wurden. Ich entschied auf die klassischen Nutztiere zu fokussieren. Auch weil die genaue Aufteilung der Übrigen sehr aufwändig geworden wäre.

Zusammenhang zwischen Betrieben und Anzahl Tieren - war praktisch nicht möglich, die Spanne ist zu gross und die genaue Aufteilung, welcher Betrieb welche Tiere hält fehlte.

## Zusammenfassung mit Briefingperson

Arthur Zesiger, Bundesamt für Statistik:
Wusste nicht, dass es so eine Auswertung schon mal gegeben habe. Verwies darauf, dass die Daten von den Kantonen kommen und auf Gemeindeebene am anfälligsten sind für Fehler. Bei extremen Zahlen sicher kurz nachprüfen. Sah einen weiteren (kleinen) Knackpunkt betreffend der Betriebsstandorte, welche ausschlaggebend sind für die Statistik und nicht der Ort, an welchem sich das Tier effektiv befindet. Dies vor allem bei Grossbetrieben mit weit verteilten Feldern/Weiden. Auswertung der bfs-Kategorie “übrige Tiere”, weil dort die Spanne an Arten so gross sei. Aufschlüsselung sei dann aufwändig.

## Datensatz und Programmiercode

Zusammengestellte Excels vom bfs, bearbeitete CSV-Files, Shapefiles und Code: Siehe oben

## Arbeitsprotokoll

### ab 14.1.19: 
Storyidee ausarbeiten. Was will ich mit dem Artikel erreichen? Wie verpacke ich ihn, dass es spannend ist

### 22.2.: 
Idee ausarbeiten, besprechen im Team, Briefingpersonen kontaktieren, Daten sammeln und bearbeiten

### 25.2.: 
Daten sammeln und bearbeiten. Storyidee aufgrund der Geopandas überprüfen, an Möglichkeiten anpassen (ausbauen). Diverse Telefonate mit Bauernverbänden und Gemeinden

### 26.2.: 
Umsetzung der Schweiz-Karten, Punkte für “In Kürze”-Grafiken bestimmen - im Notebook anpassen/hinzufügen, diverse Telefonate mit Bauernverbänden und Gemeinden, Artikel schreiben.

### 27.2.:
Letzter Schliff am Artikel/Grafiken. 
