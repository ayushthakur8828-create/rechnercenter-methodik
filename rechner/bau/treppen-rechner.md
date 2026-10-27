# Treppenrechner

Live: https://rechnercenter.de/treppen-rechner

Stufen, Steigung, Auftritt und Winkel einer geraden Treppe berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Geschosshöhe | cm | 280 |
| Verfügbare Lauflänge | cm | 400 |
| Nutzbare Treppenbreite | cm | 100 |

## Berechnung

h = H / n · a = L / (n − 1) · Schrittmaß = 2h + a · Winkel = arctan(H / L)
H ist die Geschosshöhe von Fertigfußboden zu Fertigfußboden, L die waagerechte Lauflänge, n die Zahl der Steigungen. Der Rechner probiert alle Teilungen von 3 bis 60 Steigungen durch und bewertet jede Variante: Je näher das Schrittmaß an 63 cm und die Steigung an 17,5 cm liegt, desto besser. Steigungen außerhalb von 14 bis 20 cm und Auftritte außerhalb von 23 bis 37 cm werden stark abgewertet. Die beste Variante wird angezeigt.
Zusätzlich gibt der Rechner die Sicherheitsregel h + a, die Bequemlichkeitsregel a − h, die Schräglänge und die Grundfläche (Lauflänge × Breite) aus. Als „im Komfortbereich“ markiert er eine Teilung nur, wenn das Schrittmaß zwischen 60 und 65 cm, die Steigung zwischen 14 und 20 cm und der Auftritt zwischen 26 und 32 cm liegt. Diese Spannen sind Orientierungswerte des Rechners, keine Grenzwerte aus einem Gesetz.
Rechtlich regeln die Landesbauordnungen, ob und wo eine Treppe nötig ist. In Bayern verlangt etwa Art. 32 BayBO für jedes nicht zu ebener Erde liegende Geschoss mindestens eine notwendige Treppe, eine für den größten zu erwartenden Verkehr ausreichende nutzbare Breite und einen festen, griffsicheren Handlauf. Konkrete Steigungs- und Auftrittsmaße nennt dieser Artikel nicht; sie ergeben sich aus technischen Regeln wie der DIN 18065. Die übrigen Länder haben eigene Bauordnungen.

## Beispiel mit den Vorgabewerten

**Vorgeschlagene Teilung:** 16 Steigungen
- Auftritte: 15 Stück
- Steigungshöhe h: 17,5 cm
- Auftrittstiefe a: 26,67 cm
- Schrittmaß 2h + a: 61,67 cm
- Sicherheitsregel h + a: 44,17 cm
- Bequemlichkeitsregel a − h: 9,17 cm
- Neigungswinkel: 35°
- Schräglänge: 488,3 cm
- Grundfläche: 4 m²

## Grenzen

Kein Nachweis nach Landesbauordnung oder DIN 18065, keine Statik, Kopfhöhe, Podeste, Geländer, Wangen oder gewendelte Stufen.

## Quellen

- [Bayerische Bauordnung, Art. 32 Treppen](https://www.gesetze-bayern.de/Content/Document/BayBO-32)
- [DIN 18065 bei DIN Media](https://www.dinmedia.de/de/norm/din-18065/322316050)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
