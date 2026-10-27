# Reifengrößen-Rechner

Live: https://rechnercenter.de/reifengroesse-rechner

Zwei Reifengrößen vergleichen: Abrollumfang, Tachoabweichung und Bodenfreiheit.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Serienreifen Breite | mm | 205 |
| Serienreifen Querschnitt | % | 55 |
| Serienreifen Felge | Zoll | 16 |
| Wunschreifen Breite | mm | 225 |
| Wunschreifen Querschnitt | % | 45 |
| Wunschreifen Felge | Zoll | 17 |

## Berechnung

Durchmesser = Felge × 25,4 + 2 × Breite × Querschnitt ÷ 100
Abrollumfang = Durchmesser × π
Abweichung = Umfang neu ÷ Umfang alt − 1
Beispiel 205/55 R16: 16 × 25,4 = 406,4 mm Felge plus 2 × 112,75 mm Flanke = 631,9 mm Durchmesser, Umfang 1.985 mm. Die Bodenfreiheit ändert sich um die Hälfte der Durchmesserdifferenz. Der Rechner nutzt die Nennmaße; der tatsächliche Abrollumfang unter Last ist etwas kleiner und unterscheidet sich je nach Reifenmodell leicht.

## Beispiel mit den Vorgabewerten

**Abweichung des Abrollumfangs:** +0,38 %
- Durchmesser alt / neu: 631,9 / 634,3 mm
- Umfang alt / neu: 1.985 / 1.993 mm
- Rechnerisch bei Tacho 100: 100,4 km/h
- Bodenfreiheit: +1,2 mm

## Grenzen

Keine Freigabeprüfung: Ob eine Größe für Ihr Fahrzeug zulässig ist, steht in der Zulassungsbescheinigung Teil I, im COC-Papier oder in einer Reifenfreigabe des Herstellers. Nicht geprüft werden Traglast- und Geschwindigkeitsindex, Freigängigkeit und Einpresstiefe

## Quellen

- [§ 57 StVZO – Geschwindigkeitsmessgerät](https://www.gesetze-im-internet.de/stvzo_2012/__57.html)
- [UN-Regelung Nr. 39 – Geschwindigkeitsmesser (EUR-Lex)](https://eur-lex.europa.eu/eli/reg/2010/39(2)/oj/eng)
- [§ 19 StVZO – Erteilung und Wirksamkeit der Betriebserlaubnis](https://www.gesetze-im-internet.de/stvzo_2012/__19.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
