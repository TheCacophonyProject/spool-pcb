# Notes

## Magnetic rotary sensor

This sensor uses a magnet attached to the shaft of the motor to detect the position of the shaft.
The magnet 469-1075-ND from digikey is used but using 2455-YB-076-1-ND with a hole in it might be more forgiving with the alignment of sensor -> magnet -> shaft.

## TODO

- Add breakout pins for I2C bus.
- Add ina216 current sensor for motor to detect stalls.
- Cutouts in the PCB so you can see the horn rotating.
- Bigger photo interrupters so less likely for horn to bump into them.
- Add plastic bit on the backside that will interfere with the horn if it is in the wrong place (so it can't be put together incorrectly)
- Add accelerometer so we can detect when the trap triggers?
