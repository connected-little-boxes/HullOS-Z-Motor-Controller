# Hullos-Z Arduino Motor control board

## Notes

### CPU Speed
Note that the CPU speed is set in Platform.ini

```
board_build.f_cpu = 16000000L
```
The above setting is for the Arduino Pro-mini 5v version. Might want to make some more build configurations for Arduino Uno and Pro-mini 3.3v.

## HullOS Version R2.2

* Changed serial baud rate to 115200
* startMotors in MotorControl now stops a motor if the requested speed is 0. The previous version left the motor running if the speed was 0.

## HullOS Version R2.3

* Changed serial baud rate to 19200 to improve connection quality. 
