# Umzugskosten-Rechner

Live: https://rechnercenter.de/umzugskosten-rechner

Umzugskosten aus Wohnfläche, Entfernung, Helfern und Etagen schätzen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Wohnfläche | m² | 70 |
| Entfernung | km | 50 |
| Stundensatz je Helfer | € | 45 |
| Anzahl Helfer | Personen | 3 |
| Etage ohne Aufzug | Stockwerke | 2 |
| Einpackservice |  | Selbst packen |

## Berechnung

Volumen = Wohnfläche × 0,2 m³
Stunden = max(4; Volumen ÷ 5 × 2 ÷ Helfer + Etagen × 0,4 + Entfernung ÷ 70 km/h)
Personal = Stunden × Helfer × Stundensatz
Fahrt = 90 € + Entfernung × 1,20 €/km
Einpacken (optional) = Volumen × 18 €/m³
Spanne = (Personal + Fahrt + Einpacken) × 0,85 bis × 1,3
Der Rechner rechnet in fünf Schritten: Zuerst schätzt er das Volumen mit 0,2 m³ je Quadratmeter Wohnfläche. Daraus folgt die Lade- und Entladezeit, auf alle Helfer verteilt; jede Etage ohne Aufzug verlängert sie um 0,4 Stunden. Dazu kommt die Fahrzeit mit durchschnittlich 70 km/h, in der die Helfer mitfahren und bezahlt werden. Unter 4 Stunden rechnet das Tool nie – das bildet die übliche Mindestbuchung ab. Die Fahrtkosten bestehen aus einer festen Pauschale von 90 € und 1,20 € je eingegebenem Kilometer. Wer den Einpackservice wählt, zahlt im Modell 18 € je Kubikmeter. Zusätzlich gibt der Rechner die Zahl der Umzugskartons aus: Volumen × 2,5, aufgerundet.
Alle Faktoren sind Modellannahmen des Rechners. Eine gesetzliche Berechnungsgrundlage für private Umzugspreise gibt es nicht; die Preise vereinbaren Sie frei mit dem Umzugsunternehmen.

## Beispiel mit den Vorgabewerten

**Voraussichtliche Umzugskosten:** 587 € bis 897 €
- Geschätztes Umzugsvolumen: 14 m³
- Veranschlagte Arbeitszeit: 4 h mit 3 Helfern
- Personalkosten: 540 €
- Fahrt- und Fahrzeugkosten: 150 €
- Einpackservice: nicht gebucht
- Benötigte Umzugskartons: 35 Stück

## Grenzen

Das Ergebnis beruht allein auf Ihren Eingaben. Keine Rechts-, Steuer-, Finanz- oder medizinische Beratung.

## Quellen

- [§ 9 EStG – Werbungskosten](https://www.gesetze-im-internet.de/estg/__9.html)
- [§ 35a EStG – Haushaltsnahe Dienstleistungen und Handwerkerleistungen](https://www.gesetze-im-internet.de/estg/__35a.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
