# U-Wert-Rechner

Live: https://rechnercenter.de/u-wert-rechner

Wärmedurchgangskoeffizient eines Bauteils aus bis zu vier Schichten berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Bauteil und Wärmestromrichtung |  | Außenwand · horizontaler Wärmestrom |
| Schicht 1 · Dicke | mm | 15 |
| Schicht 1 · λ-Wert | W/(m·K) | 0,7 |
| Schicht 2 · Dicke | mm | 240 |
| Schicht 2 · λ-Wert | W/(m·K) | 0,33 |
| Schicht 3 · Dicke | mm | 160 |
| Schicht 3 · λ-Wert | W/(m·K) | 0,04 |
| Schicht 4 · Dicke | mm | 20 |
| Schicht 4 · λ-Wert | W/(m·K) | 0,8 |

## Berechnung

R je Schicht = Dicke in m ÷ λ
R gesamt = Rsi + Σ R + Rse
U = 1 ÷ R gesamt
Rsi und Rse sind die Wärmeübergangswiderstände an der inneren und äußeren Oberfläche nach DIN EN ISO 6946: bei Wänden mit waagerechtem Wärmestrom 0,13 und 0,04 m²K/W, bei Dächern mit Wärmestrom nach oben 0,10 und 0,04 m²K/W.
Beispiel: 160 mm Dämmung mit λ = 0,035 haben einen Widerstand von 0,16 ÷ 0,035 = 4,571 m²K/W. Zusammen mit den übrigen Schichten und den Übergangswiderständen ergeben sich 5,515 m²K/W, also U = 1 ÷ 5,515 = 0,181.

## Beispiel mit den Vorgabewerten

**Wärmedurchgangskoeffizient:** 0,181 W/(m²·K)
- Gesamtwiderstand Rₜ: 5,515 m²K/W
- Materialschichten ΣR: 5,345 m²K/W
- Oberflächen Rsi + Rse: 0,17 m²K/W
- Gesamtdicke: 435,0 mm
- Wärmestrom bei 20 K Differenz: 3,63 W/m²
- GModG-Anlage-7-Vergleich: ≤ 0,24 W/(m²·K)
- Schicht 1 · R: 0,021 m²K/W
- Schicht 2 · R: 0,727 m²K/W
- Schicht 3 · R: 4,571 m²K/W
- Schicht 4 · R: 0,025 m²K/W

## Grenzen

Vereinfachte stationäre Berechnung homogener Schichten; kein GModG-, Förder-, Wärmebrücken- oder Feuchteschutznachweis und kein Ersatz für bauphysikalische Fachplanung.

## Quellen

- [GModG Anlage 7 – Höchstwerte der Wärmedurchgangskoeffizienten bei Änderung bestehender Gebäude](https://www.gesetze-im-internet.de/geg/anlage_7.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
