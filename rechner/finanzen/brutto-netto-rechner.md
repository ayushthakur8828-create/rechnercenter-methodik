# Brutto-Netto-Rechner

Live: https://rechnercenter.de/brutto-netto-rechner

Nettogehalt 2026 aus Brutto, Steuerklasse und Sozialabgaben schätzen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Bruttogehalt | €/Monat | 3.500 |
| Steuerklasse |  | I (ledig) |
| Kirchensteuer |  | Keine |
| KV-Zusatzbeitrag |  | 2,9 % (Durchschnitt 2026) |
| Kinder (PV-Abschlag) |  | Keine Kinder |

## Berechnung

Netto = Brutto − Sozialversicherung − Lohnsteuer − Solidaritätszuschlag − Kirchensteuer
Der Rechner arbeitet mit Jahreswerten (Monatsbrutto × 12) und teilt das Ergebnis am Ende wieder durch 12. Schritt für Schritt:
- Sozialversicherung (Arbeitnehmeranteil): Rentenversicherung 9,3 %, Arbeitslosenversicherung 1,3 %, Krankenversicherung 7,3 % plus die Hälfte des gewählten Zusatzbeitrags, Pflegeversicherung 1,8 % (mit Zuschlag bzw. Abschlag je nach Kinderzahl). Die Beiträge werden nur bis zur Beitragsbemessungsgrenze erhoben: 101.400 € im Jahr für Renten- und Arbeitslosenversicherung, 69.750 € für Kranken- und Pflegeversicherung.
- Zu versteuerndes Einkommen: Jahresbrutto abzüglich einer Vorsorgepauschale (Rentenbeitrag, Krankenversicherung mit ermäßigtem Satz von 7,0 % plus halbem Zusatzbeitrag, Pflegebeitrag), des Arbeitnehmer-Pauschbetrags von 1.230 € (§ 9a EStG) und des Sonderausgaben-Pauschbetrags von 36 €.
- Lohnsteuer: Anwendung des Tarifs nach § 32a EStG. In Klasse III wird das Einkommen halbiert, besteuert und die Steuer verdoppelt (Splitting). In Klasse II wird zusätzlich der Entlastungsbetrag von 4.260 € abgezogen (§ 24b EStG). Klasse V und VI folgen den Sonderformeln des Programmablaufplans.
- Soli und Kirchensteuer werden auf die Lohnsteuer aufgeschlagen, bei Kindern auf Basis einer fiktiven Steuer nach Abzug der Kinderfreibeträge.

## Beispiel mit den Vorgabewerten

**Nettogehalt (ca.):** 2.333,25 €
- Lohnsteuer: 405,5
- Soli + Kirchensteuer: 0
- Sozialversicherung: 761,25
- Netto: 2.333,25

## Grenzen

BMF-nahe Schätzung mit Tarif und Beitragsgrenzen 2026. Individuelle Freibeträge, Sachsen-Regelung, Alter, Kassenbeitrag und weitere Abrechnungsmerkmale können das Ergebnis verändern. Keine Steuerberatung.

## Quellen

- [§ 32a EStG – Einkommensteuertarif](https://www.gesetze-im-internet.de/estg/__32a.html)
- [§ 38b EStG – Lohnsteuerklassen](https://www.gesetze-im-internet.de/estg/__38b.html)
- [§ 3 SolzG 1995 – Freigrenze Solidaritätszuschlag](https://www.gesetze-im-internet.de/solzg_1995/__3.html)
- [§ 4 SolzG 1995 – Zuschlagsatz und Milderung](https://www.gesetze-im-internet.de/solzg_1995/__4.html)
- [Bundesregierung – Beitragsbemessungsgrenzen 2026](https://www.bundesregierung.de/breg-de/aktuelles/beitragsgemessungsgrenzen-2386514)
- [Bundesgesundheitsministerium – Beiträge der GKV](https://www.bundesgesundheitsministerium.de/beitraege)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
