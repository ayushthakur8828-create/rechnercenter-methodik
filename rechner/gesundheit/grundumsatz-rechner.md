# Grundumsatz-Rechner

Live: https://rechnercenter.de/grundumsatz-rechner

Ruheverbrauch in kcal nach Mifflin-St-Jeor aus Gewicht, Größe und Alter.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Geschlecht |  | Männlich |
| Gewicht | kg | 80 |
| Größe | cm | 178 |
| Alter (ab 18 Jahren) | Jahre | 35 |

## Berechnung

Der Rechner verwendet die 1990 veröffentlichte Gleichung von Mifflin und Kollegen. Sie wurde aus Messungen (indirekte Kalorimetrie) an 498 gesunden Personen zwischen 19 und 78 Jahren abgeleitet, darunter normalgewichtige und adipöse. In der vereinfachten, nach Geschlecht getrennten Form lautet sie:
Männer: 10 × Gewicht (kg) + 6,25 × Größe (cm) − 5 × Alter (Jahre) + 5
Frauen: 10 × Gewicht (kg) + 6,25 × Größe (cm) − 5 × Alter (Jahre) − 161
Das Ergebnis wird auf ganze kcal gerundet. Für die Hochrechnung auf den Tagesbedarf multipliziert der Rechner den ungerundeten Grundumsatz mit festen Faktoren:
- 1,2 für überwiegend sitzende Lebensweise
- 1,375 für Bürotätigkeit mit wenig Sport (steht als eigene Zeile im Ergebnis)
- 1,55 für moderat aktive Menschen
- 1,725 für sehr aktive Menschen
Zusätzlich zeigt der Rechner den Verbrauch je Stunde, also den Grundumsatz geteilt durch 24. Die Faktoren sind Näherungswerte des Rechners. Die Deutsche Gesellschaft für Ernährung (DGE) arbeitet in ihren Referenzwerten mit PAL-Werten, das ist das Verhältnis von Gesamtenergieverbrauch zu Ruheverbrauch, und gibt Richtwerte für PAL 1,4, 1,6 und 1,8 an.

## Beispiel mit den Vorgabewerten

**Grundumsatz:** 1.743 kcal/Tag
- Gesamtumsatz (Büro, wenig Sport): 2.396 kcal
- Pro Stunde in Ruhe: 73 kcal

## Grenzen

Schätzformel für Gesunde – individuelle Abweichungen von ±10 % sind normal. Keine Ernährungsberatung.

## Quellen

- [Mifflin et al. (1990): A new predictive equation for resting energy expenditure in healthy individuals, Am J Clin Nutr 51:241-247](https://pubmed.ncbi.nlm.nih.gov/2305711/)
- [DGE – FAQ Energiezufuhr (Grundumsatz, Ruheenergieverbrauch, PAL)](https://www.dge.de/gesunde-ernaehrung/faq/energiezufuhr/)
- [DGE – Referenzwerte Energie](https://www.dge.de/wissenschaft/referenzwerte/energie/)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
