# Midijob-Rechner

Live: https://rechnercenter.de/midijob-rechner

Reduzierte Sozialabgaben im Midijob (603,01–2.000 €) für 2026 berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Monatliches Brutto | € | 1.200 |
| Zusatzbeitrag Krankenkasse | % | 2,9 |
| Pflegeversicherung |  | Mit 1 Kind / unter 23 |

## Berechnung

Grundlage ist § 20 Abs. 2a SGB IV. Es gibt zwei beitragspflichtige Einnahmen: eine für den Gesamtbeitrag und eine nur für den Arbeitnehmeranteil. Mit dem Faktor F = 0,6619 für 2026 (28 % geteilt durch den Gesamtsozialversicherungsbeitragssatz) ergeben sich vereinfacht:
BE gesamt = 1,1459372226 × Brutto − 291,8744452399
BE Arbeitnehmer = 1,43163922691 × Brutto − 863,2784538207
AN-Beitrag = BE Arbeitnehmer × (9,3 % RV + 1,3 % AV + 7,3 % KV + ½ Zusatzbeitrag + 1,8 % PV) + BE gesamt × Pflege-Korrektur
Die Pflege-Korrektur ist der Unterschied zwischen Ihrem individuellen Pflegesatz und 1,8 %: kinderlose Versicherte ab 23 zahlen 0,6 Prozentpunkte mehr, Eltern mit mehreren Kindern unter 25 erhalten Abschläge von 0,25 Punkten je Kind ab dem zweiten (bis zum fünften). Diese Korrektur wird auf die Einnahme für den Gesamtbeitrag angewandt. Zum Vergleich rechnet das Tool den normalen Arbeitnehmeranteil auf das volle Brutto und weist die Differenz als Ersparnis aus.

## Beispiel mit den Vorgabewerten

**Ihr SV-Beitrag (ca.):** 180,77 €
- Normaler AN-Anteil: 253,8
- Monatliche Ersparnis: 73,03

## Grenzen

Berechnung mit den amtlichen Übergangsbereichsformeln 2026. Abweichungen sind möglich, etwa durch Umlagen, Sonderregeln oder die kassenindividuelle Abrechnung.

## Quellen

- [§ 20 SGB IV – Übergangsbereich](https://www.gesetze-im-internet.de/sgb_4/__20.html)
- [§ 8 SGB IV – Geringfügigkeitsgrenze](https://www.gesetze-im-internet.de/sgb_4/__8.html)
- [§ 70 SGB VI – Entgeltpunkte](https://www.gesetze-im-internet.de/sgb_6/__70.html)
- [Deutsche Rentenversicherung – Übergangsbereich](https://www.deutsche-rentenversicherung.de/DRV/DE/Experten/Arbeitgeber-und-Steuerberater/Gleitzone-Uebergangsbereich/uebergangsbereich_gleitzone.html)
- [BMAS – Mindestlohn](https://www.bmas.de/DE/Arbeit/Arbeitsrecht/Mindestlohn/mindestlohn.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
