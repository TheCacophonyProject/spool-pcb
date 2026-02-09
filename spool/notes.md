# Notes

## Magnetic rotary sensor

This sensor uses a magnet attached to the shaft of the motor to detect the position of the shaft.
The magnet 469-1075-ND from digikey is used but using 2455-YB-076-1-ND with a hole in it might be more forgiving with the alignment of sensor -> magnet -> shaft.

## TODO

- [x] Add breakout pins for I2C bus.
- [x] Add ina216 current sensor for motor to detect stalls.
- [x] Cutouts in the PCB so you can see the horn rotating.
- [x] Bigger photo interrupters so less likely for horn to bump into them.
- [x] Add accelerometer so we can detect when the trap triggers?
- [x] Change current limit resistor to 2A for motor driver. Ω
- [ ] Add light sensor?
- [ ] Measure current as it gets reset and then back off and drive forward again. If the trap is reset properly the current draw from the motor should be much less after resetting the trap.
