# Estrich-Rechner

Live: https://rechnercenter.de/estrich-rechner

Estrichmenge in Kilogramm und Säcken aus Fläche und Dicke berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Estrichfläche | m² | 30 |
| Verbrauch je cm Dicke | kg/m²/cm | 20 |
| Estrichdicke in cm | x | 5 |
| Verschnitt und Reserve | % | 5 |
| Sackgröße | kg | 40 |
| Preis je Sack | € | 6 |

## Berechnung

Menge = Fläche × Dicke in cm × Verbrauch je m² und cm × (1 + Verschnitt)
Säcke = Menge ÷ Sackgewicht, aufgerundet
Beispiel: 30 m² × 5 cm × 20 kg = 3.000 kg; mit 5 % Verschnitt 3.150 kg; bei 40 kg je Sack 79 Säcke.

## Beispiel mit den Vorgabewerten

**Materialkosten:** 474 €
- Materialbedarf ohne Reserve: 3.000 kg
- Estrichdicke in cm: 5
- Mit 5 % Verschnitt: 3.150 kg
- Zu kaufende Säcke: 79 Säcke
- Tatsächlich gekaufte Menge: 3.160 kg
- Rest nach der Arbeit: 10 kg
- Kosten je m²: 15,80 €

## Grenzen

Das Ergebnis beruht allein auf Ihren Eingaben. Keine Rechts-, Steuer-, Finanz- oder medizinische Beratung.

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
