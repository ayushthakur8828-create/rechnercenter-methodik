# Kalorienbedarf-Rechner

Live: https://rechnercenter.de/kalorienbedarf-rechner

Grundumsatz und Tagesbedarf in kcal, mit PAL-Stufe, Sport und Abnehmwert.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Geschlecht |  | Frau |
| Alter (ab 18 Jahren) | Jahre | 30 |
| Gewicht | kg | 70 |
| Größe | cm | 175 |
| Überwiegende Tätigkeit am Tag |  | Sitzend, zeitweise gehend oder stehend |

## Berechnung

Grundumsatz = 10 × Gewicht (kg) + 6,25 × Größe (cm) − 5 × Alter (Jahre) + 5 (Männer) bzw. − 161 (Frauen)
Gesamtumsatz = Grundumsatz × PAL
Mit Sport = Gesamtumsatz + 400 kcal × 3 ÷ 7
Zum Abnehmen = Gesamtumsatz − 500 kcal, mindestens Grundumsatz
Für den Grundumsatz verwendet der Rechner die Gleichung nach Mifflin und St Jeor. Die Multiplikation mit dem PAL-Wert entspricht dem Vorgehen der DGE: Grundumsatz mal PAL ergibt den Gesamtenergiebedarf. Ein Gesetz oder eine Rechtsvorschrift steht dahinter nicht; die Werte der DGE sind Empfehlungen.
Der Rechner kennt fünf Aktivitätsstufen mit den Faktoren 1,4, 1,6, 1,75, 2,0 und 2,2. Die Stufe richtet sich nach der überwiegenden Tätigkeit am Tag, nicht nach dem Training. Sport kommt als eigene Zeile hinzu: Der Rechner setzt dafür 400 kcal je Einheit an und rechnet drei Einheiten pro Woche auf den Tagesschnitt um (rund 171 kcal).

## Beispiel mit den Vorgabewerten

**Gesamtumsatz:** 2372 kcal/Tag
- Grundumsatz (BMR): 1483 kcal
- Aktivitätsfaktor (PAL): × 1,6
- Mit 3 Trainingseinheiten je Woche: 2544 kcal/Tag im Schnitt
- Zum Abnehmen: 1872 kcal (−500 kcal)

## Grenzen

Richtwerte für gesunde Erwachsene, keine Ernährungs- oder medizinische Beratung. Bei Erkrankungen, Essstörungen, Schwangerschaft: ärztlich begleiten lassen.

## Quellen

- [DGE – Referenzwerte Energie](https://www.dge.de/wissenschaft/referenzwerte/energie/)
- [DGE – FAQ Energie (PDF, 2015)](https://www.dge.de/fileadmin/dok/gesunde-ernaehrung/faq/DGE-FAQ-Energie-2015.pdf)
- [Verbraucherzentrale NRW – Energiebedarf und Kalorien](https://www.verbraucherzentrale.nrw/wissen/lebensmittel/gesund-ernaehren/ernaehrung-umsatz-kalorien-wie-viel-energie-benoetigt-der-koerper-102519)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
