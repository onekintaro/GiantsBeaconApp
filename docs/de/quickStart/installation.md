## Getting Started
### Installation aus dem Repository

- Klone das Repository:
```bash
git clone https://github.com/onekintaro/GiantsBeaconApp.git
```

- Navigiere in das Projektverzeichnis:
```bash
cd GiantsBeaconApp
```

- Optional: Erstelle ein virtuelles Python-Umfeld:
```bash
python -m venv .venv
```

- Installiere die benötigten Python-Bibliotheken mit dem folgenden Befehl:
```bash
pip install -r requirements.txt
```

- Starte die App mit dem folgenden Befehl:
```bash
python ./main.py
```
- Fertig! 🎉

#### Selbstkompilierung (Windows)
- Klone das Repository.
- Navigiere in das Projektverzeichnis.
- (Optional) Erstelle ein virtuelles Python-Umfeld.
- Installiere pyinstaller mit `pip install pyinstaller`.
- Kompiliere die App mit `pyinstaller --onefile --windowed --icon=beacon.ico main.py`.
- führe die Datei `dist/GiantsBeaconApp.exe` aus.
- Fertig! 🎉

### Installation aus dem Release (Windows)
- Lade die neueste Version aus den Releases herunter.
- Entpacke das Archiv und führe die Datei `GiantsBeaconApp.exe` aus.
- Fertig! 🎉