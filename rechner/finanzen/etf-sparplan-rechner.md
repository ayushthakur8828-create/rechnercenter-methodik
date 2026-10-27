# Sparplan-Rechner

Live: https://rechnercenter.de/etf-sparplan-rechner

ETF-Sparplan und ETF-Rendite durchrechnen: Endkapital mit Zinseszins.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Monatliche Sparrate | € | 200 |
| Startkapital | € | 0 |
| Anlagedauer | Jahre | 20 |
| Erwartete Rendite | % p. a. | 6 |

## Berechnung

Der Rechner rechnet die Jahresrendite in einen Monatszins um (Jahresrendite ÷ 12) und verzinst monatlich. Die Sparrate wird jeweils am Monatsende eingezahlt, das Startkapital liegt ab dem ersten Monat im Depot.
i = Rendite ÷ 100 ÷ 12, n = Jahre × 12
Endkapital = Start × (1 + i)ⁿ + Rate × ((1 + i)ⁿ − 1) ÷ i
Kursgewinn = Endkapital − (Start + Rate × n)
Bei 0 % Rendite entspricht das Endkapital einfach der Summe der Einzahlungen. Das Ergebnis ist ein Bruttowert: Fondskosten (TER), Ordergebühren, Inflation und Steuern sind nicht abgezogen. Die steuerlichen Regeln, die später greifen, stehen in § 20 und § 32d EStG sowie in §§ 18 und 20 InvStG.

## Beispiel mit den Vorgabewerten

**Endkapital (ca.):** 92.408,18 €
- Einzahlungen: 48.000
- Kursgewinn: 44.408,18

## Grenzen

Modellrechnung mit konstanter Rendite – reale Märkte schwanken. Keine Anlageberatung.

## Quellen

- [§ 20 InvStG – Teilfreistellung](https://www.gesetze-im-internet.de/invstg_2018/__20.html)
- [§ 18 InvStG – Vorabpauschale](https://www.gesetze-im-internet.de/invstg_2018/__18.html)
- [§ 2 InvStG – Begriff Aktienfonds](https://www.gesetze-im-internet.de/invstg_2018/__2.html)
- [§ 20 EStG – Sparer-Pauschbetrag](https://www.gesetze-im-internet.de/estg/__20.html)
- [§ 32d EStG – Abgeltungsteuer](https://www.gesetze-im-internet.de/estg/__32d.html)
- [§ 4 SolZG – Solidaritätszuschlag](https://www.gesetze-im-internet.de/solzg_1995/__4.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
