# Lohnsteuer-Rechner

Live: https://rechnercenter.de/lohnsteuer-rechner

Monatliche Lohnsteuer 2026 nach Steuerklasse I–VI berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Bruttogehalt | €/Monat | 3.500 |
| Steuerklasse |  | I (ledig) |

## Berechnung

Jahresbrutto = Monatsbrutto × 12
Vorsorgepauschale = 9,3 % × min(Jahresbrutto; 101.400 €) + 10,85 % × min(Jahresbrutto; 69.750 €)
zu versteuerndes Einkommen = Jahresbrutto − Vorsorgepauschale − 1.230 € − 36 €
Lohnsteuer pro Monat = Tarif nach § 32a EStG ÷ 12
Rechtsgrundlage ist § 39b Absatz 2 EStG. Die 1.230 € sind der Arbeitnehmer-Pauschbetrag (§ 9a EStG), die 36 € der Sonderausgaben-Pauschbetrag (§ 10c EStG). Die Vorsorgepauschale besteht aus der Hälfte des Rentenversicherungsbeitrags (9,3 %, bis zur Beitragsbemessungsgrenze von 101.400 €) sowie dem Teil für Kranken- und Pflegeversicherung. Der Rechner setzt hierfür 10,85 % an (ermäßigter Satz 7,0 %, halber durchschnittlicher Zusatzbeitrag 1,45 % und Pflegebeitrag Kinderloser 2,4 %), begrenzt auf 69.750 € Jahreseinkommen.
Je nach Klasse ändert sich der letzte Schritt: In Klasse II wird zusätzlich der Entlastungsbetrag für Alleinerziehende von 4.260 € abgezogen (§ 24b EStG). In Klasse III wird das Einkommen halbiert, der Tarif angewandt und das Ergebnis verdoppelt (Splitting). In Klasse V und VI gilt die Sonderformel aus § 39b Absatz 2 Satz 7 EStG: das Zweifache des Unterschieds zwischen der Steuer auf das 1,25-Fache und das 0,75-Fache des Einkommens, mindestens 14 %. In Klasse VI entfallen außerdem die Pauschbeträge.

## Beispiel mit den Vorgabewerten

**Lohnsteuer (ca.):** 405,5 €
- Lohnsteuer pro Jahr: 4.866
- Steuerquote: 11,6 %

## Grenzen

BMF-nahe Schätzung nach Tarif und Beitragsgrenzen 2026 (ohne Kirchensteuer, Soli und individuelle Freibeträge). Verbindlich ist die Gehaltsabrechnung. Keine Steuerberatung.

## Quellen

- [§ 32a EStG – Einkommensteuertarif](https://www.gesetze-im-internet.de/estg/__32a.html)
- [§ 39b EStG – Einbehaltung der Lohnsteuer](https://www.gesetze-im-internet.de/estg/__39b.html)
- [§ 38b EStG – Lohnsteuerklassen](https://www.gesetze-im-internet.de/estg/__38b.html)
- [§ 39a EStG – Freibetrag beim Lohnsteuerabzug](https://www.gesetze-im-internet.de/estg/__39a.html)
- [Verordnung über Rechengrößen der Sozialversicherung 2026](https://www.gesetze-im-internet.de/svbezgrv_2026/BJNR1160A0025.html)
- [Bundesgesundheitsministerium – Beiträge zur GKV](https://www.bundesgesundheitsministerium.de/beitraege)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
