RamBoExtension by Enggmaug -
==============

Electronics Project to extend RamBo 1.2 capabilities to 7 Steppers, 5 Thermistors and 5 Heating resitors/cartridges/beds.
Rambo 1.2 Project can be found here : https://github.com/ultimachine/RAMBo

This project uses the RamBo 1.2 Silk to position the connectors.
The design was greatly inspired by the design of the Rambo 1.2 card, in order to be consistent in how in/outs are driven.
As most users of the RamBo will plug in a LCD, the LCD extension card will block the way in between PWM Connector and Stepper Extension Connectors.
This is why the extension does not directly plug in the PWM extension connector, but will use a flex or strap wire instead.


Required Hardware :
-----------------

In order to use the extension, you need :
- 1 Rambo 1.2 card
- Pololu A4988 Stepper Driver Modules (1 for each stepper added, up to 2)
- Extra Steppers (up to 2), thermistor (1), heating resistor or cartridge (1).

In order to achieve 5 hot ends control, you plug in :
- Heating Bed Output
- Heat 0
- Heat 1
- Fan 0 (same output design as a heater)
- Heat3 on the extension.


Configuring the extension :
-------------------------
You shall select microstep values with jumpers.

To Be Completed






