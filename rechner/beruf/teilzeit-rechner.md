# Teilzeit-Rechner

Live: https://rechnercenter.de/teilzeit-rechner

Teilzeitgehalt brutto und netto bei weniger Wochenstunden berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Vollzeit-Bruttogehalt | €/Monat | 4.000 |
| Vollzeit-Wochenstunden | Std. | 40 |
| Gewünschte Wochenstunden | Std. | 30 |

## Berechnung

Teilzeit-Brutto = Vollzeit-Brutto × Teilzeitstunden ÷ Vollzeitstunden
Netto = Brutto − Sozialabgaben − Lohnsteuer (Jahreswert ÷ 12)
Für das Netto rechnet das Tool auf Jahresbasis. Sozialabgaben: 9,3 % Rente und 1,3 % Arbeitslosenversicherung bis zur Beitragsbemessungsgrenze von 101.400 € im Jahr, dazu 7,3 % Krankenversicherung plus halber Zusatzbeitrag (1,45 %) und 2,4 % Pflegeversicherung bis 69.750 €. Für die Lohnsteuer zieht es eine Vorsorgepauschale sowie 1.266 € (Arbeitnehmer-Pauschbetrag 1.230 € und Sonderausgaben-Pauschbetrag 36 €) ab und wendet den Grundtarif nach § 32a EStG mit dem Grundfreibetrag von 12.348 € an. Die Pflegequote entspricht dem Satz für Kinderlose; Kirchensteuer und Solidaritätszuschlag bleiben außen vor.

## Beispiel mit den Vorgabewerten

**Teilzeit-Brutto:** 3.000 €
- Netto Teilzeit (ca.): 2.054,42
- Netto Vollzeit (ca.): 2.605,5
- Netto-Verzicht: 551,08

## Grenzen

Netto-Schätzung für Steuerklasse I ohne Kirchensteuer (Tarif 2026). Keine Steuerberatung.

## Quellen

- [§ 8 TzBfG – Verringerung der Arbeitszeit](https://www.gesetze-im-internet.de/tzbfg/__8.html)
- [§ 9a TzBfG – Brückenteilzeit](https://www.gesetze-im-internet.de/tzbfg/__9a.html)
- [§ 4 TzBfG – Diskriminierungsverbot](https://www.gesetze-im-internet.de/tzbfg/__4.html)
- [§ 32a EStG – Einkommensteuertarif](https://www.gesetze-im-internet.de/estg/__32a.html)
- [§ 2 TzBfG – Begriff Teilzeit](https://www.gesetze-im-internet.de/tzbfg/__2.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
