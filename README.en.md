# GiantsBeaconApp
![AppIcon](beacon.png)

> [!NOTE]
> English Documentation: [docs/en/index.md](docs/en/index.md)
>
> [!NOTE]
> Deutsche README: [README.md](README.md)
> Deutsche Dokumentation: [docs/de/index.md](docs/de/index.md)


> [!WARNING]
> App files have not yet been uploaded!
> These will be uploaded as soon as possible as soon as an executable version is available
> (when I have finally fixed these stupid bugs 🐞🪲)
> But should be done at Easter 2024. 🐰🥚

## Überblick
The GiantsBeaconApp is a tool for controlling the Giant Software USB beacon (rotating beacon) without the Farming Simulator. The whole thing is intended to enable control without the LS and also to automate it.

> [!NOTE]
> _As the app is still under development, some functions may be limited or may not yet work as expected._ 😅

> [!TIP]
> The Beacon can be purchased here, for example:
> [Giants Amazon Store](https://amzn.to/3TVB6Tp)
> [Beacon](https://amzn.to/4ctbZzL)
>
> *Amazon Affiliate Links: if you buy the Beacon via this link, you support me and my project.* 🙏

## How the beacon works
- The beacon supports the following modes:
- round: Simulates the illumination of a rotating beacon
- blink: Simulates the flashing or blinking of a warning light.
- off: Switches the Beacon off.
_After 10 seconds (or earlier if an off command is sent), the beacon switches off automatically._
_To light up the beacon continuously, a command must be sent every 3 seconds._

## App Features 🚀
- UI for controlling the beacon: The app offers a GUI that can be used to control the beacon manually.
- Tray icon for background operation: The programme can run discreetly in the system tray so that it does not interfere.
- MQTT mode: Allows the beacon to be controlled via MQTT commands, ideal for smart home integrations.
- UI for settings: All configurations can be made via a GUI.
The settings are saved in a config.json file.

## Planned Features 📅
- Home Assistant integration: Only dummy functions are currently implemented. 🏠
- Module system: A module system to extend the core functionality of the app. 🧩
- Plugin system: A plugin system to integrate additional services and functions. 🧩🔌


# Further feature ideas💡
- RestServer: A small REST API to control the beacon. (e.g. for integration into other applications) 🌐
- Rest Read Mode: Query API calls with configurable responses to activate the beacon for certain events, such as new messages. 📩
- Integration with Leitstellenspiel.de (and/or the international offshoots): e.g. a function that enables the beacon to be activated when new alarms or voice requests are received in the game. 🚓🚒🚑
- Integration with Discord: A function that makes it possible to activate the beacon when certain events occur in Discord. 🎮
- The possibilities are endless! 🚀 But hard to do alone 😅, so anyone who wants to is welcome to work on this project and improve it. 🤝

## Screenshots
> [!NOTE]
> TODO! 😇

## Thanks
Many thanks to everyone who supports this project and provides feedback. 🙏

🤗 Special thanks to @Microgenital for the original Python script that served as the basis for this project
[Original Repository](https://github.com/Microgenital/Giants_Software_USB_Beacon/) 👍
Danke auch an Giant Software dass sie so ein cooles Produkt entwickelt haben. 🚜🚨

> [!NOTE]
> This tool is a hobby project and is continuously being developed.
> Feedback and suggestions are always welcome.
> Please understand that not all functions are available immediately or that unexpected behaviour may occur.

## License
This project is licensed under the MIT licence. [LICENSE.md](LICENSE.md).