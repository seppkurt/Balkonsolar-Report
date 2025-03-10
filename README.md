# Solar auf der Garage mit Batterie - was sind die Zahlen/Aussagen dazu

## tl;dr
 
Seit dem Start am 20.April 2023 wurden 309 € eingespart. PV-Eigenverbauch bei ca 66 %, Autarkie über die Gesamtzeit ca. 44 %. Mit größere Batterie bewegt sie sich aktuell in Richtung 55 %. Ab Ende Februar bis Mitte Oktober liefert die Anlage bei Sonnenschein ca 3 kWh am Tag. Das deckt bis zu 60 % des täglichen Strombedarfs. Die Stromrechnung hat sich dadurch um 20-40 % reduziert, je nach Betrachtungszeitraum.
Intrinsische Motivation und Spaß bei der gekonnten Lastverteilung riesig.

![PXL_20241125_110133909](https://github.com/user-attachments/assets/8e485d8e-2a5a-46eb-bcf3-09ab57c2eb68)

## Einleitung

- Zeiträume kaum vergleichbar, es ändern sich dauerhaft Variablen und Bedingungen, 
    - bspw. System: Anzahl/Ausrichtung Paneele, Batteriegröße; Erzeugung: Sonnenstand und Verschattung, Bezug; Urlaub, Lasten
- gesteuerte Einspeisung funktioniert nur mit Smartmeter, welches das Batteriesystem regelt (bei mir Shelly Pro 3 EM und Zendure Hub)
    - sonst Grundlastdeckung, was aber viel verschwendet wegen Lastspitzen wie Kühlschrank, Pumpen usw., siehe dazu Teil in Zahlen 

## Zahlen und Fakten

- Start des Projektes am 20.April 2023
- 4 Modulen mit gesamt 1640 kWp bei Ausrichtung je 2 Module SO und SW, Neigung 20 Grad
- ab November 2024 Ausrichtung und Abstand der Module optimiert; 1,3 m Abstand und je 2 Module Ausrichtung SSO bzw. SSW
- viel Verschattung durch Haus und Baum
- Jahresverbauch Haushalt siehe Tab "Naturstrom Abrechnung"
- aufgrund Bakonsolar keine Einspeisevergütung für Strom der ins öffentliche Netz eingespeist wird und nicht lokal verbraucht wird.
- Grundlast (zB nachts, ohne Kochen/Spülen, TV, Büro, Waschen) 80-140 (für 3 min) Watt, meine Batterie deckt das für 15-20 Stunden je nch Ladestand, im Winter höher
- Mit einem weiteren kleinen Solarpanel (220 kWp) auf der Vorderseite des Hauses lässt sich der Grundbedarf zwischen 12 und 13:30 gut decken.
- Erzeugung ergänzt in der Tabelle

<div style="text-align: center"><iframe width="100%" height="500" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS-z5dD4E9KlhfY2olzrEX0vFCz-tpt3txlGv_PSdX61e7uvdKEYowRO_AByZfbT4_DFFLDh1CJMndW/pubhtml?widget=true&amp;headers=false"></iframe></div> 
[Daten und Diagramme direkt in der Tabelle anschauen.](https://docs.google.com/spreadsheets/d/1OQrDd55vFqSM-HJhpbEvh-sc8auhfAw-Hk7Z3eXBGTc/edit?usp=sharing)

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
- **Zusätzliche Zendure AB1000S**: 328,00 €
- 
#### **Summe der Kosten:**  
**1.200,00 € + 254,98 € + 1.258,00 € + 795,00 € + 75,00 € + 82,90 € + 328 € = 3.993,88 €**

#### **Abzüglich Förderung Berlin:**  
**3.993,88 € - 500,00 € = 3.493,88 €**  

#### **Endsumme:**  
**3.493,88 €** inklusive jede Menge Spaß bei den Arbeiten am System und Austauschmit Freunden/Interessierten dazu

![PXL_20240517_063642188](https://github.com/user-attachments/assets/9ed1520c-68aa-437e-a72d-8e567aeacf18)

## Zusammenfassung

### Ammortisation seit Projektstart bis Stand 18.Februar 2025
- kWh erzeugt seit Beginn: **1.561 kWh** (Zahl aus Wechselrichter der an Außensteckdose angeschlossen ist)
- kWh davon ohne Vergütung eingespeist: **530 kWh** (Zahl aus Stromzähler Einspeisezählwerk)
- Selbstverbaucht: **1.030 kWh**
- Ersparnis bei 0,30 €/kWh: **309 €**
- **PV-Eigenverbauch: 66 %**
- **Autarkie bei ca 2.300 kWh Bedarf: 44 %** (für Zeitraum bis große Batterie 1.300 kWH ca 40 % und danach 1.000 kWh ca 50%)
- Die Solarmodule laden direkt die Batterie und damit ist es möglich, deutlich mehr als die 800 Watt Leistung (beschränkt durch die Regelung für Balkonsolaranlagen) anzuschließen.
- Freude und Spaß das System aufzusetzen: **unbezahlbar**

### Sonstiges

- aufgrund meiner Verschattung und Ausrichtung, sparsam sein bis 11 Uhr, davor kaum Erzeugung
- das Zendure System kann unter 100 Watt Einspeisung nur in Stufen von 30,60, 90 Watt einspeisen. Das ist ok, aber bei geringer Last wird es etwas ungenau.
- kleines Solarmodule mit 240 kWp mit Solarnative-Wechselrichter auf der Vorderseite des Hauses erzeugt am Vormittag bis Mittag 200-300 kWh.
- wenn die Batterie voll ist (Im Sommer Mai - August) ab ca. 15 Uhr STROM VERBRAUCHEN
    - variable Verbraucher anschalten, sonst Einspeisung in öffentliches Netz
    - E-Bike Batterie, Spülmaschine, Waschmaschine, Laptop-Akkus
    - Frage Stefan: "Wie wäre es mit netzdienlichem Verhalten, d.h. Einspeisen zur Mittagszeit gänzlich verhindern?
    - Antwort Sebastian: "Ja, theoratisch möglich. Aber bei meiner Anlage (Ausrichtung, Größe, Verschattung) eher kein Problem. 
- mit Batterie während Abwesenheit (Urlaub) 75% des Jahres keine Stromkosten
- Große Verbraucher nicht paralell betreiben wenn dafür PV-Strom verwendet werden soll
- Falls große Verbraucher sich unterhalb 800 Watt betreiben lassen bspw. PC (Notebook Akku) oder e-bike Akku sinnvoll dann einsetzbar, wenn genügend Strom vorhanden. Entweder sie lassen sich in ihrer Last regeln oder gehen einfach nicht mit der Lastspitze oberhalb 800 Watt.
    - Auch die Verwendung von mehr als einem Balkonkraftwerk könnte das lösen. Dabei werden dann mehr als 800 Watt an das Hausnetz abgegeben (gesetzlich erlaubt bis zu 3-mal).
- TV und Desktop PC ziehen ordentlich, Kochen und Backen hat hohe Peaks und verbraucht viel Energie, Trockner braucht sehr viel Energie
- Steuerung mit dem Volkszähler-Setup (Optokpoppler) hat 1 min Verzögerung und verpasst damit die Lastspitzen
    - Anmerkung von Stefan: "Das ließe sich wegoptimieren, liegt vor Allem an Abtastraten und Mittelungen in der Volkszähler-Konfiguration"
    - Antwort Sebastian: "Ja okay, allerdings braucht es dann trotzdem noch die Batteriesteuerung die darauf reagiert. Zendure bietet da z.B. aktuell nur Shelly Support an."
- meine Faustregel 1 (für mein Setup und als Hobby Budget für Batterie) "Solange der Haushalt Strom vom Netz bezieht und trotzdem irgendwann eingespeist wird, ist der Akku zu klein" oder "Solange der Verbrauch höher ist als die Erzeugung ist Einspeisung kein Thema"

## Next

- noch 1 kWh Batterie dazusetzen, bereits Mitte April ist der Akku in ca. 4 Stunden (ca. 14:30) voll, wenn dann nicht verbraucht wird, geht der Strom als Einspeisung "verloren"
- 

## PS bzw. auf dem Weg hier her

- Ich hatte noch weitere Batteriesysteme zum Test zu Hause. Beide habe ich zurückgesandt
   - System A passte nicht mit der Spannung meiner Module zusammen. Es hätte allerdings eine spannende Einspeisereglung gehabt
   - System B konnte nur über das Hausnetz mit konstant (hoher) Leistung geladen werden. Das war "damals" noch nicht Stand der Technik
