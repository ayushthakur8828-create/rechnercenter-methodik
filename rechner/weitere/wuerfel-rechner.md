# Würfel-Rechner

Live: https://rechnercenter.de/wuerfel-rechner

Volumen, Oberfläche und Raumdiagonale eines Würfels aus der Kante.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Kantenlänge (a) | cm | 5 |

## Berechnung

V = a · a · a = a³
O = 6 · a²
d = a · √2 (Flächendiagonale)
D = a · √3 (Raumdiagonale)
Das Volumen entsteht, weil Länge, Breite und Höhe identisch sind: Statt l · b · h wie beim Quader rechnet man dreimal a. Die Oberfläche ist die Summe der sechs Seitenquadrate mit je a².
Die Raumdiagonale verbindet zwei gegenüberliegende Ecken quer durch den Körper. Sie folgt aus zweimaligem Anwenden des Satzes des Pythagoras: Zuerst die Diagonale der Grundfläche, d² = a² + a² = 2a². Diese bildet mit einer senkrechten Kante ein rechtwinkliges Dreieck, also D² = 2a² + a² = 3a² und damit D = a · √3 ≈ 1,732 · a. Die Flächendiagonale a · √2 ≈ 1,414 · a zeigt der Rechner nicht an, sie lässt sich aber leicht ergänzen.

## Beispiel mit den Vorgabewerten

**Volumen:** 125 cm³
- Oberfläche: 150 cm²
- Raumdiagonale: 8,66 cm

## Quellen

- [Einheitenverordnung (EinhV)](https://www.gesetze-im-internet.de/einhv/)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
