# Hausabriss-Kosten-Rechner

Live: https://rechnercenter.de/hausabriss-kosten-rechner

Abrisskosten eines Hauses aus umbautem Raum, Keller, Entsorgung und Schadstoffen schätzen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Umbauter Raum des Gebäudes | m³ | 600 |
| Abbruchpreis je m³ | € | 40 |
| Keller vorhanden |  | Ja – Ausbau und Verfüllung nötig |
| Kellerausbau und Verfüllung | € | 6.000 |
| Schadstoffe |  | Keine bekannt |
| Entsorgung und Container | € | 5.000 |
| Genehmigung, Statik, Absperrung | € | 1.500 |

## Berechnung

Abbruch = umbauter Raum × Preis je m³ × Schadstoffzuschlag
Gesamt = Abbruch + Keller + Entsorgung + Nebenkosten
Den Preis je m³ und die übrigen Werte entnehmen Sie Angeboten von Abbruchunternehmen. Der Rechner rechnet bei künstlichen Mineralfasern mit 30 % und bei Asbest mit 80 % Zuschlag auf den Abbruch; das sind grobe Annahmen.

## Beispiel mit den Vorgabewerten

**Abbruchkosten insgesamt:** 36.500 €
- Reiner Abbruch: 24.000 €
- Schadstoffzuschlag: entfällt
- Keller: 6.000 €
- Entsorgung: 5.000 €
- Nebenkosten: 1.500 €
- Kosten je m³ umbauter Raum: 60,83 €

## Grenzen

Das Ergebnis beruht allein auf Ihren Eingaben. Keine Rechts-, Steuer-, Finanz- oder medizinische Beratung.

## Quellen

- [TRGS 519 – Asbest: Abbruch-, Sanierungs- oder Instandhaltungsarbeiten](https://www.baua.de/DE/Angebote/Regelwerk/TRGS/TRGS-519.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
