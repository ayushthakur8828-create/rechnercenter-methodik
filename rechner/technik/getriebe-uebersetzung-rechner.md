# Getriebe-Übersetzung-Rechner

Live: https://rechnercenter.de/getriebe-uebersetzung-rechner

Übersetzung, Abtriebsdrehzahl und ideales Drehmoment eines Zahnradpaars.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Zähne Antriebsrad |  | 20 |
| Zähne Abtriebsrad |  | 60 |
| Antriebsdrehzahl | 1/min | 1.500 |

## Berechnung

i = z₂ ÷ z₁
n₂ = n₁ ÷ i
M₂ = M₁ · i (ideal, ohne Verluste)
Der Rechner nimmt die Zähnezahl des treibenden Rads z₁, die des getriebenen Rads z₂ und die Antriebsdrehzahl n₁ in 1/min. Er gibt die Abtriebsdrehzahl n₂ aus, dazu die Übersetzung i und die ideale Momentenänderung als Faktor (er ist identisch mit i).
Die Herleitung: Im Eingriff wälzen beide Räder am Teilkreis ohne Gleiten aufeinander ab, die Umfangsgeschwindigkeit ist also gleich. Da bei gleichem Modul der Teilkreisdurchmesser proportional zur Zähnezahl ist, laufen die Drehzahlen umgekehrt zu den Zähnezahlen. Die Leistung P = M · ω bleibt ideal gleich, daher steigt das Moment, wenn die Drehzahl sinkt. Es handelt sich um eine technisch-physikalische Beziehung, keine gesetzliche Regel.

## Beispiel mit den Vorgabewerten

**Abtriebsdrehzahl:** 500 1/min
- Übersetzung i = z₂/z₁: 3
- Ideale Momentenänderung: Faktor 3

## Quellen

- [TU Dresden – Formelsammlung Maschinenwesen](https://tu-dresden.de/ing/maschinenwesen/fernstudium/ressourcen/dateien/downloads/ae/Formelsammlung.pdf?lang=de)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
