# Leasing-Rechner

Live: https://rechnercenter.de/leasing-rechner

Leasingrate, Leasingfaktor und Gesamtkosten aus Preis und Restwert kalkulieren.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Fahrzeugpreis (Verhandlungsbasis) | € | 40.000 |
| Restwert am Ende | % | 55 |
| Laufzeit | Monate | 36 |
| Anzahlung | € | 0 |
| Leasingzins | % p. a. | 5 |

## Berechnung

Wertverlust je Monat = (Preis − Anzahlung − Restwert) ÷ Laufzeit
Zinsanteil = (Preis − Anzahlung + Restwert) ÷ 2 × Zinssatz ÷ 12
Rate = Wertverlust + Zinsanteil
Leasingfaktor = Rate ÷ Preis × 100
Der Restwert wird als Prozentsatz des eingegebenen Preises angesetzt. Für den Zinsanteil nimmt der Rechner das durchschnittlich gebundene Kapital – den Mittelwert aus Startbetrag und Restwert – und verzinst es monatlich. Das ist eine gängige Näherung; eine exakte Annuitätenrechnung des Leasinggebers kann um einige Euro abweichen. Die Gesamtkosten sind Rate × Laufzeit plus Anzahlung.
Rechtlich gilt: Verpflichtet sich ein Verbraucher, bei Vertragsende für einen bestimmten Wert des Fahrzeugs einzustehen – also beim klassischen Restwertvertrag –, ist der Leasingvertrag nach § 506 Abs. 2 Satz 1 Nr. 3 BGB eine entgeltliche Finanzierungshilfe. Dann gelten nach § 506 Abs. 1 BGB weite Teile des Verbraucherdarlehensrechts entsprechend, darunter das Widerrufsrecht.

## Beispiel mit den Vorgabewerten

**Monatliche Leasingrate:** 629,17 €
- Wertverlust-Anteil: 500
- Zins-Anteil: 129,17
- Kalkulierter Restwert: 22.000

## Grenzen

Keine Überführungs- und Zulassungskosten, keine Wartungs- oder Versicherungspakete, keine Mehrkilometer- und Minderkilometerabrechnung und keine Nachforderung für Schäden über die normale Abnutzung hinaus bei Rückgabe

## Quellen

- [BGB § 506 – Zahlungsaufschub, sonstige Finanzierungshilfe](https://www.gesetze-im-internet.de/bgb/__506.html)
- [BGB § 495 – Widerrufsrecht bei Verbraucherdarlehen](https://www.gesetze-im-internet.de/bgb/__495.html)
- [BGB § 355 – Widerrufsrecht bei Verbraucherverträgen](https://www.gesetze-im-internet.de/bgb/__355.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
