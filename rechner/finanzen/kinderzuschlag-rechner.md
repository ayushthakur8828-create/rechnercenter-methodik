# Kinderzuschlag-Rechner

Live: https://rechnercenter.de/kinderzuschlag-rechner

Kinderzuschlag aus Einkommen, Warmmiete und Kinderzahl schätzen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Kinder unter 25 im Haushalt | Anzahl | 2 |
| Elternteil(e) |  | Paar |
| Bruttoeinkommen der Eltern | €/Monat | 2.800 |
| Zu berücksichtigendes Erwerbseinkommen der Eltern | €/Monat | 2.100 |
| Sonstiges anrechenbares Elterneinkommen | €/Monat | 0 |
| Warmmiete inklusive Heizkosten | €/Monat | 900 |
| Anrechenbares Einkommen der Kinder | €/Monat gesamt | 0 |

## Berechnung

Elternbedarf = Regelbedarf + Warmmiete × Wohnkostenanteil
Anrechnung = (Elterneinkommen − Elternbedarf) × 45 %
Zuschlag = 297 € × Kinder − 45 % × Kindeseinkommen − Anrechnung
Rechtsgrundlage ist § 6a BKGG. Der Regelbedarf beträgt 563 € für Alleinerziehende und 2 × 506 € für Paare. Erwerbseinkommen über dem Elternbedarf mindert den Zuschlag zu 45 %, anderes Einkommen wie Arbeitslosen- oder Krankengeld in voller Höhe (Absatz 6). Der Rechner setzt das so um: Sonstiges Einkommen, das den Elternbedarf schon für sich allein übersteigt, wird voll abgezogen, der übrige Überschuss zu 45 %. Das Ergebnis wird auf volle Euro gerundet.

## Beispiel mit den Vorgabewerten

**Kinderzuschlag (ca.):** 392 €
- Höchstbetrag gesamt: 594
- Eigener Bedarf der Eltern: 1.651
- Elternanteil an Wohnkosten: 71 %
- Anrechnung Elterneinkommen: 202,05

## Grenzen

Vorprüfung nach § 6a BKGG und dem KiZ-Merkblatt der Familienkasse. Das anrechenbare Einkommen nach SGB II, Mehrbedarfe, Wohngeld, Vermögen und die Verteilung von Kindeseinkommen können das Ergebnis verändern. Verbindlich entscheidet die Familienkasse.

## Quellen

- [§ 6a BKGG – Kinderzuschlag](https://www.gesetze-im-internet.de/bkgg_1996/__6a.html)
- [Merkblatt Kinderzuschlag (Familienkasse, Stand Juli 2026)](https://www.arbeitsagentur.de/datei/KiZ2-MerkblattKinderzuschlag_ba015395.pdf)
- [Familienkasse: Kinderzuschlag – Anspruch, Höhe, Dauer](https://www.arbeitsagentur.de/familie-und-kinder/kinderzuschlag-verstehen/kinderzuschlag-anspruch-hoehe-dauer)
- [Bundesagentur: Grundsicherungsgeld löst Bürgergeld ab](https://www.arbeitsagentur.de/grundsicherung-loest-buergergeld-ab)
- [Bundestag: Entwurf Haushaltsbegleitgesetz 2027 (Drucksache 21/7860)](https://dserver.bundestag.de/btd/21/078/2107860.pdf)
- [§ 66 EStG – Höhe des Kindergeldes](https://www.gesetze-im-internet.de/estg/__66.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
