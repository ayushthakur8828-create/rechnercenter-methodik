# Rentenbesteuerung-Rechner

Live: https://rechnercenter.de/rentensteuer-rechner

Schätzen, wie viel Einkommensteuer auf Ihre gesetzliche Rente anfällt.

## Eingaben

| Feld | Einheit | Vorgabe |
|---|---|---|
| Monatliche Bruttorente | €/Monat | 1.600 |
| Jahr des Rentenbeginns |  | 2.024 |
| Bruttorente im ersten vollen Rentenjahr | €/Monat | 0 |
| Zusatzbeitrag der Krankenkasse | % | 2,9 |
| Pflegeversicherung |  | Kinderlos, ab 23 Jahren (4,2 %) |
| Veranlagung |  | Einzelveranlagung |
| Weitere Einkünfte (Miete, Zinsen …) | €/Jahr | 0 |

## Berechnung

Rentenfreibetrag = Jahresbruttorente im ersten vollen Rentenjahr × (100 % − Besteuerungsanteil)
steuerpflichtiger Teil = aktuelle Jahresbruttorente − Rentenfreibetrag
zvE = steuerpflichtiger Teil + weitere Einkünfte − Kranken- und Pflegeversicherung − 102 € − 36 €
Steuer = Tarif nach § 32a EStG (bei Zusammenveranlagung Splitting)
Der Besteuerungsanteil steht in der Tabelle in § 22 Nr. 1 Satz 3 Buchstabe a EStG. Er stieg von 50 % (2005) jährlich um 2 Prozentpunkte bis 80 % (2020), danach um 1 Punkt auf 82 % (2022). Seit dem Wachstumschancengesetz steigt er ab 2023 nur noch um 0,5 Punkte pro Jahr und erreicht 100 % erst bei Rentenbeginn 2058.
Vom steuerpflichtigen Teil zieht der Rechner die Beiträge zur Kranken- und Pflegeversicherung als Sonderausgaben ab. Angesetzt werden für pflichtversicherte Rentner 7,3 % plus der halbe Zusatzbeitrag (Standard 2,9 %, also 1,45 %) sowie der volle Pflegebeitrag: 3,6 % mit Kind, 4,2 % kinderlos, mit Abschlägen für mehrere Kinder unter 25. Hinzu kommen der Werbungskosten-Pauschbetrag von 102 € für Renten (§ 9a EStG) und der Sonderausgaben-Pauschbetrag von 36 € (§ 10c EStG).

## Beispiel mit den Vorgabewerten

**Einkommensteuer auf die Rente:** 143 €
- Jahresbruttorente: 19.200
- Rentenfreibetrag: 3.264
- Steuerpflichtiger Anteil: 15.936
- Kranken-/Pflegeversicherung: 2.486,4
- zu versteuerndes Einkommen: 13.311,6

## Grenzen

Schätzung mit dem Einkommensteuertarif 2026 für gesetzlich krankenversicherte Rentner. Nicht berücksichtigt werden unter anderem Kirchensteuer, Solidaritätszuschlag, individuelle Sonderausgaben und private Krankenversicherung. Verbindlich ist der Steuerbescheid. Keine Steuerberatung.

## Quellen

- [§ 22 EStG – Besteuerungsanteil von Renten](https://www.gesetze-im-internet.de/estg/__22.html)
- [§ 32a EStG – Einkommensteuertarif](https://www.gesetze-im-internet.de/estg/__32a.html)
- [§ 9a EStG – Werbungskosten-Pauschbetrag 102 €](https://www.gesetze-im-internet.de/estg/__9a.html)
- [§ 56 EStDV – Pflicht zur Steuererklärung](https://www.gesetze-im-internet.de/estdv_1955/__56.html)
- [BMG: Finanzierung der Pflegeversicherung](https://www.bundesgesundheitsministerium.de/themen/pflege/online-ratgeber-pflege/die-pflegeversicherung/finanzierung)
- [§ 3 SolzG – Freigrenze Solidaritätszuschlag](https://www.gesetze-im-internet.de/solzg_1995/__3.html)

---
Stand der Werte: 30. September 2026. Fehler gefunden? Bitte ein Issue anlegen.
