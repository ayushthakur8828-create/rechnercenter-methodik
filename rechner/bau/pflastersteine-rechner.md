# Pflastersteine-Rechner

Live: https://rechnercenter.de/pflastersteine-rechner

Pflastermenge und Kosten.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Zu pflasternde Fläche | m² | 30 |
| Steine je m² | Stück/m² | 50 |
| Arbeitsgänge | x | 1 |
| Verschnitt und Reserve | % | 8 |
| Steine je Palette | Stück | 480 |
| Preis je Palette | € | 320 |

## Berechnung

Steine pro m² = 10.000 ÷ (Länge × Breite in cm)
Bedarf = Fläche × Steine pro m² × (1 + Verschnitt)
Danach rundet der Rechner auf ganze Paletten auf. Die genaue Stückzahl pro m² steht meist im Datenblatt des Herstellers; dort sind die Fugen schon eingerechnet.

## Beispiel mit den Vorgabewerten

**Materialkosten:** 1.280 €
- Materialbedarf ohne Reserve: 1.500 Steine
- Mit 8 % Verschnitt: 1.620 Steine
- Zu kaufende Paletten: 4 Paletten
- Tatsächlich gekaufte Menge: 1.920 Steine
- Rest nach der Arbeit: 300 Steine
- Kosten je m²: 42,67 €

## Grenzen

Das Ergebnis beruht allein auf Ihren Eingaben. Keine Rechts-, Steuer-, Finanz- oder medizinische Beratung.

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
