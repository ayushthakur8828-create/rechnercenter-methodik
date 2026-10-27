# Autotransport-Kosten-Rechner

Live: https://rechnercenter.de/autotransport-kosten-rechner

Kosten für einen Autotransport nach Strecke, Fahrzeug und Transportart schätzen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Entfernung | km | 300 |
| Fahrzeugtyp |  | Limousine / Kombi |
| Transportart |  | Offen (Anhänger/Autotransporter) |

## Berechnung

Schätzwert = 120 € + Entfernung × 1,30 €/km × Fahrzeugfaktor × Transportfaktor (+ 120 € bei nicht fahrbereitem Fahrzeug), mindestens 180 €
Spanne = 80 % bis 125 % des Schätzwerts
Die Faktoren im Rechner:
- Fahrzeug: Kleinwagen 1,0 · Limousine/Kombi 1,1 · SUV/Transporter 1,3 · nicht fahrbereit 1,25 und zusätzlich 120 €
- Transportart: offen 1,0 · geschlossen 1,45
Der Kilometersatz ist linear. Dass der Preis pro Kilometer mit wachsender Strecke sinkt, liegt im Modell allein am fixen Grundbetrag, der sich auf mehr Kilometer verteilt. Mengenrabatte, Rückfahrten oder Sammeltouren rechnet der Rechner nicht ein.
Rechtlich ist ein Autotransport durch ein Unternehmen in der Regel ein Frachtvertrag nach § 407 HGB: Der Frachtführer verpflichtet sich, das Fahrzeug zum Bestimmungsort zu befördern, der Absender zahlt die vereinbarte Fracht.

## Beispiel mit den Vorgabewerten

**Ergebnis:** 439,2 bis 686,25
- Entfernung: 300 km
- ca. pro km: 1.83 €

## Grenzen

Keine Verladung nicht fahrbereiter Fahrzeuge, keine Fähr- und Mautkosten, keine Zoll- oder Ausfuhrformalitäten und keine Transportversicherung über die gesetzliche Haftung hinaus

## Quellen

- [§ 407 HGB – Frachtvertrag](https://www.gesetze-im-internet.de/hgb/__407.html)
- [§ 431 HGB – Haftungshöchstbetrag](https://www.gesetze-im-internet.de/hgb/__431.html)
- [§ 438 HGB – Schadensanzeige](https://www.gesetze-im-internet.de/hgb/__438.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
