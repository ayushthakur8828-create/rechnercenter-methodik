# Wohngeld-Rechner

Live: https://rechnercenter.de/wohngeld-rechner

Wohngeld nach der Formel aus § 19 WoGG aus Miete, Einkommen und Haushalt schätzen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Personen im Haushalt |  | 2 |
| Mietenstufe der Gemeinde |  | IV (mittleres Mietniveau) |
| Miete inkl. kalter Nebenkosten (ohne Heizung) | €/Monat | 800 |
| Gesamteinkommen (brutto) | €/Monat | 2.200 |
| Pauschale Abzüge (Steuern + RV + KV) |  | 30 % (Arbeitnehmer, Standard) |

## Berechnung

Wohngeld = 1,15 × (M − (a + b × M + c × Y) × Y)
Die Formel steht in § 19 WoGG. M ist die monatliche Miete, die berücksichtigt wird, Y das monatliche Gesamteinkommen. Die Werte a, b und c legt Anlage 2 des Gesetzes je nach Haushaltsgröße fest. Der Rechner geht in diesen Schritten vor:
- Er bestimmt den Höchstbetrag für Ihre Haushaltsgröße und Mietenstufe (§ 12 Abs. 1, Anlage 1) und addiert die Klimakomponente (§ 12 Abs. 7).
- Er nimmt das Kleinere aus Ihrer tatsächlichen Miete und diesem Betrag und addiert die Heizkostenkomponente (§ 12 Abs. 6). Das Ergebnis ist M.
- Er kürzt das Bruttoeinkommen um den gewählten Pauschalabzug. Das Ergebnis ist Y.
- Er setzt M und Y mit den Koeffizienten Ihrer Haushaltsgröße in die Formel ein und rundet auf volle Euro. Beträge unter 10 € zeigt er als „kein Anspruch“.
Für Haushalte mit mehr als zwölf Mitgliedern sieht § 19 einen Zuschlag je weiterer Person vor. Der Rechner begrenzt die Eingabe daher auf zwölf Personen.

## Beispiel mit den Vorgabewerten

**Wohngeld (ca.):** 271 €
- Berücksichtigte Miete inkl. Heizkostenkomponente: 786,4
- Anrechenbares Einkommen (Näherung): 1.540
- Höchstbetrag der Miete (Mietenstufe): 643,8

## Grenzen

Schätzung nach der Wohngeldformel (§ 19 WoGG, Werte 2025/2026). Das anrechenbare Einkommen ist pauschal genähert; Freibeträge, z. B. für Alleinerziehende oder Schwerbehinderung, sind nicht enthalten. Verbindlich entscheidet die Wohngeldstelle.

## Quellen

- [§ 19 WoGG – Höhe des Wohngeldes](https://www.gesetze-im-internet.de/wogg/__19.html)
- [§ 12 WoGG – Höchstbeträge, Heizkosten- und Klimakomponente](https://www.gesetze-im-internet.de/wogg/__12.html)
- [Anlage 1 WoGG – Höchstbeträge für Miete](https://www.gesetze-im-internet.de/wogg/anlage_1.html)
- [§ 17 WoGG – Freibeträge](https://www.gesetze-im-internet.de/wogg/__17.html)
- [Bundesregierung – Wohngeld wird neu geordnet](https://www.bundesregierung.de/breg-de/aktuelles/neuordnung-wohngeld-2445796)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
