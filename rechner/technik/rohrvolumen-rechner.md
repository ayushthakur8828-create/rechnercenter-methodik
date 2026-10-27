# Rohrvolumen-Rechner

Live: https://rechnercenter.de/rohrvolumen-rechner

Liter im Rohr aus Innendurchmesser, Länge und Füllgrad berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Innendurchmesser | mm | 100 |
| Rohrlänge | m | 10 |
| Füllgrad | % | 100 |

## Berechnung

A = π · d² / 4 (d in m)
V = A · L (in m³) · 1.000 = Liter
Liter pro Meter = A · 1.000
Inhalt bei Füllgrad = V · Füllgrad / 100
Der Rechner wandelt den eingegebenen Innendurchmesser von Millimetern in Meter um, berechnet die Kreisfläche und multipliziert sie mit der Länge. Das ist gleichwertig mit π · r² · L, denn r = d / 2. Ein Kubikmeter entspricht 1.000 Litern; der Liter ist nach der Einheitenverordnung eine gesetzliche Einheit für das Volumen.
Der Füllgrad ist ein volumetrischer Anteil: 50 % bedeutet die Hälfte des Rohrinhalts. Er ist nicht gleichbedeutend mit der Füllhöhe – bei einem liegenden Rohr entspricht ein Wasserstand auf halber Höhe zwar 50 %, bei anderen Höhen aber nicht linear. Biegungen ändern das Ergebnis nicht, solange Länge und Querschnitt gleich bleiben.

## Beispiel mit den Vorgabewerten

**Rohrinhalt:** 78,54 Liter
- Volumen bei 100 %: 78,54 Liter
- Liter pro Meter: 7,854 l/m
- Innenquerschnitt: 7.853,982 mm²
- Volumen in m³: 0,07854 m³
- Innenradius: 50 mm

## Grenzen

Nur zylindrischer, über die Länge gleichbleibender Innenquerschnitt; keine Armaturen, Einbauten, Verformung, Wandstärke oder ungleichmäßige Teilfüllung.

## Quellen

- [Einheitenverordnung (EinhV) – Gesetzliche Einheiten](https://www.gesetze-im-internet.de/einhv/__1.html)
- [Einheitenverordnung – Volltext mit Anlage (Liter als Volumeneinheit)](https://www.gesetze-im-internet.de/einhv/BJNR022720985.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
