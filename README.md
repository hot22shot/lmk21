# Scrap files for my Zuoya LMK21 numpad

* definition : contains the definition json files for the numpad to be recognized by the usevia.app application.
* layout : via json layouts for the numpad.
* zuoya : contain an exe that will flash the lmk21 numpad to its default configuration.

Basic instructions for pairing the numpad with via web application :
1. Connect the numpad
2. Open https://www.usevia.app/
3. Go to the Settings tab
4. Enable 'Show Design tab'
5. In the Design tab, enable 'Use V2 definitions (deprecated)'
6. Now click on 'Load' and browse to the JSON definition file
7. Connection request should pop-up

> [!TIP]
> For saving layout not working in the web app : https://github.com/the-via/releases/issues/241

> [!WARNING]
> Zuoya is on the license violator list of QMK (https://docs.qmk.fm/license_violations) it is unlikely we'll have a release of the QMK firmware from them.
> Additionnaly the MCU used in the LKM21 numpad to provide tri-connectivity modes may not be officaly supported by QMK.
