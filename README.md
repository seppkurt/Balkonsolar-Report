# Solar auf der Garage mit Batterie - was sind die Zahlen/Aussagen dazu

## Einleitung

- Zeiträume kaum vergleichbar, es ändern sich dauerhaft Variablen und Bedingungen, 
    - bspw. System: Anzahl/Ausrichtung Paneele, Batteriegröße; Erzeugung: Sonnenstand und Verschattung, Bezug; Urlaub, Lasten
- gesteuerte Einspeisung funktioniert nur mit Smartmeter das Batteriesystem regelt (bei mir Shelly Pro 3 EM und Zendure Hub)
    - sonst Grundlastdeckung, was aber viel verschwendet wegen Lastspitzen wie Kühlschrank, Pumpen usw., siehe dazu Teil in Zahlen 

## Zahlen und Fakten

Zeitstrahl
davor
nur PV
Bat klein
Bat voll usw. was in Keep steht

Jahresverbauch Haushalt 2022, 2023, 2024



Grundlast (zB nachts, ohne Kochen/Spülen, TV, Büro, Waschen)
80-140 (für 3 min) kWh, die Batterie deckt das für 15-20 Stunden
im Winter höher

Erzeugung übers Jahr mit 1640 kWp bei je 820 kWp SSW und SSO
Winter Nov - Januar nahe 0 kWh
Übergang Ab Feb - April und Sep - Okt 2,5 - 3,5 kWh 
Sommer Mai - August, 3,5 - 5 kWh
TODO % in Sonnendauer pro Tag

| Datum        | Abstand in Tagen | Zählerstand (kWh) | Zählerstand / Abstand in Tagen | Erzeugung (geschätzt) | Eigenverbrauch | Einspeisung | Autarkie | Beschreibung |
|--------------|------------------|-------------------|-------------------------------|-----------------------|----------------|-------------|----------|--------------|
| 26.08.2023   | 0                | 0                 |                               |                       |                |             |          |              |
| 01.01.2024   | 128              | 678               | 5.30                          | Geschätzt 2 kWh pro Ta |                |             |          |              |
| 01.04.2024   | 90               | 1148              | 5.75                          | Geschätzt 2 kWh pro Tag |                |             |          |              |
| 14.05.2024   | 43               | 1245              | 2.79                          | Geschätzt 2 kWh pro Tag |                | 90-120 W    |          | Ab hier 2 kWh Batterie, fixe Einspeisung |
| 24.05.2024   | 10               | 1268              | 2.30                          |                       |                |             |          |              |
| 04.06.2024   | 11               | 1270              | 0.18                          |                       |                | Nahe 0 W    |          | Shelley Pro 3 EM eingebaut |
| 23.06.2024   | 19               | 1307              | 1.95                          |                       |                |             |          | Ab hier 4 kWh Batterie |
| 03.08.2024   | 41               | 1367              | 1.46                          |                       |                |             |          |              |
| 16.09.2024   | 44               | 1422              | 1.25                          |                       |                |             |          |              |
| 09.10.2024   | 23               | 1470              | 2.09                          |                       |                |             |          |              |
| 03.11.2024   | 25               | 1512              | 1.68                          |                       |                |             |          |              |
| 15.12.2024   | 42               | 1768              | 6.10                          |                       |                |             |          |              |
| 03.01.2025   | 19               | 1866              | 5.16                          |                       |                |             |          |              |



Zendure hatte lange einen Bug der bei voller Batterie die Erzeugung abgeschaltet hat. Mit dem Fix wurde das auf Bypass umgestellt, d.h. alles was bei voller Batterie erzeugt wird, geht direkt ins Hausnetz und wird dort falls nicht verbraucht, ins öffentliche Netz eingespeist. Siehe Situation im Sommer ab 15 Uhr

## Zusammenfassung
- aufgrund meiner Verschattung und Ausrichtung, sparsam sein bis 11 Uhr, davor kaum Erzeugung
- wenn die Batterie voll ist (Im Sommer Mai - August) ab ca. 15 Uhr STROM VERBRAUCHEN
    - variable Verbraucher anschalten, sonst Einspeisung in öffentliches Netz
    - E-Bike Batterie, Spülmaschine, Waschmaschine, Laptop-Akkus
- mit Batterie 75% des Jahres keine Stromkosten während Abwesenheit (Urlaub)
- Große Verbraucher nicht paralell betreiben
- Falls große Verbrauche sich unterhalb 800 Watt betreiben lassen bspw. PC (Notebook Akku) oder e-bike Akku sinnvoll dann einsetzbar wenn genügend Strom vorhanden 
- TV und Desktop PC ziehen ordentlich, Kochen und Backen hat hohe Peaks und verbraucht viel Energie, Trockner braucht sehr viel Energie
- Steuerung mit dem Volkszähler-Setup (Optokpoppler) hat 1 min Verzögerung und verpasst damit die Lastspitzen
- meine Faustregel 1 (für mein Setup und als Hobby Budget für Batterie) "Solange der Haushalt Strom vom Netz bezieht und trotzdem irgendwann eingespeist wird, ist der Akku zu klein" oder "Solange der Verbrauch höher ist als die Erzeugung ist Einspeisung kein Thema"
