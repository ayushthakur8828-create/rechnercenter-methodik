# Promille-Rechner

Live: https://rechnercenter.de/promille-rechner

Blutalkohol nach der Widmark-Formel schätzen, mit Abbauzeit.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Getränkemenge | ml | 500 |
| Alkoholgehalt | Vol-% | 5 |
| Körpergewicht | kg | 75 |
| Geschlecht |  | Mann |
| Zeit seit Trinkbeginn | h | 1 |

## Berechnung

Alkohol in Gramm = Menge in ml × Vol-% ÷ 100 × 0,8
Promille = Alkohol in Gramm ÷ (Körpergewicht in kg × r)
r = 0,7 bei Männern, 0,6 bei Frauen
0,8 ist die Dichte von Alkohol in Gramm je Milliliter. Der Verteilungsfaktor r berücksichtigt, dass sich Alkohol nur im wasserhaltigen Teil des Körpers verteilt; Frauen haben im Durchschnitt einen höheren Fettanteil und deshalb einen kleineren Faktor.
Für den Abbau rechnet der Rechner vorsichtig mit 0,1 Promille pro Stunde, dem unteren Ende üblicher Angaben. So zeigt er eher zu spät als zu früh „nüchtern“ an. Den Abbau kann man weder mit Kaffee noch mit Bewegung oder frischer Luft beschleunigen.

## Beispiel mit den Vorgabewerten

**Promille (ca.):** 0,28 ‰
- Aufgenommener Alkohol: 20 g
- Anfangswert: 0,38 ‰
- Abbau in 1 h: 0,1 ‰
- Rechnerisch nüchtern nach: 3,81 h

## Grenzen

Nur eine grobe Orientierung. Der tatsächliche Wert hängt von vielen Faktoren ab (Magenfüllung, Tagesform u. a.). Fahren Sie niemals alkoholisiert – verlassen Sie sich nicht auf diese Schätzung.

## Quellen

- [§ 24a StVG – 0,5-Promille-Grenze](https://www.gesetze-im-internet.de/stvg/__24a.html)
- [§ 24c StVG – Alkoholverbot für Fahranfänger](https://www.gesetze-im-internet.de/stvg/__24c.html)
- [Bußgeldkatalog-Verordnung, Anlage (Nr. 241 und 243 ff.)](https://www.gesetze-im-internet.de/bkatv_2013/anlage.html)
- [§ 316 StGB – Trunkenheit im Verkehr](https://www.gesetze-im-internet.de/stgb/__316.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
