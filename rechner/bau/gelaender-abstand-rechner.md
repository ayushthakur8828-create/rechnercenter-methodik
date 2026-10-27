# Geländer-Rechner

Live: https://rechnercenter.de/gelaender-abstand-rechner

Stäbe und Abstände eines Geländers.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Lichte Breite zwischen den Pfosten | mm | 1.200 |
| Breite eines Stabs | mm | 20 |
| Gewünschter maximaler lichter Abstand | mm | 120 |

## Berechnung

Zahl der Zwischenräume = aufrunden((Öffnung + Stabbreite) ÷ (Höchstabstand + Stabbreite))
Stäbe = Zwischenräume − 1
lichter Abstand = (Öffnung − Stäbe × Stabbreite) ÷ Zwischenräume
Der Achsabstand – Mitte Stab bis Mitte Stab – ist lichter Abstand plus Stabbreite. Mit ihm markieren Sie die Bohrungen.

## Beispiel mit den Vorgabewerten

**Benötigte innere Stäbe:** 8 Stück
- Gleiche Zwischenräume: 9 Stück
- Tatsächlicher lichter Abstand: 115,56 mm
- Achsabstand Stab zu Stab: 135,56 mm
- Gesamtbreite der Stäbe: 160 mm
- Kontrollmaß: 1.200 mm

## Grenzen

Keine Ermittlung des rechtlich zulässigen Abstands und keine Prüfung von Geländerhöhe, Kletterwirkung, Lasten, Befestigung, Korrosion, Toleranzen oder Landesbauordnung.

## Quellen

- [LBOAVO Baden-Württemberg § 3 – Umwehrungen](https://lxgesetze.de/lboavo/3)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
