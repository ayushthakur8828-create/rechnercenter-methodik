# Trockenbau-Rechner

Live: https://rechnercenter.de/trockenbau-rechner

Material für eine Trockenbauwand aus Wandlänge, Höhe, Ständerabstand und Beplankung berechnen.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Wandlänge | m | 5 |
| Wandhöhe | m | 2,5 |
| Achsabstand der CW-Ständer |  | 62,5 cm (Standard) |
| Beplankung je Seite |  | einlagig |

## Berechnung

- CW-Ständer: Wandlänge ÷ Achsabstand, abgerundet, plus eins; jeder Ständer in Raumhöhe.
- UW-Profil: zweimal die Wandlänge, oben und unten.
- Platten: Wandfläche × 2 Seiten × Lagen, plus 5 % Verschnitt, geteilt durch 2,5 m² je Platte.
- Schrauben: rund 15 je m² Plattenfläche.
- Fugenspachtel: rund 0,2 kg je m² Wandseite.

## Beispiel mit den Vorgabewerten

**Gipskartonplatten:** 11 Platten
- Wandfläche: 12,5 m²
- CW-Ständer: 9 Stück, 22,5 m
- UW-Profil (oben und unten): 10 m
- Plattenfläche beidseitig: 25 m²
- Schnellbauschrauben (rund): 375 Stück
- Fugenspachtel (rund): 5 kg
- Dämmung im Wandhohlraum: 12,5 m²

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
