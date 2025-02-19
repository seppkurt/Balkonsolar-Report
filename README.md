# Solar auf der Garage mit Batterie - was sind die Zahlen/Aussagen dazu

## tl;dr

Seit dem Start vor 309 € eingespart. PV-Eigenverbauch bei ca 66 %, Autarkie über die Gesamtzeit ca. 44 %. Mit größere Batterie bewegt sie sich aktuel in Richtung 55 %. Intrinsische Motivation und Spaß bei der gekonnten Lastverteilung riesig.

## Einleitung

- Zeiträume kaum vergleichbar, es ändern sich dauerhaft Variablen und Bedingungen, 
    - bspw. System: Anzahl/Ausrichtung Paneele, Batteriegröße; Erzeugung: Sonnenstand und Verschattung, Bezug; Urlaub, Lasten
- gesteuerte Einspeisung funktioniert nur mit Smartmeter das Batteriesystem regelt (bei mir Shelly Pro 3 EM und Zendure Hub)
    - sonst Grundlastdeckung, was aber viel verschwendet wegen Lastspitzen wie Kühlschrank, Pumpen usw., siehe dazu Teil in Zahlen 

## Zahlen und Fakten

- Start des Projektes am 20.April 2023
- 4 Modulen mit gesamt 1640 kWp bei Ausrichtung je 2 Module SO und SW, Neigung 20 Grad
- ab November 2024 Ausrichtung und Abstand der Module optimiert; 1,3 m Abstand und je 2 Module Ausrichtung SSO bzw. SSW
- viel Verschattung durch Haus und Baum
- Jahresverbauch Haushalt siehe Tab "Naturstrom Abrechnung"
- aufgrund Bakonsolar keine Einspeisevergütung für Strom der ins öffentliche Netz eingespeist wird und nicht lokal verbraucht wird.
- Grundlast (zB nachts, ohne Kochen/Spülen, TV, Büro, Waschen) 80-140 (für 3 min) kWh, die Batterie deckt das für 15-20 Stunden, im Winter höher
- Mit einem weiteren kleinen Solarpanel (220 kWp) auf der Vorderseite des Hauses lässt sich der Grundbedarf zwischen 12 und 13:30 gut decken.
- Erzeugung ergänzt in der Tabelle

<div style="text-align: center"><iframe width="100%" height="500" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS-z5dD4E9KlhfY2olzrEX0vFCz-tpt3txlGv_PSdX61e7uvdKEYowRO_AByZfbT4_DFFLDh1CJMndW/pubhtml?widget=true&amp;headers=false"></iframe></div>

Zendure hatte lange einen Bug der bei voller Batterie die Erzeugung abgeschaltet hat. Mit dem Fix wurde das auf Bypass umgestellt, d.h. alles was bei voller Batterie erzeugt wird, geht direkt ins Hausnetz und wird dort falls nicht verbraucht, ins öffentliche Netz eingespeist. Siehe Situation im Sommer ab 15 Uhr

### Kosten und Förderung Gesamtkostenberechnung Solaranlage

##### Einzelposten:
- **4 Module Maysun 410 Wp + Hoymiles Wechselrichter 1500**: 1.200,00 €  
- **Aufständerung Valkbox3**: 254,98 €  
- **Zendure Solarflow Hub2000 + AB2000**: 1.258,00 €  
- **Zusätzliche Zendure AB2000**: 795,00 €  
- **Kabel und Sonstiges**: 75,00 €  
- **Shelly Pro 3 EM Smartmeter**: 82,90 € (keine Installationskosten)
- **Ahoy DTU (OTA Auslesen des Hoymiles Wechselrichter)**: 24 €

#### **Summe der Kosten:**  
**1.200,00 € + 254,98 € + 1.258,00 € + 795,00 € + 75,00 € + 82,90 € = 3.665,88 €**

#### **Abzüglich Förderung Berlin:**  
**3.665,88 € - 500,00 € = 3.165,88 €**  

#### **Endsumme:**  
**3.165,88 €**

## Zusammenfassung

### Ammortisation seit Projektstart bis Stand 18.Februar 2025
- kWh erzeugt seit Beginn: **1.561 kWh** (Zahl aus Wechselrichter der an Außensteckdose angeschlossen ist)
- kWh davon ohne Vergütung eingespeist: **530 kWh** (Zahl aus Stromzähler Einspeisezählwerk)
- Selbstverbaucht: **1.030 kWh**
- Ersparnis bei 0,30 €/kWh: **309 €**
- **PV-Eigenverbauch: 66 %**
- **Autarkie bei ca 2.300 kWh Bedarf: 44 %** (für Zeitraum bis große Batterie 1.300 kWH ca 40 % und danach 1.000 kWh ca 50%)
- Freude und Spaß das System aufzusetzen: **unbezahlbar**

### Sonst

- aufgrund meiner Verschattung und Ausrichtung, sparsam sein bis 11 Uhr, davor kaum Erzeugung
- wenn die Batterie voll ist (Im Sommer Mai - August) ab ca. 15 Uhr STROM VERBRAUCHEN
    - variable Verbraucher anschalten, sonst Einspeisung in öffentliches Netz
    - E-Bike Batterie, Spülmaschine, Waschmaschine, Laptop-Akkus
- mit Batterie 75% des Jahres keine Stromkosten während Abwesenheit (Urlaub)
- Große Verbraucher nicht paralell betreiben wenn dafür PV-Strom verwendet werden soll
- Falls große Verbraucher sich unterhalb 800 Watt betreiben lassen bspw. PC (Notebook Akku) oder e-bike Akku sinnvoll dann einsetzbar wenn genügend Strom vorhanden 
- TV und Desktop PC ziehen ordentlich, Kochen und Backen hat hohe Peaks und verbraucht viel Energie, Trockner braucht sehr viel Energie
- Steuerung mit dem Volkszähler-Setup (Optokpoppler) hat 1 min Verzögerung und verpasst damit die Lastspitzen
- meine Faustregel 1 (für mein Setup und als Hobby Budget für Batterie) "Solange der Haushalt Strom vom Netz bezieht und trotzdem irgendwann eingespeist wird, ist der Akku zu klein" oder "Solange der Verbrauch höher ist als die Erzeugung ist Einspeisung kein Thema"

## Next

- noch 1 kWh Batterie dazusetzen, bereits Mitte April ist der Akku in ca. 4 Stunden (ca. 14:30) voll, wenn dann nicht verbraucht wird, geht der Strom als Einspeisung "verloren"
