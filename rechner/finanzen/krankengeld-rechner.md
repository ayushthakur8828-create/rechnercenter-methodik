# Krankengeld-Rechner

Live: https://rechnercenter.de/krankengeld-rechner

Krankengeld brutto und netto je Tag und Monat schätzen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Bruttoentgelt | €/Monat | 3.000 |
| Nettoentgelt | €/Monat | 2.000 |
| Pflegeversicherung |  | Mit 1 Kind / unter 23 |

## Berechnung

Brutto-Krankengeld = Minimum aus (70 % × Brutto; 90 % × Netto; 135,63 € × 30)
Netto-Krankengeld = Brutto-Krankengeld × (1 − Abzugssatz)
Abzugssatz = 9,3 % (RV) + 1,3 % (AV) + Pflegeversicherungsanteil
Der Rechner nimmt die drei Werte, vergleicht sie und übernimmt den kleinsten. Der Tageshöchstbetrag wird mit 30 Tagen auf den Monat hochgerechnet, weil ein voller Kalendermonat nach § 47 Abs. 1 SGB V mit 30 Tagen angesetzt wird; das ergibt 4.068,90 €. Den Pflegeanteil wählen Sie nach Kinderzahl: 1,8 % bei einem Kind oder unter 23 Jahren, 2,4 % kinderlos ab 23, bei zwei bis fünf Kindern unter 25 Jahren jeweils 0,25 Punkte weniger je Kind. Der Betrag je Tag ist das monatliche Netto-Krankengeld geteilt durch 30. Rechtsgrundlagen: § 47 SGB V für die Höhe, § 170 SGB VI und § 347 SGB III für die hälftige Beitragstragung bei Rente und Arbeitslosenversicherung.

## Beispiel mit den Vorgabewerten

**Krankengeld netto (ca.):** 1.576,8 €
- Pro Tag (ca.): 52,56
- Brutto-Krankengeld: 1.800
- Sozialbeiträge: -223,2

## Grenzen

Vereinfachte Schätzung. Die genaue Höhe berechnet Ihre Krankenkasse. Krankengeld gibt es ab der 7. Woche der Arbeitsunfähigkeit. Keine verbindliche Auskunft.

## Quellen

- [§ 47 SGB V – Höhe und Berechnung des Krankengeldes](https://www.gesetze-im-internet.de/sgb_5/__47.html)
- [§ 48 SGB V – Dauer des Krankengeldes](https://www.gesetze-im-internet.de/sgb_5/__48.html)
- [§ 49 SGB V – Ruhen des Anspruchs](https://www.gesetze-im-internet.de/sgb_5/__49.html)
- [§ 170 SGB VI – Beitragstragung bei Sozialleistungen](https://www.gesetze-im-internet.de/sgb_6/__170.html)
- [§ 32b EStG – Progressionsvorbehalt](https://www.gesetze-im-internet.de/estg/__32b.html)
- [Bundesgesundheitsministerium – Krankengeld](https://www.bundesgesundheitsministerium.de/krankengeld)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
