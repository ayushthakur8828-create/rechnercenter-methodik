# Tilgungsrechner

Live: https://rechnercenter.de/tilgungsrechner

Monatsrate, Restschuld und Volltilgungsdauer eines Annuitätendarlehens.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Darlehenssumme | € | 300.000 |
| Sollzins | % p. a. | 3,5 |
| Anfängliche Tilgung | % p. a. | 2 |
| Zinsbindung | Jahre | 10 |

## Berechnung

Monatsrate = Darlehenssumme × (Sollzins + anfängliche Tilgung) ÷ 100 ÷ 12
Zinsanteil im Monat = Restschuld × Sollzins ÷ 100 ÷ 12
Tilgungsanteil = Monatsrate − Zinsanteil
neue Restschuld = alte Restschuld − Tilgungsanteil
Der Rechner wiederholt diese Schritte Monat für Monat über die gesamte Zinsbindung und summiert dabei die Zinsen. Die Volltilgungsdauer bestimmt er mit der Annuitätenformel n = ln(Rate ÷ (Rate − Darlehen × i)) ÷ ln(1 + i), wobei i der Monatszins ist. Die Annahme dahinter: Auch nach Ende der Zinsbindung bleibt der Zins unverändert – in der Praxis wird er neu verhandelt.
Rechtlich wichtig ist § 489 BGB: Bei gebundenem Sollzins können Sie den Vertrag in jedem Fall zehn Jahre nach vollständigem Empfang des Darlehens mit sechs Monaten Frist kündigen. § 500 Abs. 2 BGB regelt, dass vorzeitige Rückzahlungen bei Immobiliar-Verbraucherdarlehen mit gebundenem Sollzins während der Zinsbindung nur bei berechtigtem Interesse möglich sind.

## Beispiel mit den Vorgabewerten

**Monatliche Rate:** 1.375 €
- Restschuld nach Zinsbindung: 228.283,74
- Gezahlte Zinsen (Zinsbindung): 93.283,74
- Getilgt: 71.716,26

## Grenzen

Keine Sondertilgungen, keine Bereitstellungszinsen bei verzögertem Abruf und keine Aussage über den Anschlusszins nach Ablauf der Bindung – genau dort liegt das größte Risiko der Finanzierung

## Quellen

- [§ 489 BGB – Ordentliches Kündigungsrecht des Darlehensnehmers](https://www.gesetze-im-internet.de/bgb/__489.html)
- [§ 500 BGB – Vorzeitige Rückzahlung](https://www.gesetze-im-internet.de/bgb/__500.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
