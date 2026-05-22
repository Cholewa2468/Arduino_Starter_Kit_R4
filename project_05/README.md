# Arduino Starter Kit R4 - Project 05 - Mood Cue

## Decscription

This project presents a simple mechanism for operating a servo motor. The motor adjusts to a position dependent on the position of the potentiometer.

### Code notes:
```
The signal received from the potentiometer represents the voltage value from 0V to 5V (Pin A0). The servo motor is connected to pin 9 (white signal cable). When servo motor starts to move, it draws more current than if it were already in motion. This will cause a dip in voltage on board, so the 100μF capacitor is placed across power and ground.
```

---
| Project | Description |
| :---: | :--- |  
| ![Schema No. 1](/project_05/schema/schema1.png) | <p>Ingredients</p><li>1x Servo motor</li><li>1x Potentiometer</li><li>1x Motor arm</li><li>2x Capacitor (100μF)</li> |