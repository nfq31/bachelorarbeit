In diesem Ordner befinden sich alle zusätzlichen Inhalte zu meiner Bachelorarbeit "Numerische Simulation von Wetterderivaten".

Im Ordner "Plot Durchschnittstemperatur" befinden sich zwei Dateien, um die Durchschnittstemperatur zu plotten. Einmal 
für 2 Jahre (zwei_jahre_plot.m) und für 30 Jahre (dreissig_jahre_plot.m). Der Matlab Code "histogramm_temp.m" plottet ein Histogramm der täglichen Temperaturveränderungen in Ulm.

Im Ordner "Mittelwertsfunktion" und "Standardabweichung und Rückkehrgeschwindigkeit" werden die verschiedenen Parameter, die für die SDE benötigt werden, geschätzt.
In der Datei mittelwertsfunktion.m werden die Parameter A,B,C und phi berechnet. Die Datei std_rueckgabeparam.m beschäftigt sich mit der Schätzung der Standardabweichung und der Parameter für die Rückkehrgeschwindigkeit. Die Datei "empirische_std.m" plottet ein Schaubild der Standardabweichung in Ulm innerhalb eines Jahres.

Im Ordner "Simulation Temperaturverläufe" befindet sich einmal die Funktion "temp_paths.m", welche anhand der geschätzten Parameter Temperaturverläufe von Ulm simulieren kann. Die Datei "simulation_pfade.m" plottet einen Vergleich der täglichen Durchschnittstemperatur und der Simulation von Temperaturverläufen mit dem in Abschnitt 3.4 vorgestellten Verfahren.
In der Datei "simulation_jahr_2021.m" wird nochmal ein Schaubild geplottet, welche die Mittelwertsfunktion, Simulation von Temperaturverläufen und die tägliche Durschnittstemperatur in Ulm vergleicht.

Im Ordner "Numerische Experimente" befindet sich eine Datei "monte_carlo.m". Diese berechnet den Preis einer Wetteroption mittels Monte-Carlo-Simulationen.
Die Datei "emm.m" berechnet den Preis einer Wetteroption mittels risikoneutraler Bewertung.
In der Datei "numerische_experimente" befinden sich alle Rechnungen und Plots welche in Kapitel 5 vorgestellt wurden. 









