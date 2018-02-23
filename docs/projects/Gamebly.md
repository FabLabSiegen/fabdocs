# Gamebly
## Projektstatus

__Aktuell keine Entwicklung.__

## Projektidee
Ein Tisch mit einer LED-Matrix in der Mitte, auf dem man spielen kann.

## Projektteilnehmer
Jasmin und Zack

Kontakt: Zack

## Verwendete Hardware
* NodeMCU-Board
* Apa102C-LED-Streifen
    * 3 x 5 Meter
    * 30 LEDs pro Meter


## Installation zur Benutzung des NodeMCU-Boards
[Es müssen Treiber installiert werden (CP2102)](https://www.silabs.com/products/mcu/Pages/USBtoUARTBridgeVCPDrivers.aspx)

### Anschluss Apa102C-LED-Streifen
![Schaltplan](http://www.elec-tron.org/wp-content/uploads/2015/12/nodetoapaq102.png)

Daten: Grün
Takt: Gelb
5V: Rot
Erde: Schwarz

## Verwendete Tools
* [Plattformio](http://platformio.org) als Entwicklungsumgebung
* [Git-Hub](http://github.com) zur Versionierung des Codes

## Code
[https://github.com/d-amend/Gamebly](https://github.com/d-amend/Gamebly)

## Related Work

### All Pixel

[https://github.com/ManiacalLabs/AllPixel](https://github.com/ManiacalLabs/AllPixel)

#### Pro

#### Kontra

- kein Mapping

### Open Pixel control

Ansteuerung der LEDs über das Netzwerk

[http://openpixelcontrol.org](http://openpixelcontrol.org)