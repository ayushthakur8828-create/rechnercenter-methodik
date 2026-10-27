# Pflegegrad-Rechner

Live: https://rechnercenter.de/pflegegrad-rechner

Pflegegrad aus den Punkten der sechs Begutachtungsmodule berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Modul 1 · Mobilität | Rohpunkte | 5 |
| Modul 2 · Kognitive und kommunikative Fähigkeiten | Rohpunkte | 10 |
| Modul 3 · Verhaltensweisen und psychische Problemlagen | Rohpunkte | 4 |
| Modul 4 · Selbstversorgung | Rohpunkte | 18 |
| Modul 5 · Therapiebedingte Anforderungen | Rohpunkte | 3 |
| Modul 6 · Alltagsleben und soziale Kontakte | Rohpunkte | 6 |

## Berechnung

Gesamtpunkte = Modul 1 + max(Modul 2, Modul 3) + Modul 4 + Modul 5 + Modul 6
(jeweils gewichtete Punkte)
Der Rechner ordnet jede eingegebene Modulsumme dem Punktbereich aus Anlage 2 zu, nimmt den höheren Wert aus Modul 2 und 3, addiert alles und vergleicht das Ergebnis mit den Schwellen aus § 15 Abs. 3 SGB XI. Zusätzlich zeigt er, wie viele Punkte bis zur nächsten Schwelle fehlen. Schon wenige Einzelpunkte können über eine Stufe entscheiden, weil die gewichteten Punkte in Sprüngen steigen.

## Beispiel mit den Vorgabewerten

**Rechnerische Einstufung:** Pflegegrad 3 · 50 Punkte
- Mobilität: 5 gewichtete Punkte
- Kognition (höher als Modul 3): 7,5 gewichtete Punkte
- Selbstversorgung: 20 gewichtete Punkte
- Therapieanforderungen: 10 gewichtete Punkte
- Alltagsleben: 7,5 gewichtete Punkte
- Abstand zur nächsten Schwelle: 20 Punkte

## Grenzen

Rechnerische Orientierung nach Begutachtungs-Richtlinien; kein Gutachten, Bescheid oder Leistungsversprechen.

## Quellen

- [§ 15 SGB XI – Ermittlung des Grades der Pflegebedürftigkeit](https://www.gesetze-im-internet.de/sgb_11/__15.html)
- [Anlage 2 zu § 15 SGB XI – Bewertungssystematik](https://www.gesetze-im-internet.de/sgb_11/anlage_2.html)
- [Bundesgesundheitsministerium – Leistungsansprüche 2026 im Kurzüberblick (PDF)](https://www.bundesgesundheitsministerium.de/fileadmin/Dateien/3_Downloads/P/Pflegeversicherung_Leistungsbeitraege/Uebersicht_Leistungsbetraege_2026.pdf)
- [§ 45b SGB XI – Entlastungsbetrag](https://www.gesetze-im-internet.de/sgb_11/__45b.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
