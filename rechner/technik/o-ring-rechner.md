# O-Ring Rechner

Live: https://rechnercenter.de/o-ring-rechner

Nutmaße und passenden O-Ring aus Dichtdurchmesser und Schnurstärke berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Einbauart |  | Nut im Kolben / auf der Welle (außendichtend) |
| Dichtdurchmesser (Bohrung bzw. Welle) | mm | 40 |
| Schnurstärke d2 |  | 3,00 mm |
| Anwendung |  | Statisch (Teile bewegen sich nicht) |

## Berechnung

Nutgrund-Ø (außendichtend) = Bohrung − 2 × Nuttiefe
Nutgrund-Ø (innendichtend) = Welle + 2 × Nuttiefe
Verpressung = (d2 − Nuttiefe) ÷ d2 × 100 %
Innendurchmesser außendichtend: Der Ring sitzt auf dem Nutgrund. Nach dem ERIKS-Handbuch soll er im eingebauten Zustand höchstens um 5 % gedehnt sein. Geeignet sind also Ringe mit d1 zwischen Nutgrund ÷ 1,05 und Nutgrund. Als Vorschlag zeigt der Rechner den Wert bei 2 % Dehnung.
Innendurchmesser innendichtend: Der Ring darf laut ERIKS höchstens um 3 % gestaucht werden. Der Rechner nennt d1 zwischen Wellendurchmesser und Wellendurchmesser × 1,03.

## Beispiel mit den Vorgabewerten

**Passender O-Ring:** 34,7 × 3,00 mm
- Nuttiefe t (statisch): 2,30 mm
- Nutbreite ohne Stützring: 4,00 mm
- Nutbreite mit 1 / 2 Stützringen: 5,40 / 6,80 mm
- Nutgrund-Ø: 35,40 mm
- Verpressung: 23,3 %
- Radius am Nutgrund (Tabellenwert): 0,6 mm

## Quellen

- [Dichtelemente arcus GmbH – O-Ringe, Einbauräume (PDF)](https://static.o-ring.de/or_1.pdf)
- [ERIKS – Technisches Handbuch O-Ringe, Montagebedingungen (PDF)](https://o-ring.info/de/technisches%20handbuch/eriks%20-%20technisches%20handbuch%20-%20o-ring%20montagebedingungen.pdf)
- [ISO 3601-2:2025 – O-Ringe, Einbauräume](https://www.iso.org/standard/85921.html)
- [DIN ISO 3601-1 bei DIN Media](https://www.dinmedia.de/en/standard/din-iso-3601-1/191097119)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
