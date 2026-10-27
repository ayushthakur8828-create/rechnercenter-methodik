# Heizkosten-Rechner

Live: https://rechnercenter.de/heizkosten-rechner

Jährliche Heizkosten aus Fläche, Verbrauch je m² und Energiepreis schätzen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Wohnfläche | m² | 90 |
| Verbrauch je m² | kWh/m²·a | 130 |
| Energieträger |  | Erdgas |
| Eigener Energiepreis (optional) | ct/kWh | – |

## Berechnung

Der Rechner multipliziert Fläche und Verbrauch zum Energiebedarf und diesen mit dem Energiepreis. Tragen Sie Ihren Arbeitspreis von der Rechnung ein, rechnet er damit. Ohne Eingabe nutzt er Annahmen je Energieträger:
EnergieträgerAnnahme im Rechner
 | Erdgas | 12 ct/kWh (BDEW August 2026: 11,93 ct)
 | Heizöl | 12 ct/kWh
 | Holzpellets | 8 ct/kWh
 | Fernwärme | 13 ct/kWh
 | Strom (Direktheizung) | 30 ct/kWh
Außer beim Gas sind das grobe Annahmen. Preise unterscheiden sich stark nach Anbieter, Vertrag und Region; der eigene Arbeitspreis ist deshalb immer genauer. Grundpreise, Wartung und Messdienst sind nicht enthalten.

## Beispiel mit den Vorgabewerten

**Heizkosten pro Jahr:** 1.404 €
- Energiebedarf: 11.700 kWh/Jahr
- Pro Monat: 117
- Pro m²: 15,60 €

## Grenzen

Keine individuelle Gebäudedämmung, Lage der Wohnung im Haus, Geschosshöhe oder Nutzerverhalten. Keine Aufteilung nach Heizkostenverordnung (50–70 % Verbrauch, Rest Fläche) und keine Grund- oder Wartungskosten der Anlage

## Quellen

- [BDEW – Gaspreisanalyse (August 2026)](https://www.bdew.de/service/daten-und-grafiken/bdew-gaspreisanalyse/)
- [§ 7 HeizkostenV – Verteilung der Kosten](https://www.gesetze-im-internet.de/heizkostenv/__7.html)
- [§ 12 HeizkostenV – Kürzungsrecht](https://www.gesetze-im-internet.de/heizkostenv/__12.html)
- [Kohlendioxidkostenaufteilungsgesetz (CO2KostAufG)](https://www.gesetze-im-internet.de/co2kostaufg/)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
