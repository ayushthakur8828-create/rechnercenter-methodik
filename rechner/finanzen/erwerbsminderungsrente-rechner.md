# Erwerbsminderungsrente-Rechner

Live: https://rechnercenter.de/erwerbsminderungsrente-rechner

Volle oder teilweise EM-Rente aus Entgeltpunkten, Alter und Zurechnungszeit schätzen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Bisherige Entgeltpunkte | Punkte | 25 |
| Aktuelles Alter | Jahre | 50 |
| Art der Erwerbsminderung |  | Volle EM (unter 3 Std./Tag arbeitsfähig) |

## Berechnung

Der Rechner nutzt die Rentenformel des § 64 SGB VI:
Zurechnungspunkte = (66,25 − Alter) × Entgeltpunkte ÷ (Alter − 20)
Brutto = (Entgeltpunkte + Zurechnungspunkte) × 0,892 × Rentenartfaktor × 42,52 €
Netto, vor Steuern = Brutto × (1 − 0,1235)
Der Rentenartfaktor beträgt 1,0 (voll) oder 0,5 (teilweise; § 67). Der Zugangsfaktor 0,892 entspricht dem Höchstabschlag von 10,8 % (§ 77). 66,25 sind 66 Jahre und 3 Monate, das Ende der Zurechnungszeit bei Rentenbeginn 2026 (§ 253a). Als Punkteschnitt gelten Ihre Entgeltpunkte geteilt durch die Jahre seit dem 20. Lebensjahr; was ein Gehalt an Punkten bringt, zeigt der Rentenpunkte-Rechner. Die Pauschale von 12,35 % entspricht 7,3 % (Hälfte des allgemeinen Satzes von 14,6 %), 1,45 % (Hälfte des durchschnittlichen Zusatzbeitrags von 2,9 %) und 3,6 % Pflegeversicherung, die Rentner allein tragen.

## Beispiel mit den Vorgabewerten

**Volle EM-Rente (ca.):** 1.281,27 €
- Bruttorente: 1.461,8
- Zurechnungszeit (Punkte): 13,54
- KV-/PV-Abzug: 180,53

## Grenzen

Grobe Schätzung (Rentenwert 42,52 € seit Juli 2026, maximaler Abschlag, pauschale Abzüge). Verbindlich rechnet die Deutsche Rentenversicherung. Keine Rechtsberatung.

## Quellen

- [§ 43 SGB VI – Rente wegen Erwerbsminderung](https://www.gesetze-im-internet.de/sgb_6/__43.html)
- [§ 253a SGB VI – Zurechnungszeit](https://www.gesetze-im-internet.de/sgb_6/__253a.html)
- [§ 77 SGB VI – Zugangsfaktor](https://www.gesetze-im-internet.de/sgb_6/__77.html)
- [§ 96a SGB VI – Hinzuverdienst](https://www.gesetze-im-internet.de/sgb_6/__96a.html)
- [Deutsche Rentenversicherung: Rentenanpassung 2026](https://www.deutsche-rentenversicherung.de/DRV/DE/Ueber-uns-und-Presse/Presse/Meldungen/2026/260612-rentenanpassung-2026-bundesrat)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
