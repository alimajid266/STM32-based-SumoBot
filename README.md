# STM32-based-SumoBot
Implemented a 2WD robot that remains inside a ring, and avoids obstacles. Used PWM, timers, sensors and motor driver to design the autonomous battery-powered robot. 
The following is the list of components used:
1. STM32-F401RE Nucleo-64
2. L298N Motor driver
3. Obstacle sensor (Infra-red)
4. Line sensor (Infra-red)
5. 2WD chassis with 2 DC motors
6. Two 3.7v batteries

The batteries power the motor driver, which has a 5v regulator built-in, which ultimately powers the microcontroller. T

