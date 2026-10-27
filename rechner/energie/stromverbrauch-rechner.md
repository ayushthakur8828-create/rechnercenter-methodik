# Stromverbrauch-Rechner (Geräte)

Live: https://rechnercenter.de/stromverbrauch-rechner

Stromverbrauch und Kosten eines Geräts pro Tag, Monat und Jahr berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Leistung des Geräts | Watt | 100 |
| Betriebsdauer | Std./Tag | 4 |
| Strompreis | ct/kWh | 35 |

## Berechnung

kWh pro Tag = Watt × Stunden pro Tag ÷ 1.000
kWh pro Jahr = kWh pro Tag × 365
Kosten = kWh × Strompreis (ct/kWh) ÷ 100
Der Rechner nimmt eine gleichbleibende Leistung über die gesamte angegebene Laufzeit an. Für den Monatswert verwendet er 30,44 Tage, also ein Zwölftel von 365,25 Tagen; die Jahreskosten beruhen auf 365 Tagen. Der Strompreis wird in Cent pro Kilowattstunde eingegeben, voreingestellt sind 35 ct/kWh. Die monatliche Grundgebühr Ihres Tarifs bleibt außen vor, weil sie unabhängig vom einzelnen Gerät anfällt.
Die Leistung finden Sie auf dem Typenschild oder dem Netzteil. Dort steht allerdings meist die maximale Leistungsaufnahme. Geräte mit Thermostat oder wechselnder Last (Kühlschrank, Waschmaschine, PC) ziehen diese Leistung nicht dauerhaft. Genauer wird es mit einem Energiekostenmessgerät für die Steckdose, das den tatsächlichen Verbrauch über einige Tage aufzeichnet.

## Beispiel mit den Vorgabewerten

**Stromkosten pro Jahr:** 51,1 €
- Pro Tag: 0,14
- Pro Monat: 4,26

## Grenzen

Kein Standby-Verbrauch außerhalb der eingegebenen Betriebszeit, keine taktenden Geräte mit schwankender Leistungsaufnahme (Kühlschrank, Wärmepumpe) und keine Anlaufströme. Für solche Geräte liefert ein Messgerät über mehrere Tage belastbarere Werte

## Quellen

- [Destatis: Stromverbrauch der privaten Haushalte nach Haushaltsgröße](https://www.destatis.de/DE/Themen/Gesellschaft-Umwelt/Umwelt/UGR/private-haushalte/Tabellen/stromverbrauch-haushalte.html)
- [Destatis: Stromabsatz nach Abnehmergruppen](https://www.destatis.de/DE/Themen/Branchen-Unternehmen/Energie/Verwendung/Tabellen/stromabsatz-haushalt.html)
- [Destatis: Energieverbrauch der privaten Haushalte für Wohnen](https://www.destatis.de/DE/Themen/Gesellschaft-Umwelt/Umwelt/UGR/private-haushalte/Tabellen/energieverbrauch-haushalte.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
