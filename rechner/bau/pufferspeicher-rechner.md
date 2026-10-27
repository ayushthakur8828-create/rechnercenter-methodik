# Pufferspeicher-Rechner

Live: https://rechnercenter.de/pufferspeicher-rechner

Speichervolumen eines Pufferspeichers aus Leistung, Zeit und Spreizung berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Leistung des Wärmeerzeugers | kW | 12 |
| Gewünschte Überbrückungszeit | h | 2 |
| Nutzbare Temperaturspreizung | K | 20 |
| Art der Anlage |  | Wärmepumpe – Sperrzeiten überbrücken |

## Berechnung

Energie in kWh = Leistung × Zeit
Volumen in Litern = Energie × 1.000 ÷ (1,163 × Spreizung)
12 kW × 2 h = 24 kWh; 24.000 ÷ (1,163 × 20) = 1.032 Liter. Je kleiner die nutzbare Spreizung, desto größer muss der Speicher sein.

## Beispiel mit den Vorgabewerten

**Empfohlenes Speichervolumen:** 1.500 Liter
- Zu speichernde Energie: 24 kWh
- Rechnerisches Volumen: 1.032 Liter
- Faustregel zur Gegenprobe: 240 Liter – Wärmepumpe: rund 20 l je kW Heizleistung
- Nächste gängige Baugröße: 1.500 Liter
- Gewicht gefüllt: 1.500 kg – Statik prüfen

## Grenzen

Das Ergebnis beruht allein auf Ihren Eingaben. Keine Rechts-, Steuer-, Finanz- oder medizinische Beratung.

## Quellen

- [§ 5 der 1. BImSchV – Pufferspeicher für Feuerungsanlagen](https://www.gesetze-im-internet.de/bimschv_1_2010/__5.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
