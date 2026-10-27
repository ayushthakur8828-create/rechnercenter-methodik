# Verzugszinsen-Rechner 2026

Live: https://rechnercenter.de/verzugszinsen-rechner

Verzugszinsen taggenau mit Basiszinssatz 2026 und § 288 BGB berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Offene Hauptforderung | € | 5.000 |
| Erster Verzugstag |  | – |
| Berechnung bis einschließlich |  | – |
| Art der Forderung |  | Verbraucher beteiligt: Basiszins + 5 Punkte |
| 40-€-Pauschale bei B2B mit einrechnen |  | false |

## Berechnung

Der Rechner zerlegt den Zeitraum vom ersten Verzugstag bis zum gewählten Enddatum (einschließlich) in Abschnitte mit jeweils gleichem Basiszinssatz. Für jeden Abschnitt gilt:
Zinsen = Hauptforderung × (Basiszinssatz + 5 bzw. 9 Prozentpunkte) ÷ 100 × Tage ÷ Tage des Kalenderjahres
Gerechnet wird mit tatsächlichen Kalendertagen; im Schaltjahr teilt der Rechner durch 366. Die Teilbeträge werden addiert. Es handelt sich um einfache Zinsen ohne Zinseszins, denn nach § 289 BGB sind von Zinsen keine Verzugszinsen zu entrichten. Der Basiszinssatz ändert sich nach § 247 BGB jeweils zum 1. Januar und 1. Juli; die Bundesbank veröffentlicht den neuen Wert im Bundesanzeiger. Hinterlegt sind die Sätze vom 1. Januar 2023 bis 31. Dezember 2026.

## Grenzen

Rechenhilfe nach den veröffentlichten Basiszinssätzen und § 288 BGB. Der Eintritt des Verzugs und Sonderregeln werden nicht rechtlich geprüft.

## Quellen

- [§ 288 BGB – Verzugszinsen und sonstiger Verzugsschaden](https://www.gesetze-im-internet.de/bgb/__288.html)
- [§ 286 BGB – Verzug des Schuldners](https://www.gesetze-im-internet.de/bgb/__286.html)
- [§ 247 BGB – Basiszinssatz](https://www.gesetze-im-internet.de/bgb/__247.html)
- [§ 289 BGB – Zinseszinsverbot](https://www.gesetze-im-internet.de/bgb/__289.html)
- [Deutsche Bundesbank – Basiszinssatz nach § 247 BGB](https://www.bundesbank.de/de/bundesbank/organisation/agb-und-regelungen/basiszinssatz-607820)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
