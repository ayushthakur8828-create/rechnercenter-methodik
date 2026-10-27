# Gasverbrauch-Rechner m³ in kWh

Live: https://rechnercenter.de/gasverbrauch-rechner

Gaszähler-Kubikmeter mit Brennwert und Zustandszahl in kWh umrechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Gasverbrauch / Zählerdifferenz | m³ | 1.200 |
| Brennwert laut Rechnung | kWh/m³ | 10,3 |
| Zustandszahl laut Rechnung |  | 0,95 |

## Berechnung

Die Netzbetreiber rechnen nach dem DVGW-Arbeitsblatt G 685 „Gasabrechnung“ ab. Der Weg hat zwei Schritte:
- Betriebs- in Normkubikmeter: Der Zähler misst das Gas, wie es im Haus ankommt, also bei der dortigen Temperatur und dem dortigen Druck. Die Zustandszahl rechnet dieses Volumen auf den Normzustand um: 0 °C und 1.013,25 mbar.
- Normkubikmeter in Kilowattstunden: Der Brennwert gibt an, wie viel Energie ein Normkubikmeter enthält.
Der Rechner multipliziert beide Werte mit Ihrer Zählerdifferenz und rundet auf ganze Kilowattstunden. Die Zählerdifferenz ist der neue minus der alte Zählerstand, jeweils nur die Ziffern vor dem Komma oder genau wie auf der Rechnung angegeben.

## Beispiel mit den Vorgabewerten

**Abgerechneter Gasverbrauch:** 11.742 kWh
- Umrechnungsfaktor: 9,785 kWh je m³
- Gasmenge: 1.200 m³
- Rechenweg: 1.200 × 10,3 × 0,95

## Grenzen

Brennwert und Zustandszahl schwanken regional und über das Jahr; maßgeblich sind ausschließlich die Werte auf Ihrer Jahresrechnung. Keine Korrektur für Zählerwechsel oder Ablesefehler

## Quellen

- [Bundesnetzagentur – Umstellung von L- auf H-Gas](https://www.bundesnetzagentur.de/DE/Vportal/Energie/Netzanschluss/UmstellungGas/artikel.html)
- [Verbraucherzentrale – Von L-Gas auf H-Gas](https://www.verbraucherzentrale.de/wissen/energie/heizen-und-warmwasser/von-lgas-auf-hgas-darum-wird-das-erdgas-umgestellt-13264)
- [New Netz – Thermische Abrechnung nach DVGW G 685 (PDF)](https://new-netz.de/mediathek/Informationsblatt_zur_thermischen_Abrechnung_nach_DVGW_Regelwerk_G685.pdf)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
