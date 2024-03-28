# GiantsBeaconApp
![AppIcon](beacon.png)

> [!NOTE]
> Deutsche Dokumentation: [docs/de/index.md](docs/de/index.md)
> [!NOTE]
> English README: [README.en.md](README.en.md)
> English Documentation: [docs/en/index.md](docs/en/index.md)

> [!WARNING]
> App Dateien wurden noch nicht hochgeladen!
> Diese werden baldmöglichst hochgeladen, sobald eine lauffähige Version vorhanden ist.
> (wenn ich diese blöden bugs 🐞🪲 endlich gefixt habe)
> Sollte aber an Ostern 2024 erledigt sein. 🐰🥚

## Überblick
Die GiantsBeaconApp ist ein Tool um den Giant Software USB-Beacon (Rundumleuchte) auch ohne Landwirtschafts-Simulator zu steuern.
Das ganze soll zum einen die Steuerung ohne LS ermöglichen und zum anderen auch automatisieren.

> [!NOTE]
> _Da die App noch in Entwicklung ist, können manche Funktionen eingeschränkt sein oder noch nicht wie erwartet funktionieren._ 😅

> [!TIP]
> Der Beacon kann zB hier gekauft werden:
> [Giants Amazon Store[https://amzn.to/3TVB6Tp]]
> [Beacon[https://amzn.to/4ctbZzL]]
> *Amazon Affiliate Links: falls du den Beacon über diesen Link kaufst, unterstützt du mich und mein Projekt.* 🙏

## Funktionsweise des Beacons
- Der Beacon unterstützt die folgenden Modi:
- round: Simuliert das Leuchten einer Rundumleuchte.
- blink: Ähnelt dem Blinken oder Blitzen einer Warnleuchte.
- off: Schaltet den Beacon aus.
_Nach 10 Sekunden (oder früher, wenn ein off-Befehl gesendet wird) schaltet sich der Beacon automatisch aus._
_Um den Beacon kontinuierlich leuchten zu lassen, muss alle 3 Sekunden ein Befehl gesendet werden._

## Features der App 🚀
- UI zur Steuerung des Beacons: Die App bietet eine GUI, über die der Beacon manuell gesteuert werden kann.
- Tray-Icon für Hintergrundbetrieb: Das Programm kann diskret im Systemtray laufen, sodass es nicht stört.
- MQTT-Modus: Erlaubt die Steuerung des Beacons über MQTT-Befehle, ideal für Smart-Home-Integrationen.
- UI für Einstellungen: Alle Konfigurationen können über eine GUI vorgenommen werden.
Die Einstellungen werden in einer config.json-Datei gespeichert.

## Geplante Features 📅
- Home Assistant Integration: Aktuell sind nur Dummy-Funktionen vorhanden. 🏠
- Modul-System: Ein Modul-System, um die Kernfunktionalität der App zu erweitern. 🧩
- Plugin-System: Ein Plugin-System, um weitere Dienste und Funktionen zu integrieren. 🧩🔌


# Weitere Feature Ideen 💡
- RestServer: Eine kleine REST API zur Steuerung des Beacons. (z.B. für Integration in andere Anwendungen) 🌐
- Rest Read Mode: Abfrage von API-Calls mit konfigurierbaren Antworten, um den Beacon bei bestimmten Ereignissen, wie neuen Nachrichten, aktivieren zu können. 📩
- Integration mit Leitstellenspiel.de (und/oder auch die Internationalen Ableger): z.B. Eine Funktion, die es ermöglicht, den Beacon zu aktivieren, wenn neue Alarme oder Sprechwünsche im Spiel eingehen. 🚓🚒🚑
- Integration mit Discord: Eine Funktion, die es ermöglicht, den Beacon zu aktivieren, wenn bestimmte Ereignisse in Discord eintreten. 🎮
- Die möglichkeiten sind endlos! 🚀 Aber allein schwer zu schaffen 😅, daher ist jeder der möchte herzlich Willkommen, an diesem Projekt mitzuarbeiten und es zu verbessern. 🤝

## Screenshots
> [!NOTE]
> TODO! 😇

## Thanks
Vielen dank an alle, die dieses Projekt unterstützen und Feedback geben. 🙏

🤗 Ein Besonderer Dank geht an @Microgenital für das ursprüngliche Python-Script, das als Grundlage für dieses Projekt diente.
[Original Repository[https://github.com/Microgenital/Giants_Software_USB_Beacon/]] 👍

Danke auch an Giant Software dass sie so ein cooles Produkt entwickelt haben. 🚜🚨

> [!NOTE]
> Dieses Tool ist ein Hobbyprojekt und wird kontinuierlich weiterentwickelt.
> Feedback und Vorschläge sind immer willkommen.
> Bitte habe Verständnis dafür, dass nicht alle Funktionen sofort verfügbar sind oder es zu unerwartetem Verhalten kommen kann.

## License
Dieses Projekt ist unter der MIT-Lizenz lizenziert. [LICENSE.md](LICENSE.md).