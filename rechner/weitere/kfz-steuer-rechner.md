# Kfz-Steuer Rechner

Live: https://rechnercenter.de/kfz-steuer-rechner

Jährliche Kfz-Steuer für Pkw ab Erstzulassung 2021 aus Hubraum und CO₂.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Hubraum | cm³ | 1.600 |
| CO₂-Ausstoß | g/km | 120 |
| Kraftstoff |  | Benzin |

## Berechnung

Steuer = abgerundet( Hubraum in 100-cm³-Schritten (aufgerundet) × 2 € bzw. 9,50 € + Summe der CO₂-Stufen oberhalb von 95 g/km )
Rechtsgrundlage ist § 9 KraftStG. Der Rechner rundet den Hubraum je angefangene 100 cm³ auf, multipliziert mit dem Satz für Benzin (2 €) oder Diesel (9,50 €) und addiert den CO₂-Anteil. Beim CO₂-Anteil zählt jedes Gramm nur in seiner eigenen Stufe: Die ersten 20 g über 95 g/km kosten je 2 €, die nächsten 20 g je 2,20 € und so weiter. Es gilt also keine Rückwirkung auf die niedrigeren Stufen. Zuletzt wird nach § 11 KraftStG auf volle Euro abgerundet.
Maßgeblich für den CO₂-Wert ist laut Gesetz die Typgenehmigung nach den EU-Verordnungen 715/2007 und 2017/1151. Praktisch lesen Sie ihn aus der Zulassungsbescheinigung Teil I ab, Hubraum in Feld P.1, CO₂ in Feld V.7.

## Beispiel mit den Vorgabewerten

**Kfz-Steuer pro Jahr:** 83 €
- Hubraum-Anteil: 32
- CO₂-Anteil: 51
- Hubraum: 1600 cm³

## Grenzen

Berechnung für Pkw mit Verbrennungsmotor und Erstzulassung ab 2021. Ältere Fahrzeuge, Wankelmotoren, Oldtimer und Sonderfälle folgen anderen Regeln. Maßgeblich ist der Steuerbescheid des Hauptzollamts.

## Quellen

- [§ 9 KraftStG – Steuersätze für Pkw](https://www.gesetze-im-internet.de/kraftstg/__9.html)
- [§ 11 KraftStG – Entrichtungszeitraum und Rundung](https://www.gesetze-im-internet.de/kraftstg/__11.html)
- [§ 3d KraftStG – Befreiung für Elektrofahrzeuge](https://www.gesetze-im-internet.de/kraftstg/__3d.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
