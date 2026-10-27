# Taxikosten-Rechner

Live: https://rechnercenter.de/taxikosten-rechner

Taxipreis nach amtlichem Tarif für Berlin, Hamburg und München berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Amtlicher Stadttarif |  | Berlin – Stand 1. Juli 2026 |
| Gefahrene Strecke | km | 10 |
| Berechnete Wartezeit | min | 0 |
| Großraumzuschlag |  | Nein |
| Weitere vereinbarte Zuschläge | € | 0 |

## Berechnung

Fahrpreis = Grundpreis + Kilometer je Tarifstufe × Kilometerpreis + Wartezeit in Minuten ÷ 60 × Stundensatz + Zuschläge
Beispiel Berlin, 10 km: 4,30 € + 3 × 2,80 € + 4 × 2,60 € + 3 × 2,10 € = 4,30 + 8,40 + 10,40 + 6,30 = 29,40 €. Das Taxameter rechnet in kleinen Schritten, sogenannten Schalteinheiten; deshalb kann der Endpreis um einige Cent abweichen.

## Beispiel mit den Vorgabewerten

**Geschätzter Taxameterpreis in Berlin:** 29,40 €
- Grundpreis: 4,30 €
- Streckenpreis: 25,10 €
- Wartezeit: 0,00 €
- Großraum / weitere Zuschläge: 0,00 €
- Tarifstand: 1. Juli 2026

## Grenzen

Taxameter-Schalteinheiten, tatsächlich gefahrene Route, Umschaltgeschwindigkeit, Festpreisvereinbarungen, Sonderfahrten und unbekannte Zuschläge können abweichen.

## Quellen

- [§ 51 PBefG – Beförderungsentgelte im Taxenverkehr](https://www.gesetze-im-internet.de/pbefg/__51.html)
- [Taxi Times – Hamburger Taxitarif](https://taxi-times.com/hamburg-fixe-festpreise-und-grosse-aenderungen-beim-taxitarif/)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
