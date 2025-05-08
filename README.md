# Company Performance Analysis - [Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiMjFlZjFhZTgtYTUyYi00ODAzLWIwMzctOGMzMTk5MWU5YTMxIiwidCI6IjA1MDRmNzIxLWQ0NTEtNDAyYi1iODg0LTM4MTQyODU1OWUzOSIsImMiOjh9&pageName=a3dbadc54af337fe9bbc)

## Inhaltsverzeichnis
1. [Projektübersicht](#projektübersicht)  
2. [Motivation](#motivation)  
3. [Methodik](#methodik)  
4. [Dashboard-Beschreibung](#dashboard-beschreibung)  
   - [Selektion & Kennzahlen (Top-Leiste)](#selektion--kennzahlen-top-leiste)  
   - [Bottom-10 YTD vs PYTD | Country](#bottom-10-ytd-vs-pytd--country)  
   - [Gross Profit YTD vs PYTD | Month – Country – Product (Wasserfall)](#gross-profit-ytd-vs-pytd--month--country--product-wasserfall)  
   - [Gross Profit YTD vs PYTD | Month (gestapelte Säule)](#gross-profit-ytd-vs-pytd--month-gestapelte-säule)  
   - [Account Profitability Segmentation | GP% und Gross Profit (Streudiagramm)](#account-profitability-segmentation--gp-und-gross-profit-streudiagramm)  
5. [Interpretation und Hintergründe](#interpretation-und-hintergründe)  
   - [Soziale Faktoren](#soziale-faktoren)  
   - [Politische Rahmenbedingungen](#politische-rahmenbedingungen)  
   - [Wirtschaftliche Einflüsse](#wirtschaftliche-einflüsse)  
6. [Fazit](#fazit)

## Projektübersicht
Dieses Power BI-Projekt analysiert die finanzielle Performance eines fiktiven Unternehmens (Plant Co.) für das Jahr 2023. Im Zentrum stehen Kennzahlen wie Bruttogewinn (Gross Profit), Year-to-Date-Vergleiche zum Vorjahr (PYTD) und verschiedene Betrachtungsebenen nach Monat, Land und Produkttyp.

## Motivation
Die laufende Überwachung von Bruttomargen und Abweichungen zum Vorjahr ist essenziell für fundierte Geschäftsentscheidungen. Durch die visuelle Aufbereitung in Power BI können Trends, Problembereiche und profitable Segmente rasch identifiziert werden – eine wichtige Grundlage für Kostenoptimierungen, Portfolioanpassungen und strategische Planungsprozesse.

## Methodik
1. **Datenaufbereitung:** Import und Transformation der ERP- und CSV-Daten in Power Query, Berechnung der YTD-Werte, Zuordnung der Produktkategorien  
2. **Kennzahlen-Berechnung:** Ermittlung von Gross Profit YTD, PYTD, Abweichung (YTD vs PYTD) und Bruttogewinnmarge (GP%)  
3. **Visualisierung:** Aufbau von Dropdown-Selektoren, KPI-Kacheln, Wasserfalldiagramm, gestapelten Säulen und Streudiagramm in Power BI  

## Dashboard-Beschreibung

### Selektion & Kennzahlen (Top-Leiste)
Ein Dropdown-Menü erlaubt die Auswahl des Analysejahres (hier: 2023). Dynamische KPI-Kacheln zeigen:  
- **Gross Profit YTD** (5,42 Mio.)  
- **PYTD-Abweichung** (−0,27 Mio.)  
- **Gross Profit YTD aktuelles Jahr** (5,15 Mio.)  
- **Bruttogewinnmarge (GP%)** (39,62 %)  
Diese Übersicht liefert einen schnellen Überblick über Zielerreichung und Margenentwicklung.

### Bottom-10 YTD vs PYTD | Country
Eine farbkodierte Heatmap listet die zehn Länder mit den stärksten Rückgängen im Bruttogewinn (YTD vs PYTD). China führt die Liste mit −0,405 Mio. an, gefolgt von Schweden und den Vereinigten Staaten. Die Tiefstwerte markieren Regionen mit operativen Problemen oder rückläufiger Nachfrage. Diese Analyse hilft, gezielte Maßnahmen in Problem-Märkten zu priorisieren.

### Gross Profit YTD vs PYTD | Month – Country – Product (Wasserfall)
Ein Wasserfalldiagramm zeigt die Entwicklung des kumulierten Bruttogewinns im Jahresverlauf im Vergleich zum Vorjahr, aufgeschlüsselt nach Monat, Land (Aggregat) und Produktkategorien:  
- **Grün:** positive Abweichungen (Erhöhungen)  
- **Rot:** negative Abweichungen (Abnahmen)  
Die stärksten Zuwächse im Mai (0,09 Mio.) deuten auf saisonale Nachfragespitzen hin, während der Einbruch im Dezember (−0,15 Mio.) auf erhöhte Kosten oder Nachfragerückgänge zum Jahresende zurückzuführen ist.

### Gross Profit YTD vs PYTD | Month (gestapelte Säule)
Ein gestapeltes Säulendiagramm zeigt den Bruttogewinn YTD je Monat, aufgeteilt nach Produkttypen **Indoor**, **Landscape** und **Outdoor**, mit der roten Linienserie als **Value PYTD** des Vorjahres. Der Verlauf demonstriert, dass:  
- **Indoor-Produkte** im Frühjahr stark wachsen (März–Mai).  
- **Landscape** konstanten Beitrag übers Jahr hinweg leisten.  
- **Outdoor** im Sommer und Herbst höhere Margen erzielen.  
Der Vergleich zur PYTD-Linie macht Abweichungen und Trends im Produktmix sichtbar.

### Account Profitability Segmentation | GP% und Gross Profit (Streudiagramm)
Ein Streudiagramm zeigt einzelne Konten (Accounts) mit **Bruttogewinnmarge (GP%)** auf der Y-Achse und **Bruttogewinn YTD** auf der X-Achse. Eine gestrichelte rote Linie markiert den durchschnittlichen GP% (ca. 40 %). Die Verteilung verdeutlicht:  
- Accounts rechts oben sind strategisch wichtigste Kunden (hohe Profitabilität und hohe Deckungsbeiträge).  
- Links unten liegen unprofitablere Segmente, die besonderes Augenmerk auf Kostenoptimierung erfordern.  
- Die Verteilung zeigt, wie Margen und Volumina korrelieren.

## Interpretation und Hintergründe

### Soziale Faktoren
Kundenanforderungen und Lieferkettenverhalten haben direkten Einfluss auf Bruttogewinnmargen. In Ländern mit hohem Umweltbewusstsein (z. B. Deutschland, Skandinavien) werden Indoor- und Landscape-Produkte stärker nachgefragt, da energieeffiziente Lösungen gewünscht sind. Saisonspezifische Festtage und Urlaubszeiten beeinflussen die Performance der Outdoor-Produkte, insbesondere in Nordamerika und Asien.

### Politische Rahmenbedingungen
Zölle und Handelspolitik wirken sich auf Materialkosten aus: Erhöhte Importzölle auf Komponenten verteuern Produkte und drücken Margen. Förderprogramme für nachhaltige Bauprojekte können den Absatz von Landscape-Produkten fördern. Landesbezogene Subventionen im Wohnungsbau steigern die Nachfrage nach Garten- und Outdoor-Lösungen, während in anderen Regionen politische Unsicherheiten als Hemmnis wirken.

### Wirtschaftliche Einflüsse
Rohstoffpreise (Stahl, Holz, Kunststoffe) und Wechselkursschwankungen wirken sich unmittelbar auf Herstellkosten und somit Bruttogewinn aus. Inflation und Zinssätze beeinflussen Investitionsentscheidungen von Kunden und Jahresendgeschäft. Saisonale Kostenstrukturen (z. B. Energiekosten im Winter) sowie Logistikengpässe während globaler Krisen erklären Einbrüche in bestimmten Monaten.

## Fazit
Das Power BI-Dashboard erlaubt eine ganzheitliche Analyse der Cost- und Revenue-Treiber auf globaler Ebene. Identifizierte Trendbrüche und Margenschwankungen liefern wichtige Steuerungsimpulse für Marketing, Vertrieb und Supply Chain. Eine regelmäßige Aktualisierung und Erweiterung um zusätzliche Kontextdaten (z. B. Währungseinflüsse) wird dringend empfohlen, um die Entscheidungsqualität weiter zu steigern.
