# Autofinanzierung-Rechner

Live: https://rechnercenter.de/autofinanzierung-rechner

Monatsrate und Zinskosten einer Autofinanzierung berechnen, auch mit Schlussrate.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Kaufpreis | € | 30.000 |
| Anzahlung | € | 5.000 |
| Schlussrate (Ballon) | € | 0 |
| Effektiver Jahreszins | % | 5,5 |
| Laufzeit | Monate | 48 |

## Berechnung

Kredit = Kaufpreis − Anzahlung
Monatszins i = (1 + effektiver Jahreszins)^(1/12) − 1
Rate = (Kredit − Schlussrate ÷ (1 + i)^n) × i ÷ (1 − (1 + i)^−n)
Der Rechner nutzt die Annuitätenformel: Jede Rate ist gleich hoch, anfangs enthält sie mehr Zinsen, später mehr Tilgung. Aus dem effektiven Jahreszins wird ein Monatszins berechnet, der aufs Jahr hochgerechnet genau den Effektivzins ergibt. Bei einer Schlussrate wird nur der Teil des Kredits über die Monatsraten getilgt, der nicht am Ende auf einmal fällig ist.
Der Gesamtaufwand ist die Summe aller Raten plus Anzahlung plus Schlussrate. Zinskosten sind der Gesamtaufwand minus Kaufpreis.

## Beispiel mit den Vorgabewerten

**Monatliche Rate:** 579,89 €
- Kreditsumme: 25.000
- Zinskosten gesamt: 2.834,57
- Schlussrate: 0

## Grenzen

Kein individueller bonitätsabhängiger Zins, keine Restschuldversicherung, keine Bearbeitungs- oder Kontoführungsentgelte. Bei Ballonfinanzierung wird nicht geprüft, ob der Fahrzeugwert bei Fälligkeit die Schlussrate deckt

## Quellen

- [§ 6 PAngV – Effektiver Jahreszins](https://www.gesetze-im-internet.de/pangv_2022/__6.html)
- [§ 500 BGB – Vorzeitige Rückzahlung](https://www.gesetze-im-internet.de/bgb/__500.html)
- [§ 502 BGB – Vorfälligkeitsentschädigung](https://www.gesetze-im-internet.de/bgb/__502.html)
- [§ 355 BGB – Widerrufsrecht](https://www.gesetze-im-internet.de/bgb/__355.html)
- [§ 358 BGB – Verbundene Verträge](https://www.gesetze-im-internet.de/bgb/__358.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
