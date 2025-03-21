# Projektarbeit
## 1. Overview
Dieses Projekt konzentriert sich auf die Implementierung eines maschinellen Lernmodells zur Vorhersage des Ergebnisses von Fußballspielen mit dem Ziel, eine möglichst hohe Vorhersagegenauigkeit zu erreichen. Als Kernstück des maschinellen Lernmodells wird ein Random-Forest-Algorithmus verwendet, der verschiedene spielbezogene Daten wie Mannschaftsleistungen, Statistiken und andere relevante Merkmale nutzt, um vorherzusagen, ob eine Mannschaft gewinnen, verlieren oder unentschieden spielen wird. Durch die Analyse historischer Spieldaten soll das Modell die Genauigkeit der Vorhersagen für zukünftige Fußballspiele optimieren.


## 2. How-To Run ?

Die folgenden Schritte beschreiben eine Methode zur Ausführung des Projekts. Bitte beachten Sie, dass dieser Prozess die Installation von **Miniconda** erfordert. **Miniconda** ist ein minimales Installationsprogramm für **Conda**, ein Paketverwaltungssystem und Umgebungsverwaltungswerkzeug.

1. **Install Miniconda:**
   - Laden Sie Miniconda von der offiziellen Website herunter und installieren Sie es: [Miniconda Installation](https://docs.conda.io/en/latest/miniconda.html)
   - Folgen Sie den Installationsanweisungen für Ihr Betriebssystem.

2. Nachdem Sie Miniconda installiert haben, öffnen Sie das **Terminal** und erstellen Sie eine neue Umgebung mit dem folgenden Befehl:
   ```conda create --name myenv python=3.8```

3. Aktivieren Sie die Umgebung:
   ```conda activate myenv```
4. Um das Projekt zu starten muessen folgende Pakete installiert werden: numpy, pandas, matplotlib, scikit-learn, pip, seaborn mit folgendem Befehl:
    ``conda install numpy, pandas, matplotlib, scikit-learn, pip, seaborn``
5. Ebenfalls gibt es 2 Pakete, welche nicht in der **Conda**-Libery enthalten sind und mit folgendem Befehl installiert werden müssen:
   ```pip install soccerdata``` & ```pip install beautifulsoup4```
6. Nach erfolgreicher Installation aller Pakete können Sie das Jupyter-Notebook öffnen und das Projekt starten.
   - Um das Projekt zu starten, verwenden Sie den folgenden Befehl:
      ```jupyter notebook```
7. Öffnen Sie nun die **Projektarbeit** Datei aus dem Repository 

8. Um das Projekt erfolgreich laufen zu lassen, muss noch die addtional_train.csv heruntergeladen und in das Projekt eingebunden werden(7. Zeile). <br>
   **WICHTIG ohne diesen Schritt wird es auch bei erfolgreicher Ausführung der vorherigen Schritte eine Fehlermeldung geben**


