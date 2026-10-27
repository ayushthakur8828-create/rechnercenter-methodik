# Rohrgeschwindigkeit-Rechner

Live: https://rechnercenter.de/rohrgeschwindigkeit-rechner

Mittlere Fließgeschwindigkeit aus Volumenstrom und Rohr-Innendurchmesser berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Volumenstrom | m³/h | 20 |
| Rohr-Innendurchmesser | mm | 80 |

## Berechnung

- Volumenstrom in m³/s: m³/h ÷ 3.600. 20 m³/h sind 0,005556 m³/s.
- Durchmesser in m: mm ÷ 1.000. 80 mm sind 0,08 m.
- Querschnitt: π × 0,08² ÷ 4 = 0,005027 m².
- Geschwindigkeit: 0,005556 ÷ 0,005027 = 1,105 m/s.
Das Ergebnis ist die mittlere Geschwindigkeit über den Querschnitt. In der Rohrmitte fließt das Medium schneller, an der Wand langsamer.

## Beispiel mit den Vorgabewerten

**Mittlere Fließgeschwindigkeit:** 1,105 m/s
- Rohrquerschnitt: 0,005027 m²
- Volumenstrom: 0,005556 m³/s

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
