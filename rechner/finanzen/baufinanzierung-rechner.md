# Baufinanzierung-Rechner

Live: https://rechnercenter.de/baufinanzierung-rechner

Monatsrate, Laufzeit und Zinskosten eines Annuitätendarlehens berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Darlehenssumme | € | 300.000 |
| Sollzins pro Jahr | % | 3,5 |
| Anfängliche Tilgung | % | 2 |

## Berechnung

Der Rechner bestimmt zuerst die Rate, dann den Monatszins und daraus die Zahl der Monate bis zur Restschuld null:
Rate = Darlehenssumme × (Sollzins % + Tilgung %) ÷ 100 ÷ 12
Monatszins i = Sollzins % ÷ 100 ÷ 12
Monate n = ln[Rate ÷ (Rate − Darlehenssumme × i)] ÷ ln(1 + i)
Zinskosten = Rate × n − Darlehenssumme
Rechtsgrundlage ist der Darlehensvertrag nach § 488 BGB: Der Darlehensnehmer ist verpflichtet, den geschuldeten Zins zu zahlen und das Darlehen bei Fälligkeit zurückzuzahlen (Abs. 1). Ohne andere Vereinbarung sind Zinsen jährlich zu entrichten (Abs. 2); der Rechner unterstellt dagegen monatliche Zahlung und Verzinsung mit einem Zwölftel des Jahreszinses. Laufzeit in Jahren: n ÷ 12, auf eine Dezimalstelle gerundet.

## Beispiel mit den Vorgabewerten

**Monatliche Rate:** 1.375 €
- Laufzeit (ca.): 28,9 Jahre
- Zinskosten gesamt (ca.): 177.592,71
- Gesamtkosten (ca.): 477.592,71

## Grenzen

Vereinfachte Berechnung ohne Sondertilgungen, Zinsbindungsende oder Gebühren. Nach Ablauf der Zinsbindung kann eine Anschlussfinanzierung nötig werden. Keine Finanzberatung.

## Quellen

- [Bundesbank – Wohnungsbaukredite an private Haushalte (Zinsstatistik, Neugeschäft)](https://www.bundesbank.de/de/statistiken/geld-und-kapitalmaerkte/zinssaetze-und-renditen/wohnungsbaukredite-an-private-haushalte-hypothekarkredite-auf-wohngrundstuecke-615036)
- [§ 488 BGB – Vertragstypische Pflichten beim Darlehensvertrag](https://www.gesetze-im-internet.de/bgb/__488.html)
- [§ 489 BGB – Ordentliches Kündigungsrecht des Darlehensnehmers](https://www.gesetze-im-internet.de/bgb/__489.html)
- [§ 500 BGB – Kündigungsrecht des Darlehensnehmers; vorzeitige Rückzahlung](https://www.gesetze-im-internet.de/bgb/__500.html)
- [§ 502 BGB – Vorfälligkeitsentschädigung](https://www.gesetze-im-internet.de/bgb/__502.html)
- [§ 16 PAngV – Verbraucherdarlehen (effektiver Jahreszins)](https://www.gesetze-im-internet.de/pangv_2022/__16.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
