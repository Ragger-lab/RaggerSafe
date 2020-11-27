# RaggerSafe
RaggerSafe is een IOT project om de tuin te monitoren.

-------------------------------------------------------------------------------

De meeste taken heb ik al apart van elkaar getest, maar nu moet 
alles nog in een mooi jasje worden gegoten en tot een geheel komen.

Momenteel gebruik ik de volgende onderdelen :
- Ardunio Uno.
- RaspBerryPi 4
- DF-Robot Keypad shield.
- ESP32-Cam 2x ( met externe antenne ).
- Stroom- ( tot 30Amp ), Ultrasone- , PIR- , Flame- en Gas-detectie modules.
- Temparatuur, Vochtigheid en Licht sensoren.
- 4x Relais bord.
- Diverse reed kontakten
- Step down converter ( 12v in / 5v uit ).
- 12V Accu / Powerbank.


Als het goed gaat moet dit de volgende taken kunnen uitvoeren : 


Stroomverbruik :
- Stroomverbruik en Totale kosten berekenen voor 1x een 220v 16Amp groep.

Alarmen : 
- Alarm geven bij te hoge stroom >=10Amp
- Alarm geven bij onderbreking deurcontact
- Alarm geven bij gas-detectie
- Alarm geven bij vlam-detectie (vuur)
- Alarm geven bij beweging ( PIR / Video en Ultrasoon)

Video : 
- Beweging detectie => Video / Stillshot
- Timed Stillshot´s
- Playback / Live stream

IOT :
- 4x Relay
- 4x 5v I/O on ESP32-Cam

Diverse :

- Wifi / Bluetooth Connected
- Data en Video Cloud 
- LCD and pusbutton switches
- UPS

Web :

- Read / Change Status IOT
- Live / Playback Video
- Read log file´s
- Admin RaggerSafe


----------------- _/oo\_ ----------------- 
                  112020



