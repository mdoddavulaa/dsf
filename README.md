# Kundendaten_Analyse

## Inhaltsverzeichnis

- [Projektübersicht](#projektübersicht)
- [Empfehlungen](#empfehlungen)
- [Datenquellen](#datenquellen)
  
### Projektübersicht

 Dieses Datenanalyseprojekt "Kundendaten-Analyse für Mall" verwendet Python, bei dem es das Ziel ist, wertvolle Erkenntnisse über die Präferenz von Menschen zu gewinnen, während man auf einigen historischen Daten kauft, die für die strategische Planung des Einkaufszentrums hilfreich sein werden, um den Gewinn zu steigern.
 
![Plot]
### Datenquellen

Custermer-Daten : Der primäre Datensatz, der für diese ANALYSE verwendet wird, ist die Datei "shopping-trends-updated.csv" mit detaillierten Informationen über Cusremer.

### Werkzeuge

- Python
- Pandas
- Matplotlib

### Datenreinigung/Vorbereitung

In der ersten Datenaufbereitungsphase führten wir folgende Aufgaben aus:

1. Datenbeladen und Prüfen
2. Datenreinigung und Formatierung.
3. Nullwerte und unerwünschte Spalten fallen lassen.

### Analyse der Sondierungsdaten

EDA nutzte die Analyse der Kundendaten, um wichtige Fragen zu beantworten, wie:

- welches ist am meisten gekauft?
- In welcher Saison kaufen Kunden mehr?
- welcher Modus wird meistens zur Zahlung verwendet?
- Wer kauft mehr Damen oder Herren ?

### Ergebnisse/ Befunde

Die Analyseergebnisse sind wie folgt zusammengefasst:

- Die Mall-Verkaufs-Ejaffung nahm stetig zu, schillernd und nuvaly.
- Männer sind die beste Kategorie des Permorings in Bezug auf Umsatz und Umsatz.
  
### Empfehlungen

Basierend auf der Analyse empfehlen wir folgende Aktionen:
- Investieren Sie in Marketing und Promotionen während der Hauptverkaufssaison, um den Umsatz zu maximieren.
- Implementieren Sie eine Kundensegmentierungsstrategie, um Kunden effektiv anzusprechen.

### Datenanalyse

Fügen Sie einige interessante Code/Features hinzu:
```py
name = df['Gender'].value_counts().index.tolist()         
value = df['Gender'].value_counts().tolist()
´´´


















