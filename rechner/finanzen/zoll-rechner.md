# Zoll Rechner für Bestellungen

Live: https://rechnercenter.de/zoll-rechner

Zoll und Einfuhrumsatzsteuer für Bestellungen aus Nicht-EU-Staaten schätzen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Warenwert | € | 200 |
| Versand und Versicherung | € | 20 |
| Zollsatz laut Zolltarif | % | 4 |
| Verschiedene Warenarten (Tarifpositionen) | Anzahl | 1 |
| Einfuhrumsatzsteuer |  | 19 % – regulärer Satz |

## Berechnung

Zollwert = Warenwert + Versand/Versicherung
Zoll (Sachwert bis 150 €) = 3 € × Anzahl Warenkategorien
Zoll (Sachwert über 150 €) = Zollwert × Zollsatz
EUSt = (Zollwert + Zoll) × 19 % bzw. 7 %
Einfuhrabgaben = Zoll + EUSt
Der Rechner prüft zuerst, ob der eingegebene Warenwert höchstens 150 € beträgt. Separat ausgewiesene Versandkosten zählen dabei nicht mit, fließen aber in den Zollwert ein. Bei Postsendungen rechnet der Zoll das gesamte Porto in den Zollwert, weil es nicht nach Kilometern aufgeteilt wird. Im Pauschalfall ignoriert der Rechner Ihren Zollsatz und setzt 3 € je Kategorie an. Rechtsgrundlage für die EUSt sind § 1 Abs. 1 Nr. 4 UStG (Einfuhr als steuerbarer Umsatz), § 21 UStG (Zollvorschriften gelten sinngemäß) und § 12 UStG (19 % bzw. 7 %). Der Pauschalzoll beruht laut Zoll auf der Verordnung (EU) 2026/382.

## Beispiel mit den Vorgabewerten

**Geschätzte Einfuhrabgaben:** 52,27 €
- Zollwert im Modell: 220,00 €
- Zollbetrag: 8,80 €
- Einfuhrumsatzsteuer: 43,47 €
- Gesamt inklusive Ware und Versand: 272,27 €

## Grenzen

Der Zollsatz hängt von der Warennummer des Zolltarifs ab und reicht von 0 bis über 20 % – ein pauschaler Satz ist nur eine Schätzung. Nicht abgebildet: Freigrenzen für Geschenke und Reisemitbringsel, Präferenzabkommen mit reduzierten Sätzen, Verbrauchsteuern auf Alkohol und Tabak sowie Auslagenpauschalen der Zustelldienste. Verbindlich ist die Festsetzung des Zollamts

## Quellen

- [Zoll: Internetbestellungen aus Nicht-EU-Staaten](https://www.zoll.de/DE/Privatpersonen/Postsendungen-Internetbestellungen/Sendungen-aus-einem-Nicht-EU-Staat/Zoll-und-Steuern/Internetbestellungen/internetbestellungen_node.html)
- [Zoll: Wegfall der 150-Euro-Zollfreigrenze](https://www.zoll.de/DE/Fachthemen/Zoelle/Wegfall-der-150-Euro-Zollfreigrenze/wegfall-der-150-euro-zollfreigrenze_node.html)
- [Zoll: Pressemitteilung zum 1. Juli 2026](https://www.zoll.de/SharedDocs/Pressemitteilungen/DE/Sonstiges/2026/z32_wegfall_zollfreigrenze_ab_20260701_gzd.html)
- [Zoll: Reisefreimengen](https://www.zoll.de/DE/Privatpersonen/Reisen/Rueckkehr-aus-einem-Nicht-EU-Staat/Zoll-und-Steuern/Reisefreimengen/reisefreimengen.html)
- [UStG § 21 (Einfuhrumsatzsteuer)](https://www.gesetze-im-internet.de/ustg_1980/__21.html)
- [UStG § 12 (Steuersätze)](https://www.gesetze-im-internet.de/ustg_1980/__12.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
