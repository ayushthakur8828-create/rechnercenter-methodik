# Notarkosten-Rechner (Hauskauf)

Live: https://rechnercenter.de/notarkosten-rechner

Notar- und Grundbuchkosten beim Immobilienkauf nach GNotKG schätzen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Kaufpreis der Immobilie | € | 400.000 |
| Grundschuld (Kreditsumme) | € | 320.000 |

## Berechnung

G = einfache Gebühr nach Tabelle B (Geschäftswert = Kaufpreis)
Notar = G × (2,0 + 0,8) × 1,19
Grundbuch = G × (1,0 + 0,5)
Grundschuld = GS × 1,0 × 1,19 + GS × 1,0 (GS = Gebühr aus dem Grundschuldbetrag)
Summe = Notar + Grundbuch + Grundschuld + 100 € Auslagen
Die einfache Gebühr beginnt nach § 34 Abs. 2 GNotKG bei 15 € für Werte bis 500 € und steigt stufenweise, zwischen 200.000 € und 500.000 € um 50 € je angefangene 30.000 €. Der Satz 2,0 entspricht KV 21100 (Beurkundung eines Vertrags). Für Vollzug (KV 22110: 0,5) und Betreuung (KV 22200) setzt der Rechner zusammen pauschal 0,8 an. Beim Grundbuchamt fallen 1,0 für die Eigentumsumschreibung (KV 14110) und 0,5 für die Auflassungsvormerkung (KV 14150) an. Die Grundschuld kostet beim Notar 1,0 (KV 21200) und beim Grundbuchamt 1,0 (KV 14121). Umsatzsteuer von 19 % fällt nur auf Notargebühren an, nicht auf Gerichtsgebühren.

## Beispiel mit den Vorgabewerten

**Notar- & Grundbuchkosten (ca.):** 5.283,77 €
- Notar (Kaufvertrag, inkl. USt): 2.615,62
- Grundbuchamt (Eigentumsumschreibung, Vormerkung): 1.177,5
- Grundschuld (Notar inkl. USt, Grundbuchamt): 1.390,65
- Auslagen (pauschal): 100

## Grenzen

Gebühren nach Tabelle B GNotKG, Gebührensätze und Auslagen vereinfacht – der Notar rechnet exakt nach Geschäftswert und tatsächlichen Vorgängen ab.

## Quellen

- [GNotKG Anlage 1 (Kostenverzeichnis)](https://www.gesetze-im-internet.de/gnotkg/anlage_1.html)
- [GNotKG Anlage 2 (Gebührentabelle)](https://www.gesetze-im-internet.de/gnotkg/anlage_2.html)
- [GNotKG § 34 (Wertgebühren)](https://www.gesetze-im-internet.de/gnotkg/__34.html)
- [UStG § 12 (Steuersätze)](https://www.gesetze-im-internet.de/ustg_1980/__12.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
