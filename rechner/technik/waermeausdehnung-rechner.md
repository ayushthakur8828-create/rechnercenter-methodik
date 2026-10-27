# Wärmeausdehnung-Rechner

Live: https://rechnercenter.de/waermeausdehnung-rechner

Längenänderung eines Bauteils durch Erwärmen oder Abkühlen berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Ausdehnungskoeffizient | µm/(m·K) | 12 |
| Ausgangslänge | m | 5 |
| Temperaturänderung | K | 60 |

## Berechnung

Der Rechner multipliziert α (in 10⁻⁶ je Kelvin) mit der Länge in Metern und der Temperaturänderung in Kelvin und rechnet das Ergebnis in Millimeter um:
ΔL [mm] = α [µm/(m·K)] × L [m] × ΔT [K] ÷ 1.000
Beispiel: 12 × 5 × 60 ÷ 1.000 = 3,6 mm. Eine negative Temperaturänderung, also Abkühlen, ergibt eine Verkürzung. Die Formel gilt für die freie Ausdehnung in einer Richtung und für übliche Temperaturbereiche, in denen α nahezu konstant ist.

## Beispiel mit den Vorgabewerten

**Freie Längenänderung:** 3,6 mm
- Neue Länge: 5,004 m
- Relative Änderung: 0,072 %

## Quellen

- [Wikipedia – Ausdehnungskoeffizient, Tabellenwerte](https://de.wikipedia.org/wiki/Ausdehnungskoeffizient)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
