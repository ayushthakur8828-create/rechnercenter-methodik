# Tage-Rechner

Live: https://rechnercenter.de/tage-rechner

Kalendertage zwischen zwei Daten, mit oder ohne Endtag, plus Wochen und Monate.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Von |  | – |
| Bis |  | – |
| Zählweise |  | Reine Differenz (Endtag nicht mitzählen) |

## Berechnung

Tage = |Enddatum − Startdatum| (+ 1, wenn beide Tage mitzählen)
Wochen = Tage ÷ 7
Monate (ca.) = Tage ÷ 30,44
Beide Daten werden als Kalendertage ohne Uhrzeit behandelt. Die Differenz entsteht aus der tatsächlichen Länge der dazwischenliegenden Tage, Schaltjahre und unterschiedlich lange Monate sind also automatisch berücksichtigt. Liegt das Startdatum nach dem Enddatum, vertauscht der Rechner die Reihenfolge und nennt die Zeitspanne als positive Zahl. Wochen und Monate werden auf eine Nachkommastelle gerundet.
Das Ergebnis passt zu den Regeln des Bürgerlichen Gesetzbuchs: Nach § 187 Abs. 1 BGB wird bei einer Frist, die mit einem Ereignis beginnt, der Tag des Ereignisses nicht mitgerechnet. Nach § 188 Abs. 1 BGB endet eine nach Tagen bestimmte Frist mit Ablauf des letzten Tages. Die Einstellung „Endtag nicht mitzählen“ entspricht dem Zählen von Tag zu Tag. Die inklusive Variante ist für Zeiträume gedacht, in denen jeder Kalendertag einzeln gezählt werden soll.

## Beispiel mit den Vorgabewerten

**Anzahl Tage:** Bitte beide Daten wählen

## Grenzen

Keine automatische Auslegung rechtlicher Fristen, keine Arbeitstage und keine Uhrzeiten innerhalb eines Tages

## Quellen

- [§ 187 BGB – Fristbeginn](https://www.gesetze-im-internet.de/bgb/__187.html)
- [§ 188 BGB – Fristende](https://www.gesetze-im-internet.de/bgb/__188.html)
- [§ 191 BGB – Berechnung von Zeiträumen](https://www.gesetze-im-internet.de/bgb/__191.html)
- [§ 193 BGB – Sonn- und Feiertag](https://www.gesetze-im-internet.de/bgb/__193.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
