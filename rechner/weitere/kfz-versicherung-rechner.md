# Kfz-Versicherung-Rechner

Live: https://rechnercenter.de/kfz-versicherung-rechner

Kfz-Beitrag nach SF-Klasse, Typ- und Regionalklasse grob schätzen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Basisbeitrag Haftpflicht | € / Jahr | 500 |
| Gewünschter Schutz |  | Kfz-Haftpflicht |
| Schadenfreiheitsklasse |  | SF 10 |
| Typklasse |  | 15 |
| Regionalklasse |  | 6 |
| Jährliche Fahrleistung |  | bis 12.000 km |
| Jüngste fahrende Person |  | 25 Jahre oder älter |

## Berechnung

Beitrag ≈ Basisbeitrag × Schutz × SF-Faktor × Typfaktor × Regionalfaktor × km-Faktor × Altersfaktor
Der Rechner multipliziert Ihren Basisbeitrag mit sechs Faktoren und zeigt das Ergebnis als Spanne von 20 % darunter bis 20 % darüber. Die Faktoren sind Modellwerte des Rechners, keine Tarifwerte eines Versicherers:
- Schutz: Haftpflicht 1,00, mit Teilkasko 1,28, mit Vollkasko 1,65.
- Typklasse: je Klasse über 15 plus 2,5 %, darunter minus 2,5 % (mindestens 0,75).
- Regionalklasse: je Klasse über 6 plus 1,8 %, darunter minus 1,8 % (mindestens 0,78).
- Fahrleistung: von 0,82 (bis 6.000 km) bis 1,32 (über 20.000 km), 12.000 km = 1,00.
- Alter der jüngsten fahrenden Person: ab 25 Jahren 1,00, 21 bis 24 Jahre 1,25, unter 21 Jahre 1,55.

## Beispiel mit den Vorgabewerten

**Modellierte Beitragsspanne pro Jahr:** 148,00 € – 222,00 €
- Modellmitte pro Jahr: 185,00 €
- Modellmitte pro Monat: 15,42 €
- Schutzfaktor: 0 %
- SF-Modellfaktor: -63 %
- Typ / Region: 15 / 6
- Gesamtfaktor: 0,37 ×

## Grenzen

Unverbindliches Rechenmodell, keine Versicherungsberatung und kein Angebot eines Versicherers.

## Quellen

- [§ 1 PflVG – Versicherungspflicht](https://www.gesetze-im-internet.de/pflvg/__1.html)
- [Anlage zu § 4 Abs. 2 PflVG – Mindestversicherungssummen](https://www.gesetze-im-internet.de/pflvg/anlage.html)
- [§ 40 VVG – Kündigung bei Prämienerhöhung](https://www.gesetze-im-internet.de/vvg_2008/__40.html)
- [GDV – Regionalklassen-Abfrage](https://www.gdv.de/regionalklassen-abfrage)
- [ADAC – Neue Typklassen](https://www.adac.de/der-adac/aktuelles/neue-typklassen/)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
