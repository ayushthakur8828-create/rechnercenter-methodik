# Gerüstbau-Kosten-Rechner

Live: https://rechnercenter.de/geruestbau-kosten-rechner

Gerüstkosten nach Fläche, Standzeit, Netz und Fanggerüst schätzen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Einzurüstende Fläche | m² | 200 |
| Geplante Standzeit | Wochen | 4 |
| Schutznetz / Plane |  | false |
| Dachfanggerüst (bei Dacharbeiten) |  | false |

## Berechnung

Grundkosten = max(650 €; Fläche × (17 € + 0,60 € × Wochen über 4))
Netz/Plane = Fläche × 2,50 €
Dachfanggerüst = Fläche ÷ 10 × 25 €
Schätzwert = Grundkosten + Netz + Dachfanggerüst
Spanne = 85 % bis 125 % des Schätzwerts
Die Fläche ist die einzurüstende Fassadenfläche in m², also Fassadenlänge mal Gerüsthöhe aller betroffenen Seiten. Bis einschließlich 4 Wochen Standzeit bleibt der Quadratmeterpreis bei 17 €; ab der fünften Woche steigt er pro Woche um 0,60 €. Unterhalb von rund 38 m² greift ein Mindestbetrag von 650 €, der Anfahrt und Baustelleneinrichtung abbildet.
Das Dachfanggerüst rechnet der Rechner vereinfacht über die Fläche: Pro 10 m² Fassade wird 1 laufender Meter zu 25 € angesetzt. Schutznetz oder Plane kosten im Modell 2,50 €/m². Alle Beträge sind Annahmen des Tools ohne gesetzliche Grundlage – Gerüstpreise sind frei kalkuliert. Rechtlich geregelt ist dagegen die Sicherheit: Für Auf-, Um- und Abbau sowie Verankerung von Gerüsten enthält die Betriebssicherheitsverordnung in Anhang 1 Nummer 3 Mindestanforderungen an den Arbeitgeber, also an den Gerüstbaubetrieb.

## Beispiel mit den Vorgabewerten

**Ergebnis:** 2.890 bis 4.250
- Gerüst Grundkosten (Fläche): 3400 €
- Zusatzleistungen (Fanggerüst/Netz): 0 €

## Quellen

- [§ 35a EStG – Steuerermäßigung für Handwerkerleistungen](https://www.gesetze-im-internet.de/estg/__35a.html)
- [Betriebssicherheitsverordnung (BetrSichV), Anhang 1 Nr. 3 – Gerüste](https://www.gesetze-im-internet.de/betrsichv_2015/BJNR004910015.html)
- [§ 32 StVO – Verkehrshindernisse](https://www.gesetze-im-internet.de/stvo_2013/__32.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
