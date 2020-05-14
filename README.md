# swing-windows-opener
This repository contain all you need to create from scratch a swing dual external windows opener Apple Homekit opener: from mechanical to electronical parts.

This project would help everyone to create itself an automated swing window opener using modern vocie assistant at lowest price (in Italy commercial product have a price of 500€ for each window, and there isn't a commercial product able to communicate with Alexa, Google Home and Apple HomeKit)

REQUIREMENTS:
- manage power on n.2 DC Motor 24VDC?;
- delay in opening and closing: when opening, first open right window and then left window; when closing first close left window and then right window;
- opening/closing slowdown;
- 2 motor to open swing windows at 180 degree
- End of stroke of the motors should be controlled measuring the current or power
- 230 VAC
- control using Apple HomeKit via WiFi using ESP82xx
- not use 433 MHz
- manual motor release
- irreversible engine
- metal box to install DC motor, electronic mainboard
- little space to install between external and internal window
- installatin in top of existing window
- protection IP44

OPTIONAL:
- solar panels +  battery
- wall button
- control suing Alexa, Google Home


BOM:
- n.2 metal crank mechanism to connect DC motor to windows
- n.2 DC motor 24VDC
- n.1 power supply 220V->24VDC
- n.2 metal engine support?
- n.4 end of stroke (micro-switch?)
- n.1 metal box
- electronic for control delay and PM
- ESP8266 con modulo WIFI
- DUAL CONTROL DRIVER L298N (Max 2A) oppure POLOLU (Max 5A) control driver H-BRIDGE????


EXAMPLE of commercial products:
- CAME VOILA' https://www.came.com/it/installatori/soluzioni/automazioni-tende-tapparelle-e-scuri/blinds/voila


AAA looking for CAD designer 2D/3D, mechanical expert, eletronical expert
