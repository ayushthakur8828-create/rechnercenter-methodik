# BAföG-Rechner

Live: https://rechnercenter.de/bafoeg-rechner

BAföG-Anspruch für Studierende aus Elterneinkommen, Wohnsituation und Nebenjob schätzen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Wohnsituation |  | Eigene Wohnung / WG |
| Selbst kranken­versichert? |  | Ja (über 25 / eigene KV) |
| Nettoeinkommen der Eltern | €/Monat | 3.200 |
| Weitere unterhaltsberechtigte Kinder | Anzahl | 0 |
| Eigener Verdienst (brutto) | €/Monat | 0 |

## Berechnung

Bedarf = 475 € + Wohnpauschale (380 € auswärts, 59 € bei den Eltern) + 137 € KV/PV (falls selbst versichert)
Anrechnung Eltern = (Elterneinkommen − 2.540 € − 770 € je weiteres Kind) × (50 % − 5 % je weiteres Kind)
BAföG = Bedarf − Anrechnung Eltern − eigener Verdienst über 603 €
- Bedarf nach § 13 und § 13a BAföG: 102 € für die Kranken- und 35 € für die Pflegeversicherung, wenn Sie nicht mehr familienversichert sind.
- Freibetrag der Eltern nach § 25 BAföG: 2.540 € bei verheirateten, zusammenlebenden Eltern, plus 770 € je weiteres Kind, das selbst nicht in einer BAföG-fähigen Ausbildung ist.
- Vom Einkommen über dem Freibetrag bleiben 50 % frei, zuzüglich 5 % je weiteres Kind. Der Rest wird angerechnet.
- Eigener Verdienst: Ein Minijob bis zur Minijob-Grenze von 603 € im Monat bleibt anrechnungsfrei.
Beträge unter 10 € werden nicht ausgezahlt.

## Beispiel mit den Vorgabewerten

**BAföG (ca.):** 662 €
- Bedarfssatz: 992
- Anrechnung Eltern: 330
- Anrechnung eigener Verdienst: 0

## Grenzen

Stark vereinfachte Schätzung (Sozialpauschalen der Eltern nicht einzeln berechnet). Verbindlich entscheidet das BAföG-Amt.

## Quellen

- [§ 13 BAföG – Bedarf für Studierende](https://www.gesetze-im-internet.de/baf_g/__13.html)
- [§ 13a BAföG – Kranken- und Pflegeversicherungszuschlag](https://www.gesetze-im-internet.de/baf_g/__13a.html)
- [§ 25 BAföG – Freibeträge vom Einkommen der Eltern](https://www.gesetze-im-internet.de/baf_g/__25.html)
- [§ 18 BAföG – Darlehensbedingungen](https://www.gesetze-im-internet.de/baf_g/__18.html)
- [Deutscher Bundestag – Gesetzentwurf 30. BAföG-Änderungsgesetz (hib 800/2026)](https://www.bundestag.de/presse/hib/kurzmeldungen-1223398)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
