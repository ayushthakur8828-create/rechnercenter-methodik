# Dachziegel-Rechner

Live: https://rechnercenter.de/dachziegel-rechner

Dachziegel-Bedarf, Paletten und Materialkosten berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Dachfläche | m² | 80 |
| Ziegel je m² | Stück/m² | 12 |
| Arbeitsgänge | x | 1 |
| Verschnitt und Reserve | % | 5 |
| Ziegel je Palette | Stück | 240 |
| Preis je Palette | € | 420 |

## Berechnung

Bedarf = Fläche × Ziegel/m² · mit Reserve = Bedarf × (1 + Verschnitt / 100) · Paletten = aufrunden(mit Reserve / Ziegel je Palette) · Kosten = Paletten × Palettenpreis
Der Rechner multipliziert die eingegebene Dachfläche mit dem Verbrauch je Quadratmeter. Auf dieses Nettoergebnis wird der Verschnitt in Prozent aufgeschlagen. Anschließend wird auf volle Paletten aufgerundet, Teilpaletten berücksichtigt er nicht. Daraus folgen die tatsächlich gekaufte Menge, der Rest nach der Arbeit und die Kosten je m² Dachfläche.
Für den Ziegelbedarf gibt es keine gesetzliche Formel. Alle Werte – Verbrauch, Palettengröße, Preis – sind Annahmen, die Sie durch Herstellerangaben und ein konkretes Angebot ersetzen sollten. Die Voreinstellungen (12 Stück/m², 240 Stück je Palette, 420 € je Palette, 5 % Verschnitt) sind Beispielwerte des Rechners, keine Marktpreise.

## Beispiel mit den Vorgabewerten

**Materialkosten:** 2.100 €
- Materialbedarf ohne Reserve: 960 Ziegel
- Mit 5 % Verschnitt: 1.008 Ziegel
- Zu kaufende Paletten: 5 Paletten
- Tatsächlich gekaufte Menge: 1.200 Ziegel
- Rest nach der Arbeit: 192 Ziegel
- Kosten je m²: 26,25 €

## Grenzen

Das Ergebnis beruht allein auf Ihren Eingaben. Keine Rechts-, Steuer-, Finanz- oder medizinische Beratung.

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
