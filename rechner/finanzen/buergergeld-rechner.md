# Grundsicherungsgeld-Rechner (Bürgergeld)

Live: https://rechnercenter.de/buergergeld-rechner

Grundsicherungsgeld (früher Bürgergeld): Anspruch aus Regelbedarf, Miete, Einkommen schätzen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Haushalt |  | Alleinstehend |
| Kinder 6–13 Jahre | Anzahl | 0 |
| Kinder 14–17 Jahre | Anzahl | 0 |
| Kinder 0–5 Jahre | Anzahl | 0 |
| Warmmiete (angemessen) | €/Monat | 650 |
| Brutto-Erwerbseinkommen | €/Monat | 0 |
| Netto-Erwerbseinkommen | €/Monat | 0 |
| Kindergeld wird angerechnet? |  | Ja (Standard) |

## Berechnung

Anspruch = Regelbedarfe + Warmmiete − anrechenbares Netto − Kindergeld
Der Rechner addiert die Regelbedarfe aller Haushaltsmitglieder und die eingegebene Warmmiete. Danach ermittelt er den Freibetrag für Erwerbseinkommen nach § 11b SGB II: Der Freibetrag wird aus dem Brutto berechnet und vom Netto abgezogen. Nur der verbleibende Rest mindert den Anspruch.
- Die ersten 100 € Brutto bleiben frei (Grundfreibetrag).
- Für Brutto von 100 bis 520 € kommen 20 % hinzu.
- Für Brutto von 520 bis 1.000 € kommen 30 % hinzu.
- Für Brutto von 1.000 bis 1.200 € kommen 10 % hinzu, mit minderjährigem Kind bis 1.500 €.
Kindergeld (259 € je Kind im Jahr 2026) zählt als Einkommen des Kindes und wird je Kind vollständig abgezogen. Liegt das Ergebnis unter null, zeigt der Rechner „kein Anspruch“.

## Beispiel mit den Vorgabewerten

**Grundsicherungsgeld (ca.):** 1.213 €
- Regelbedarf: 563
- Unterkunft & Heizung: 650
- Anrechenbares Einkommen + Kindergeld: 0

## Grenzen

Vereinfachte Schätzung (Regelsätze 2026, ohne Mehrbedarfe und Vermögensprüfung). Verbindlich entscheidet das Jobcenter. Keine Rechtsberatung.

## Quellen

- [BMAS – Umgestaltung der Grundsicherung tritt in Kraft](https://www.bmas.de/DE/Service/Presse/Pressemitteilungen/2026/umgestaltung-der-grundsicherung-tritt-in-kraft.html)
- [BMAS – Was ändert sich für Leistungsberechtigte?](https://www.bmas.de/DE/Arbeit/Grundsicherung-fuer-Arbeitsuchende/FAQ-Was-aendert-sich-mit-der-neuen-Grundsicherung-Leistungsberechtigte/faq-was-aendert-sich-mit-der-neuen-grundsicherung-leistungsberechtigte.html)
- [Bundesregierung – Regelbedarfe 2026 (Nullrunde)](https://www.bundesregierung.de/breg-de/aktuelles/nullrunde-buergergeld-2383676)
- [§ 11b SGB II – Absetzbeträge](https://www.gesetze-im-internet.de/sgb_2/__11b.html)
- [§ 12 SGB II – Zu berücksichtigendes Vermögen](https://www.gesetze-im-internet.de/sgb_2/__12.html)
- [Familienportal – Kindergeld](https://familienportal.de/familienportal/familienleistungen/kindergeld/faq)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
