# Spachtelmasse-Rechner

Live: https://rechnercenter.de/spachtelmasse-rechner

Spachtelmasse in Säcken.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Zu spachtelnde Fläche | m² | 40 |
| Verbrauch je mm Schichtdicke | kg/m²/mm | 1,2 |
| Schichtdicke in mm | x | 2 |
| Verschnitt und Reserve | % | 10 |
| Sackgröße | kg | 25 |
| Preis je Sack | € | 18 |

## Berechnung

Bedarf (kg) = Fläche (m²) × Verbrauch (kg/m² je mm) × Schichtdicke (mm) × (1 + Reserve)
Danach teilt der Rechner durch die Sackgröße und rundet auf ganze Säcke auf. Den Verbrauch finden Sie auf dem Sack oder im technischen Merkblatt des Herstellers; die Voreinstellung von 1,2 kg ist nur ein Mittelwert.

## Beispiel mit den Vorgabewerten

**Materialkosten:** 90 €
- Materialbedarf ohne Reserve: 96 kg
- Schichtdicke in mm: 2
- Mit 10 % Verschnitt: 105,6 kg
- Zu kaufende Säcke: 5 Säcke
- Tatsächlich gekaufte Menge: 125 kg
- Rest nach der Arbeit: 19,4 kg
- Kosten je m²: 2,25 €

## Grenzen

Das Ergebnis beruht allein auf Ihren Eingaben. Keine Rechts-, Steuer-, Finanz- oder medizinische Beratung.

## Quellen

- [Bostik SL G905 Alpha ST – Produktdaten (Gipsspachtel, ca. 1,0 kg/m² je mm)](https://www.bostik.com/germany/de/catalog/product/construction/emea/germany/product-sl-g905-alpha-st/)
- [Strasser BS35S – Technisches Merkblatt (ca. 1,6 kg/m² je mm)](https://media.sievert.de/files/TM/TM_STRASSER-BS35S__SDE__AIN__V16.pdf)
- [IGG-Merkblatt 2: Verspachtelung von Gipsplatten – Oberflächengüten](https://media.siniat.de/pi52362/original/446996995/igg-merkblatt-2---verspachtelung-von-gipsplatten---oberflachengute.pdf)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
