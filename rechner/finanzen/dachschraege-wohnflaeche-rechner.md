# Dachschräge-Wohnfläche-Rechner

Live: https://rechnercenter.de/dachschraege-wohnflaeche-rechner

Anrechenbare Wohnfläche unter Dachschrägen nach der Wohnflächenverordnung.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Schrägen im Raum |  | Zwei symmetrische Dachschrägen |
| Raumlänge parallel zum First | m | 5 |
| Bodenbreite quer zur Schräge | m | 6 |
| Lichte Höhe am Kniestock | m | 0,5 |
| Dachneigung | ° | 45 |

## Berechnung

Der Rechner bestimmt, an welcher Stelle die Schräge die Höhen 1 m und 2 m erreicht. Bei einer Dachneigung α und einem Kniestock k liegt diese Stelle im Abstand
x = (Höhe − k) ÷ tan α
Wohnfläche = Fläche ab 2 m + ½ × Fläche zwischen 1 m und 2 m
von der Außenwand. Bei zwei Schrägen geschieht das auf beiden Seiten; die Bodenbreite wird dazu halbiert. Der Kniestock ist die senkrechte Wand, an der die Schräge beginnt. Je höher er ist, desto weniger Fläche liegt unter 1 m.
Gemessen wird die lichte Höhe vom fertigen Fußboden bis zur fertigen Decke, also mit Bodenbelag und Verkleidung.

## Beispiel mit den Vorgabewerten

**Anrechenbare Wohnfläche:** 20 m²
- Bodengrundfläche: 30 m²
- Unter 1 m – nicht angerechnet: 5 m²
- 1 bis unter 2 m – Grundfläche: 10 m²
- Davon angerechnet (50 %): 5 m²
- Ab 2 m – vollständig: 15 m²
- Abzug gegenüber Bodenfläche: 10 m²
- Rechnerische Firsthöhe: 3,5 m

## Grenzen

Nur rechteckige Räume mit einer geraden einseitigen oder zwei symmetrischen Schrägen; keine Gauben, Kehlbalken, ungleichen Seiten, Treppen, Pfeiler, Bekleidungen oder Sonderregeln.

## Quellen

- [§ 4 WoFlV – Anrechnung der Grundflächen](https://www.gesetze-im-internet.de/woflv/__4.html)
- [§ 1 WoFlV – Anwendungsbereich](https://www.gesetze-im-internet.de/woflv/__1.html)
- [§ 2 WoFlV – Zur Wohnfläche gehörende Grundflächen](https://www.gesetze-im-internet.de/woflv/__2.html)
- [Berliner Mieterverein – BGH, Urteil vom 24. März 2004, VIII ZR 133/03](https://www.berliner-mieterverein.de/recht/bgh/bgh0415.htm)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
