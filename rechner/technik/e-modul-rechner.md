# E-Modul Rechner

Live: https://rechnercenter.de/e-modul-rechner

Elastizitätsmodul aus Spannung und elastischer Dehnung berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Spannung | MPa | 210 |
| Elastische Dehnung | % | 0,1 |

## Berechnung

E = σ ÷ ε
σ = F ÷ A    (Kraft durch Querschnittsfläche)
ε = ΔL ÷ L₀    (Längenänderung durch Ausgangslänge)
Die Dehnung geben Sie in Prozent ein, der Rechner teilt sie durch 100: 0,1 % sind ε = 0,001. Spannung in MPa geteilt durch diese Zahl ergibt den E-Modul in MPa; durch 1.000 geteilt erhalten Sie GPa. 1 MPa entspricht 1 N/mm².
Die Formel ist das Hookesche Gesetz. Sie gilt nur, solange sich der Werkstoff nach dem Entlasten wieder vollständig zurückverformt. Oberhalb der Elastizitätsgrenze oder Streckgrenze wird die Dehnung bleibend, und das Verhältnis von Spannung zu Dehnung ist kein E-Modul mehr.

## Beispiel mit den Vorgabewerten

**Elastizitätsmodul:** 210 GPa
- Dehnung ε: 0,001
- E-Modul: 210.000 MPa

## Quellen

- [Wikipedia – Elastizitätsmodul, Tabellenwerte für Werkstoffe](https://de.wikipedia.org/wiki/Elastizit%C3%A4tsmodul)
- [EU-Kommission (JRC) – EN 1999 Eurocode 9: Aluminiumtragwerke](https://eurocodes.jrc.ec.europa.eu/EN-Eurocodes/eurocode-9-design-aluminium-structures)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
