# Solar auf der Garage mit Batterie - was sind die Zahlen/Aussagen dazu

## Einleitung

- Zeiträume kaum vergleichbar, es ändern sich dauerhaft Variablen und Bedingungen, 
    - bspw. System: Anzahl/Ausrichtung Paneele, Batteriegröße; Erzeugung: Sonnenstand und Verschattung, Bezug; Urlaub, Lasten
- gesteuerte Einspeisung funktioniert nur mit Smartmeter das Batteriesystem regelt (bei mir Shelly Pro 3 EM und Zendure Hub)
    - sonst Grundlastdeckung, was aber viel verschwendet wegen Lastspitzen wie Kühlschrank, Pumpen usw., siehe dazu Teil in Zahlen 

## Zahlen und Fakten

<div style="text-align: center"><iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS-z5dD4E9KlhfY2olzrEX0vFCz-tpt3txlGv_PSdX61e7uvdKEYowRO_AByZfbT4_DFFLDh1CJMndW/pubhtml?widget=true&amp;headers=false"></iframe></div>

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
