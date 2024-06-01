Totem wiring
============

This page describes the sound settings of the controller.


Microphone wiring
-----------------

- ``Grey`` (``GND`` and ``L/R``): ``GND``
- ``White`` (``WS``): GIO Pin ``15``
- ``Orange`` (``VDD``): ``3V3`` or 3.3V Pin
- ``Brown`` (``SD``): GIO Pin ``32``
- ``Green`` (``SCK``): GIO Pin ``14``


LED Wiring
----------

for all LEDs, connect:

- ``White`` (``V-in``): ``5V``
- ``Yellow`` (``GND``): ``GND``

and for the first LED, connect data to the ESP as well as its output to the next LEDs input:

- ``Blue`` (``D-in``): GIO Pin ``2``
- ``Green`` or ``Marked blue`` (``D-out``): ``Blue`` (``D-in``) of next LED

for the following LEDs, also connect:


- ``Green`` or ``Marked blue`` (``D-out``): ``Blue`` (``D-in``) 


Sound input pins
----------------

- Microphone type: ``Generic I2S``
- I2S SD pin: ``32``
- I2S WS pin: ``15``
- I2S SCK pin: ``14``


Batteries
---------
