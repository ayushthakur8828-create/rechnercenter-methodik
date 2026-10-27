# Steuerklassen-Rechner

Live: https://rechnercenter.de/steuerklassen-rechner

Lohnsteuer bei III/V und IV/IV vergleichen, inklusive Nachzahlungsrisiko.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Bruttogehalt Partner 1 (höher) | €/Monat | 4.500 |
| Bruttogehalt Partner 2 | €/Monat | 2.500 |

## Berechnung

zvE = Jahresbrutto − Vorsorgepauschale − 1.266 €
IV/IV: Steuer = ESt(zvE₁) + ESt(zvE₂)
III/V: Steuer = 2 · ESt(zvE₁ / 2) + Steuer nach Klasse V (zvE₂)
Tatsächlich: Steuer = 2 · ESt((zvE₁ + zvE₂) / 2)
Partner 1 ist der höher verdienende. Aus dem Bruttogehalt wird zunächst ein vereinfachtes zu versteuerndes Einkommen gebildet: Von den Jahreseinnahmen gehen eine Vorsorgepauschale (Rentenversicherung 9,3 % bis 101.400 €, Kranken- und Pflegeversicherung 10,85 % bis 69.750 €) und 1.266 € Pauschalabzüge ab. Auf dieses Einkommen wird der Tarif 2026 aus § 32a EStG angewendet (Grundfreibetrag 12.348 €).
Bei IV/IV wird jeder Partner nach der Grundtabelle besteuert. Bei III/V erhält der Besserverdiener den Splittingabzug, der andere die deutlich höhere Klasse V, die der Rechner nach der Systematik des lohnsteuerlichen Programmablaufplans nachbildet. Die gesetzliche Grundlage der Klassen ist § 38b EStG. Das Ergebnis „Echte Jahressteuer“ ist der Splittingbetrag aus dem Gesamteinkommen beider.

## Beispiel mit den Vorgabewerten

**Monatlicher Liquiditätsvorteil III/V:** 71,58 €
- Jahressteuer bei IV/IV (Abzug): 10.050
- Jahressteuer bei III/V (Abzug): 9.191
- Echte Jahressteuer: 9.732

## Grenzen

Vereinfachter Vergleich mit Tarif und Beitragsgrenzen 2026, ohne Soli, Kirchensteuer und individuelle Freibeträge. Keine Steuerberatung.

## Quellen

- [§ 38b EStG – Lohnsteuerklassen](https://www.gesetze-im-internet.de/estg/__38b.html)
- [§ 39 EStG – Lohnsteuerabzugsmerkmale](https://www.gesetze-im-internet.de/estg/__39.html)
- [§ 39f EStG – Faktorverfahren](https://www.gesetze-im-internet.de/estg/__39f.html)
- [§ 46 EStG – Veranlagung von Arbeitnehmern](https://www.gesetze-im-internet.de/estg/__46.html)
- [§ 32a EStG – Einkommensteuertarif](https://www.gesetze-im-internet.de/estg/__32a.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
