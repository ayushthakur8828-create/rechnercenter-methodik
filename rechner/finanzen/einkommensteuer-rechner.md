# Einkommensteuer-Rechner

Live: https://rechnercenter.de/einkommensteuer-rechner

Einkommensteuer 2026 aus dem zvE – mit Grenzsteuersatz, Soli und Splitting.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Zu versteuerndes Einkommen | €/Jahr | 45.000 |
| Veranlagung |  | Einzeln (Grundtabelle) |
| Kirchensteuer |  | Keine |

## Berechnung

Grundlage ist § 32a Abs. 1 EStG in der Fassung für den Veranlagungszeitraum 2026. Das zvE wird zunächst auf volle Euro abgerundet, die Steuer anschließend ebenfalls auf volle Euro. Je nach Zone gilt:
bis 12.348 €: 0 · 12.349–17.799 €: (914,51 · y + 1.400) · y mit y = (zvE − 12.348) ÷ 10.000 · 17.800–69.878 €: (173,10 · z + 2.397) · z + 1.034,87 mit z = (zvE − 17.799) ÷ 10.000 · 69.879–277.825 €: 0,42 · zvE − 11.135,63 · ab 277.826 €: 0,45 · zvE − 19.470,38
Bei der Splittingtabelle (§ 32a Abs. 5 EStG) wird die Steuer für das halbe gemeinsame zvE berechnet und verdoppelt. Der Solidaritätszuschlag beträgt 5,5 % der Steuer, höchstens aber 11,9 % des Betrags über der Freigrenze (§ 3 und § 4 SolzG). Die Kirchensteuer setzt der Rechner als 8 oder 9 % der tariflichen Steuer an. Den Grenzsteuersatz ermittelt er aus dem Steuerunterschied bei 1.000 € mehr Einkommen.

## Beispiel mit den Vorgabewerten

**Einkommensteuer:** 8.835 €
- Tarifliche Einkommensteuer: 8.835
- Solidaritätszuschlag: 0
- Kirchensteuer: 0

## Grenzen

Tarifformel 2026 (§ 32a EStG), ohne Progressionsvorbehalt, außerordentliche Einkünfte oder Ermäßigungen. Keine Steuerberatung.

## Quellen

- [§ 32a EStG – Einkommensteuertarif (ab VZ 2026)](https://www.gesetze-im-internet.de/estg/__32a.html)
- [§ 26b EStG – Zusammenveranlagung von Ehegatten](https://www.gesetze-im-internet.de/estg/__26b.html)
- [§ 3 SolzG 1995 – Bemessungsgrundlage und Freigrenzen](https://www.gesetze-im-internet.de/solzg_1995/__3.html)
- [§ 4 SolzG 1995 – Zuschlagsatz](https://www.gesetze-im-internet.de/solzg_1995/__4.html)
- [§ 51a EStG – Festsetzung und Erhebung von Zuschlagsteuern](https://www.gesetze-im-internet.de/estg/__51a.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
