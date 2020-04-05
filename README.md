# pipe pincher software
a device that pinches pipes in alternance, made to cut one circuit while the other is open.
This repo hosts the source code for the microcontroller (here an Arduino Nano, but it is compatible
with mostly anything Arduino compatible...)

## requirements : 
None

## GPIO : 
* dirPin = D7 (stepper driver direction)
* stepPin = D6 (step signal, controls the movement and speed)
* Left switch : D5;
* Right switch : D4;
* potentiometer (used to set speed) : A7
* I2C is wired in the default Arduino way, but not used here;
* Free button/gpio : D13 (unused)
