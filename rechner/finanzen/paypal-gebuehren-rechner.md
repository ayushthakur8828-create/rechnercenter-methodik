# PayPal-Gebühren-Rechner

Live: https://rechnercenter.de/paypal-gebuehren-rechner

PayPal-Gebühr, Gutschrift und nötigen Rechnungsbetrag in Sekunden berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Zahlungsbetrag | € | 100 |
| Zahlungsart |  | Waren & Dienstleistungen (Inland: 2,49 % + 0,35 €) |

## Berechnung

Gebühr = Betrag × Prozentsatz + Festgebühr
Gutschrift = Betrag − Gebühr
Nötiger Rechnungsbetrag = (Wunschbetrag + Festgebühr) ÷ (1 − Prozentsatz)
Der Rechner kennt vier Zahlungsarten: Waren und Dienstleistungen (2,49 % + 0,35 €), Mikrozahlungen (4,99 % + 0,09 €), Spenden (2,49 % + 0,35 €) sowie Freunde und Familie (0 €). Die dritte Formel löst die Frage, wie viel Sie verlangen müssen, damit nach Abzug genau der eingegebene Betrag übrig bleibt. Ein einfaches Aufschlagen von 2,49 % reicht dafür nicht, weil die Gebühr auch auf den Aufschlag selbst anfällt.
Eine gesetzliche Grundlage gibt es für diese Werte nicht: Es handelt sich um Vertragskonditionen von PayPal, die auf den offiziellen Gebührenseiten veröffentlicht werden und sich ändern können.

## Beispiel mit den Vorgabewerten

**PayPal-Gebühr:** 2,84 €
- Gutschrift nach Gebühr: 97,16
- Nötiger Rechnungsbetrag für volles Netto: 102,91

## Grenzen

Keine Währungsumrechnungsgebühr bei Fremdwährungen, kein Micropayment-Tarif für Kleinbeträge und keine individuell verhandelten Händlerkonditionen. Gebührensätze ändern sich; maßgeblich ist die aktuelle Preisliste des Anbieters

## Quellen

- [PayPal – Gebühren für Händler (Deutschland)](https://www.paypal.com/de/business/paypal-business-fees)
- [PayPal – Gebühren für Privatkunden (Deutschland)](https://www.paypal.com/de/digital-wallet/paypal-consumer-fees)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
