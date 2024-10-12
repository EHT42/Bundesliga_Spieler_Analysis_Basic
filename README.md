## 📊 Spieleranalyse der Bundesliga-Daten
Dieses Projekt analysiert Bundesliga-Spieler anhand einer CSV-Datei mit verschiedenen Merkmalen wie Alter, Preis, Position und Größe. Mithilfe von Pandas und Matplotlib werden die Daten visualisiert und ausgewertet.

# 🚀 Projektübersicht
Dieses Projekt führt eine detaillierte Analyse von Bundesliga-Spielern durch. Dazu gehört:

Einlesen und Vorbereiten der Daten.
Visualisierung von Attributen wie Spielernummern, Alter und Preisen.
Statistische Auswertungen wie Mittelwert, Median, Minimum und Maximum.
Überprüfung und Bereinigung von fehlenden Werten (NaN).
Plotten der Verteilungen von Alter und Spielernummer.
Analyse der Beziehung zwischen Alter und Preis mithilfe eines Punktediagramms und einer LOWESS-Kurve.
Gruppierung und Visualisierung von Spielergrößen nach Position.

# 📂 Datensatz
Der verwendete Datensatz ist eine CSV-Datei mit den folgenden relevanten Spalten:

name: Name des Spielers
age: Alter des Spielers
price: Marktwert des Spielers in Euro
position: Position des Spielers
height: Größe des Spielers
shirt_nr: Trikotnummer des Spielers

# 🔧 Wichtige Funktionen und Analysen
- 1. Visualisierung der Spielernummer-Verteilung
Ein Balkendiagramm zeigt die Anzahl der Spieler pro Trikotnummer.
- 2. Analyse der Altersverteilung
Ein horizontales Balkendiagramm zeigt die Anzahl der Spieler in verschiedenen Altersklassen.
Berechnung des Durchschnittsalters, des Medians sowie der jüngsten und ältesten Spieler.
- 3. Wertvollster Spieler
Das Skript findet den wertvollsten Spieler und zeigt seinen Namen, Preis und Alter an.
- 4. Punktediagramm: Alter vs. Preis
Darstellung der Beziehung zwischen dem Alter eines Spielers und seinem Marktwert.
Eine LOWESS-Kurve wird verwendet, um Trends in den Daten zu visualisieren.
- 5. Korrelationsberechnung
Berechnung des Korrelationskoeffizienten zwischen dem Alter und dem Marktwert der Spieler.
- 6. Positionsanalyse
Gruppierung und Visualisierung der Anzahl der Spieler nach ihrer Hauptposition.
Boxplot zeigt die Verteilung der Körpergrößen nach Position.
- 7. Größter und kleinster Spieler
Das Skript identifiziert den größten und kleinsten Spieler und gibt ihre Positionen und Namen aus.
