# Wo leben welche Nutztiere in der Schweiz

Die Schweiz, das Land der Kühe, Schweine und Hühner. Rund 15 Millionen Nutztiere ((Rinder, Pferde, Schafe/Ziegen, Schweine, Geflügel) gibt es hier. Doch in welchen Gemeinden hat es mehr Tiere als Einwohner, wo ist die Tier-/Mensch-Quote am höchsten und wo sind die Hotspots der Tierarten?


## Link zum Artikel

Publizierter Artikel: https://www.watson.ch/!258415238


## Ausgangsthese

In der Schweiz bilden sich immer mehr regionale Hotspots für Nutztiere

In den USA gibt es die Landwirtschaftsgürtel. Steuern wir in der Schweiz mit der Nutztierverbreitung auch auf solch spezialisierte Regionen hin? 


## Idee

Mein kleiner Sohn liebt (Bauernhof-)Tiere. Egal wo wir sind: Er will Tiere sehen. Irgendwann fragte ich mich: Leben in der Schweiz eigentlich bestimmte Nutztiere an bestimmten Orten und wie veränderte sich die Anzahl über die letzten Jahre? Da es (watson-)User lieben, bis auf Gemeindeebene vergleichen zu können, lag eine solche Auswertung auf der Hand. Gerne wird auch gewitztelt, dass Dorf xy ländlicher sei als yz. Oder “Bei euch leben ja mehr Kühe als Menschen”. 

Ich stellte mir folgende Fragen:

- Wie sieht eigentlich die Verteilung der Nutztiere auf Schweizer Gemeinden aus? Gibt es Gebiete, in welchen beispielsweise vor allem Hühner gehalten werden? Warum ist das so oder eben nicht?
- Wie veränderte sich die Anzahl der jeweiligen Nutztiere über die letzten Jahre?
- Warum nahm welches Tier ab/zu?
- Welche Gemeinde hat in absoluten Zahlen und anteilsmässig am meisten Nutztiere?
- Gibt es in der Schweiz eigentlich auch Gemeinden ohne Nutztiere/landwirtschaftliche Betriebe? Gibt es da auch “bauernfreie Hotspots?”
- Und wie oft stimmt der Satz: «Bei euch leben ja mehr Kühe/Schweine/Geflügel/etc. als Menschen?


## Einschätzung von Aufwand / Ertrag vor Beginn

### Datenbeschaffung, Bearbeitung und Auswertung: 
Die Daten sind beim Bundesamt für Statistik, müssen aber zusammengeführt werden (Anzahl Nutztiere und Bevölkerung pro Gemeinde). Die Auswertung düfte einige Zeit in Anspruch nehmen. Ich hoffe, vor allem mit Geopandas die eine oder andere spannende Information zu finden, welche die These unterstützt oder eben nicht.

### Umsetzung: 
Der Artikel lebt wohl von (interaktiven) Schweizergrafiken, damit jeder für seine Gemeinde die Daten schnell findet und vergleichen kann. Die Frage ist: Reicht eine oder braucht es am Ende mehrere? Umsetzung wohl mit Datawrapper. 

Zudem eine Übersicht mit Eckpunkten zu den jeweiligen Tieren und deren Verteilung. Diese dürften aufwendiger sein. Quotes von Gemeinden und/oder Bauernverbänden mit auffallenden Resultaten einholen, sollte problemlos sein.

### Spidercheck: 
- Mögliche Reichweite *****
- Know-How-Aufbau *****
- Kooperationspotential *
- Tiefe des Inhalts ***
- Innovation ****
- Journalistischer Impact **


## Knackpunkte

Entwicklung über die Jahre mit den Gemeindefusionen und sagt die wirklich etwas aus:
Ich entschied mich am Ende – mit Ausnahme der Gesamtanzahl der Tiere –, die Entwicklung über die letzten 20 Jahre wegzulassen und beschränkte mich auf die aktuellsten Daten von 2017. Diese zeigen auch schön, bei welchen Tieren es Hotspots gibt oder nicht.
 
Die Frage nach der Anzahl Grafiken im Artikel:
Erst dachte ich, eine mit der Gesamtnutztierzahl und vielleicht noch eine für Rinder dürfte schon reichen. Da die Verteilung der Tiere aber je nach Art sehr unterschiedlich ist und Geflügel und mit Abstrichen Schweine grundsätzlich in viel grösseren, Pferde und Ziegen in viel kleineren Mengen gehalten werden, machten einzelne Grafiken auf Gemeindeebene Sinn. Darunter gelitten haben die kantonalen Auswertungen, welche wegfielen.

Geflügel als Überflieger: 
Die Anzahl von Geflügel hat sich in den letzten rund 30 Jahren praktisch verdoppelt und steht aktuell bei jährlich 11,5 Millionen Stück. Das ist in absoluten Zahlen und vom Wachstum her einsame Spitze. Was sind die Gründe dafür? Die gegenteilige Frage stellte sich bei den Rindern und Schweinen: Warum nahmen diese doch markant ab? Am Ende entschied ich, im Artikel vertieft auf die Geflügel-Frage einzugehen.

Kategorie “übrige Tiere”:
Die Spanne ist da sehr gross. Römerswil stach mit 170’000 “Übrigen” deutlich heraus. Erst glaubten alle an einen Erfassungsfehler, es stellte sich dann aber heraus, dass hier Fische mitgezählt wurden. Ich entschied auf die klassischen Nutztiere zu fokussieren. Auch weil die genaue Aufteilung der Übrigen kein gutes Aufwand/Ertrags-Verhältnis hatte.

Zusammenhang zwischen Betrieben und Anzahl Tieren:
Gibt es immer mehr Tiere in immer wenigeren Betrieben? Ich entschied im Nachhinein diese Daten auch noch kurz auszuwerten. Das Bild war eindeutig und wenig überraschend: Insgesamt geht die Anzahl landwirtschaftlicher Betriebe in der Schweiz überall zurück (auch in Hotspot-Regionen). Die Anzahl Tiere pro Betrieb nimmt dagegen laufend zu (Einer der Hauptgründe: Professionalisierung). Ich entschied, das Thema nicht in den Artikel aufzunehmen, um den Fokus auf den Tieren/Geflügeln zu lassen.


## Zusammenfassung mit einer Briefingperson

Arthur Zesiger, Bundesamt für Statistik:
Wusste nicht, dass es so eine Auswertung schon mal gegeben habe. Verwies darauf, dass die Daten von den Kantonen kommen und auf Gemeindeebene am anfälligsten sind für Fehler. Bei extremen Zahlen sicher kurz nachprüfen. Sah einen weiteren (kleinen) Knackpunkt betreffend der Betriebsstandorte, welche ausschlaggebend sind für die Statistik und nicht der Ort, an welchem sich das Tier effektiv befindet. Dies vor allem bei Grossbetrieben mit weit verteilten Feldern/Weiden. Die Auswertung der bfs-Kategorie “übrige Tiere” sah er als problematisch an, weil dort die Spanne an verschiedenen Arten so gross sei, was die Aufschlüsselung aufwändig macht und am Ende wohl die Zahlen zu klein sind, um aussagekräftig zu bleiben.

## Die Repo enthält folgende Elemente: 

### Nutztiere Datenaufbereitung.ipynb: 
Code für Bereinigung/Zusammenstellung der Daten 

### Nutztiere Auswertung.ipynb:
Code für Auswertung der Daten inkl. Geopandas und plotten

### Rohdaten (Ordner):
Rohdaten vom Bundesamt für Statistik als csv (BevölkerungEntwicklung, TiereEntwicklung, schweiztieretotal), sowie Bereinigung Einwohner für alle Gemeinden (einwohnerfehlen, nutztieremitalleneinwohnern)

### BereinigteDaten (Ordner):
Bereinigter Datensatz als csv

### Auswertungen (Ordner):
Auswertungen der Daten pro Tierart/Betrieb als csv

### shp:
Shapefile für die Schweiz


## Arbeitsprotokoll

siehe Arbeitsprotokoll.pdf
