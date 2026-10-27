# Hallenbau-Kosten-Rechner

Live: https://rechnercenter.de/hallenbau-kosten-rechner

Kostenrahmen für Leichtbau-, Kalt- und Warmhallen nach Grundfläche.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Grundfläche | m² | 500 |
| Hallen-Typ |  | Kalthalle Stahlbau (Lagerhalle, ungedämmt) |

## Berechnung

Basis = Grundfläche × Richtpreis je m² (Leichtbau 150 €, Kalthalle 350 €, Warmhalle 850 €)
Untergrenze = Basis × 0,8 · Obergrenze = Basis × 1,3
Die Grundfläche kann zwischen 50 und 10.000 m² liegen. Der Rechner multipliziert sie mit dem Richtpreis des gewählten Hallentyps und gibt eine Spanne von 80 % bis 130 % dieses Basiswerts aus. Die breite Spanne spiegelt, wie stark Hallenpreise von Spannweite, Höhe, Schneelastzone, Bodenbelastung und Ausstattung abhängen.
Zusätzlich teilt der Rechner den Basiswert in einem Diagramm fest auf: 20 % Bodenplatte und Fundament, 45 % Stahlkonstruktion, 35 % Dach und Wandverkleidung. Diese Aufteilung ist für alle Hallentypen gleich und dient nur der Veranschaulichung. Eine gesetzliche Formel für Baukosten gibt es nicht.

## Beispiel mit den Vorgabewerten

**Ergebnis:** 140.000 bis 227.500
- Richtpreis pro m²: 350 €

## Quellen

- [Bayerische Bauordnung, Art. 55 (Genehmigungspflicht)](https://www.gesetze-bayern.de/Content/Document/BayBO-55)
- [Bayerische Bauordnung, Art. 57 (verfahrensfreie Vorhaben)](https://www.gesetze-bayern.de/Content/Document/BayBO-57)
- [§ 7 EStG (Absetzung für Abnutzung)](https://www.gesetze-im-internet.de/estg/__7.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
