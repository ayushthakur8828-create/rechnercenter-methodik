# Schornstein-Rechner

Live: https://rechnercenter.de/schornstein-rechner-online

Schornsteinquerschnitt nach Leistung, Höhe und Brennstoff grob abschätzen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Nennwärmeleistung | kW | 8 |
| Schornsteinhöhe | m | 8 |
| Brennstoff |  | Holz / Kaminofen |

## Berechnung

Basiswert: bis 6 kW → 130 mm · bis 9 kW → 150 mm · bis 14 kW → 180 mm · bis 20 kW → 200 mm · darüber → 250 mm
Höhe unter 5 m → +30 mm · Öl oder Gas → −20 mm
Ergebnis = nächste Normgröße ≥ Basiswert aus 113 / 130 / 150 / 180 / 200 / 250 / 300 mm
Der Rechner ordnet die Nennwärmeleistung einer Leistungsstufe zu und korrigiert den Wert für kurze Schornsteine nach oben, weil ein kurzer Schornstein weniger Auftrieb erzeugt. Für Öl und Gas zieht er 20 mm ab. Danach wird auf den nächsten gängigen Rohrdurchmesser aufgerundet. Holz und Pellets behandelt das Werkzeug identisch.
Eine gesetzliche Formel für den Querschnitt gibt es nicht; die Bemessung erfolgt nach der technischen Norm DIN EN 13384. Rechtlich geregelt ist vor allem die Lage der Mündung (§ 19 der 1. BImSchV, siehe unten).

## Beispiel mit den Vorgabewerten

**Empfohlener Innendurchmesser:** 150 mm
- Leistung: 8 kW
- Höhe: 8 m

## Grenzen

Dies ist nur eine grobe Orientierung. Die verbindliche Dimensionierung erfolgt nach DIN EN 13384 durch Ihren Schornsteinfeger oder einen Fachbetrieb und ist Voraussetzung für die Abnahme.

## Quellen

- [1. BImSchV § 19 – Ableitbedingungen](https://www.gesetze-im-internet.de/bimschv_1_2010/__19.html)
- [1. BImSchV § 4 – Betrieb fester Brennstoffe](https://www.gesetze-im-internet.de/bimschv_1_2010/__4.html)
- [1. BImSchV § 26 – Bestehende Einzelraumfeuerungen](https://www.gesetze-im-internet.de/bimschv_1_2010/__26.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
