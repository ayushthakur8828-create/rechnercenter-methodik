# Elektroauto-Kosten-Rechner

Live: https://rechnercenter.de/elektroauto-kosten-rechner

Energiekosten von E-Auto und Benziner pro 100 km und pro Jahr vergleichen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Verbrauch E-Auto | kWh/100 km | 18 |
| Strompreis (Lade-Mix) | ct/kWh | 30 |
| Verbrauch Vergleichs-Benziner | l/100 km | 7 |
| Benzinpreis | €/l | 1,75 |
| Jahresfahrleistung | km | 15.000 |

## Berechnung

Kosten je 100 km = Verbrauch × Preis
Jahreskosten = Kosten je 100 km × Jahreskilometer ÷ 100
Beispiel: 18 kWh × 0,30 € = 5,40 €; × 150 = 810 € Strom im Jahr. 7 l × 1,75 € = 12,25 €; × 150 = 1.837,50 € Benzin. Differenz: 1.027,50 €.

## Beispiel mit den Vorgabewerten

**Ersparnis mit E-Auto:** 1.027,5 €
- Stromkosten/Jahr: 810
- Benzinkosten/Jahr: 1.837,5

## Grenzen

Nur Energiekosten. Nicht enthalten: Anschaffungspreis, Wertverlust, Ladeverluste (real 10–20 %), Unterschied zwischen Haushalts- und Schnellladepreis, THG-Prämie, Kfz-Steuerbefreiung, Versicherung und Wartung

## Quellen

- [§ 3d KraftStG – Steuerbefreiung für Elektrofahrzeuge](https://www.gesetze-im-internet.de/kraftstg/__3d.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
