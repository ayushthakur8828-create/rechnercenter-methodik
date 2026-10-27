# Bremsweg-Rechner

Live: https://rechnercenter.de/bremsweg-rechner

Reaktions-, Brems- und Anhalteweg nach Faustformel und Physik.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Geschwindigkeit | km/h | 100 |
| Bremsung (Faustformel) |  | Normale Bremsung |
| Reaktionszeit (physikalisch) | s | 1 |
| Fahrbahn / Reibwert µ (physikalisch) |  | Trockener Asphalt (µ ≈ 0,8) |

## Berechnung

Der Rechner liefert zwei Rechenwege nebeneinander.
Faustformel: Reaktionsweg = (v ÷ 10) × 3
Bremsweg = (v ÷ 10)² (Gefahrenbremsung: ÷ 2)
Anhalteweg = Reaktionsweg + Bremsweg

Physikalisch: v in m/s = v in km/h ÷ 3,6
Reaktionsweg = v × Reaktionszeit
Bremsweg = v² ÷ (2 × µ × g), g = 9,81 m/s²
Bei der Faustformel steht v in km/h und das Ergebnis in Metern. Der Faktor 3 im Reaktionsweg entspricht einer Reaktionszeit von rund 1,08 Sekunden. In der physikalischen Rechnung bestimmen Sie die Reaktionszeit (0,1 bis 3 s) und den Reibwert µ zwischen Reifen und Fahrbahn selbst. Das Fahrzeuggewicht kürzt sich heraus: Bei gleichem µ bremst ein schwerer Wagen auf demselben Weg wie ein leichter. Der Rechner gibt zusätzlich die Bremsdauer und die Verzögerung µ · g aus.
Eine Rechenvorschrift für den Bremsweg enthält das Gesetz nicht. Rechtlich relevant ist § 3 Abs. 1 StVO: Es darf nur so schnell gefahren werden, dass innerhalb der übersehbaren Strecke gehalten werden kann.

## Beispiel mit den Vorgabewerten

**Anhalteweg:** 130 m
- Reaktionsweg (1 Sek.): 30 m
- Bremsweg: 100 m
- Physikalisch: Geschwindigkeit: 27,78 m/s
- Physikalisch: Reaktionsweg (1 s): 27,8 m
- Physikalisch: Bremsweg (µ = 0,8): 49,2 m
- Physikalisch: Anhalteweg: 76,9 m
- Physikalisch: Bremsdauer: 3,54 s
- Bremsverzögerung µ·g: 7,85 m/s²

## Grenzen

Idealwerte für trockene Fahrbahn, gute Reifen und aufmerksamen Fahrer. Nässe, Schnee, Laub, abgefahrene Reifen, Beladung, Gefälle und Ablenkung verlängern den Weg erheblich – bei Nässe grob um die Hälfte. Die Formeln sind Lernhilfen, keine gutachterliche Rekonstruktion

## Quellen

- [StVO § 4 – Abstand](https://www.gesetze-im-internet.de/stvo_2013/__4.html)
- [StVO § 3 – Geschwindigkeit](https://www.gesetze-im-internet.de/stvo_2013/__3.html)
- [StVO § 1 – Grundregeln](https://www.gesetze-im-internet.de/stvo_2013/__1.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
