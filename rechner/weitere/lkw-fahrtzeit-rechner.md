# Lkw-Fahrzeit-Rechner

Live: https://rechnercenter.de/lkw-fahrtzeit-rechner

Lkw-Ankunft mit 45-min-Pausen nach 4,5 h und Tagesruhe planen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Abfahrtsdatum |  | – |
| Abfahrtszeit |  | – |
| Verbleibende Strecke | km | 720 |
| Geplantes Durchschnittstempo | km/h | 75 |
| Lenkzeit seit letzter Fahrtunterbrechung | min | 0 |
| Heutige Lenkzeit vor Abfahrt | min | 0 |
| Angesetzte Tageslenkzeit |  | 9 Stunden – Regelfall |

## Berechnung

Reine Lenkzeit (min) = Strecke (km) ÷ Tempo (km/h) × 60
Gesamtdauer = Lenkzeit + Anzahl Pausen × 45 min + Anzahl Tagesruhen × 11 h
Ankunft = Abfahrt + Gesamtdauer
Der Rechner verteilt die Lenkzeit in Blöcke. Ein Block endet, sobald 4,5 Stunden (270 Minuten) seit der letzten Unterbrechung erreicht sind; dann fügt er 45 Minuten Pause ein. Erreicht die Tageslenkzeit den gewählten Wert von 9 oder 10 Stunden, setzt er stattdessen 11 Stunden Ruhe an und beginnt danach einen neuen Tag mit leerem Lenkblock. Eine Unterbrechung wird nur eingefügt, wenn danach noch Strecke übrig ist.
Bereits gefahrene Minuten werden berücksichtigt: die Lenkzeit seit der letzten Fahrtunterbrechung (höchstens 270 Minuten) und die heutige Lenkzeit insgesamt. Ist der Tageswert kleiner als der laufende Block, setzt der Rechner ihn auf den Blockwert hoch. Grundlage sind Art. 6, 7 und 8 der Verordnung (EG) Nr. 561/2006.

## Beispiel mit den Vorgabewerten

**Ankunft:** Bitte Abfahrtsdatum und -zeit eingeben

## Grenzen

Keine Prüfung des Anwendungsbereichs, der erlaubten 10-Stunden-Verlängerungen, Wochenlenkzeit, Mehrfahrerbetrieb, geteilter Pausen, Arbeitszeit, Ausnahmen, Zeitwechsel oder Tachographendaten.

## Quellen

- [Verordnung (EG) Nr. 561/2006 (konsolidiert, EUR-Lex)](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX%3A02006R0561-20240522)
- [§ 3 StVO – Geschwindigkeit](https://www.gesetze-im-internet.de/stvo_2013/__3.html)
- [§ 18 StVO – Autobahnen und Kraftfahrstraßen](https://www.gesetze-im-internet.de/stvo_2013/__18.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
