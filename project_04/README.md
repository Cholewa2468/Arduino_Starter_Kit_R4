# Arduino Starter Kit R4 - Project 04 - Color Mixing Lamp

## Decscription

Three phototransistors generate a current proportional to the amount of light absorbed. Each phototransistor represents a different color (red, green, or blue). Covering or additionally exposing one of the phototransistors causes changes in the RGB LED colors.

### Code notes:
```
The signal received from the phototransistors can range from 0 to 1023, so it must be divided by 4 due to the maximum capacity of the PWN (pulse width modulation) output pins, which is 255. Setting up the serial port made possible reporting the sensors readings and calculated LED light levels to the computer.
```

---
| Project | Description |
| :---: | :--- |  
| ![Schema No. 1](/project_04/schema/schema1.png) | <p>Ingredients</p><li>3x Phototransistor</li><li>3x Resistor (220Ω)</li><li>3x Resistor (10kΩ)</li><li>1x RGB LED</li><li>3x Gels (red, green, blue)</li> |