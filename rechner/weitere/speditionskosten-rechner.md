# Speditionskosten-Rechner

Live: https://rechnercenter.de/speditionskosten-rechner

Frachtkosten für Palette, Teil- oder Komplettladung nach Entfernung schätzen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Entfernung | km | 300 |
| Gewicht | kg | 500 |
| Sendungsart |  | Einzelne Palette |

## Berechnung

Grundpreis = Pauschale + Entfernung × km-Satz + Gewicht ÷ 100 × Gewichtssatz
Spanne = Grundpreis × 0,8 bis Grundpreis × 1,3
Der Rechner verwendet je Sendungsart eigene Annahmen:
SendungsartPauschaleje kmje 100 kg
 | Einzelne Palette (Stückgut) | 65 € | 0,22 € | 4 €
 | Teilladung | 180 € | 0,85 € | 5 €
 | Komplettladung | 350 € | 1,35 € | 1 €
Diese Sätze sind Modellwerte des Rechners, keine Tarife einer Spedition. Beim Stückgut ist der Kilometersatz niedrig, weil sich viele Sendungen einen Lkw teilen; bei der Komplettladung bezahlen Sie die ganze Fahrt.

## Beispiel mit den Vorgabewerten

**Ergebnis:** 120,8 bis 196,3
- Entfernung: 300 km
- Gewicht: 500 kg

## Grenzen

Keine Maut-, Fähr- und Treibstoffzuschläge, keine Verzollung, keine Be- und Entladehilfe und keine Transportversicherung über die gesetzliche Haftung nach HGB hinaus. Tagespreise schwanken mit der Auslastung erheblich

## Quellen

- [§ 431 HGB – Haftungshöchstbetrag](https://www.gesetze-im-internet.de/hgb/__431.html)
- [Bundesregierung – Lkw-Maut mit CO₂-Aufschlag](https://www.bundesregierung.de/breg-de/aktuelles/lkw-maut-co2-2194574)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
