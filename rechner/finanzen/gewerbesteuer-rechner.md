# Gewerbesteuer-Rechner

Live: https://rechnercenter.de/gewerbesteuer-rechner

Gewerbesteuer aus Gewerbeertrag und Hebesatz berechnen, mit Anrechnung auf die Einkommensteuer.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Gewerbeertrag (Gewinn) | €/Jahr | 80.000 |
| Hebesatz der Gemeinde | % | 400 |
| Rechtsform |  | Einzelunternehmen / Personengesellschaft |

## Berechnung

- Gewerbeertrag: Gewinn plus Hinzurechnungen minus Kürzungen, abgerundet auf volle 100 €.
- Freibetrag: Einzelunternehmen und Personengesellschaften ziehen 24.500 € ab, Kapitalgesellschaften nichts (§ 11 Abs. 1 GewStG).
- Steuermessbetrag: verbleibender Ertrag × 3,5 % (§ 11 Abs. 2 GewStG).
- Gewerbesteuer: Messbetrag × Hebesatz der Gemeinde.
Beispiel: 80.000 € − 24.500 € = 55.500 €; × 3,5 % = 1.942,50 € Messbetrag; × 400 % = 7.770 €.

## Beispiel mit den Vorgabewerten

**Gewerbesteuer:** 7.770 €
- Gewerbeertrag nach Freibetrag: 55.500
- Steuermessbetrag (3,5 %): 1.942,5
- ESt-Anrechnung (§ 35 EStG): 7.770

## Grenzen

Ohne Hinzurechnungen/Kürzungen (§§ 8, 9 GewStG). Keine Steuerberatung.

## Quellen

- [§ 11 GewStG – Steuermesszahl und Freibetrag](https://www.gesetze-im-internet.de/gewstg/__11.html)
- [§ 16 GewStG – Hebesatz](https://www.gesetze-im-internet.de/gewstg/__16.html)
- [§ 35 EStG – Steuerermäßigung bei gewerblichen Einkünften](https://www.gesetze-im-internet.de/estg/__35.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
