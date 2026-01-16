# Praktikum 2026

## WebTigerPython

Wir haben uns mit den Grundlagen der Python-Programmierung beschäftigt. Dazu haben wir das Tutorial und die Online-Entwicklungsumgebung des TigerPython-Projektes verwendet.

- [Python-Online Tutorial](https://python-online.ch/)
- [WebTigerPython](https://webtigerpython.ethz.ch/)

## Entwicklung mit Github und vscode

### Erstellung Github-Accounts und Anlegen der Testprojekte

- Account auf [https://github.com](Github) angelegt
- Dort jeweils ein leeres Testprojekt erstellt:
  - [3KaMa3/First-project](https://github.com/3KaMa3/First-project)
  - [Yanana48/chiikawa101](https://github.com/Yanana48/chiikawa101)

### Installation der lokalen Entwicklungsumgebung auf Windows

Im Terminal-Fenster:

```bat
winget install Git.Git
winget install python
winget install vscode
```

### vscode starten und Projekt clonen

- vscode über das Startmenü aufrufen
- Github-Account anmelden, wird für den Github-Copilot und zum Clonen benötigt
- Neues Git-Projekt von Github clonen

### Neues Programm erstellen

- `helloworld.py` oder ähnliche Datei neu anlegen
- Simplen Code einfügen, bspw. `print("Hello world!")`
- Speichern und mit dem Play-Button zum Test ausführen

### Änderung committen und zu Github pushen

- In der Git-Ansicht (links die drei Punkte) die neue Datei mit `+` stagen
- Message eingeben und *Commit* drücken

Damit ist die Änderung im lokalen Repository, aber noch nicht bei Github sichtbar.

- *Synchronisieren* drücken oder *Push* aus Menü auswählen

Damit werden alle lokalen Commits zu Github hochgeladen.

Um neue Änderungen von Githib in das lokale Repository zu holen, ebenfalls *Synchronisieren* drücken oder *Pull* aus dem Menü auswählen.

### Verwendung des KI-Agenten

Über den Chat in vscode kann jederzeit die KI eingebunden werden. Diese kann auch den geöffneten Code bearbeiten oder sogar neuen erstellen.

Empfehlungen dazu:

- präzise Anfragen stellen
- kurze Aufgaben definieren.
- unbedingt den generierten Code gründlich lesen und verstehen
- keine großen Projekte vom Agenten erstellen lassen, immer nur kleine Abschnitte
- im Zweifelsfall die KI nach Links zur Dokumentation fragen und diese lesen
