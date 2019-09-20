# ESC-test

HW: STM32F103C8T6 - (very cheap development board from china) 

IDE: STM32CubeIDE 1.0.2

Description
Using potenciometer on port A0 you can set PWM on A8 to adjust speed of ESC. Potenciometer sets pulse from 1-2ms (speed 0-100%).
Timer 1 is used with 72Mhz clock source reduced to 1Mhz. Period is set to 20ms.
Additonal 2 GPIO output pins are configured for testing C13 and C14.

Project is example of setting timer peripheal and ADC in a simple periodic polling mode. 
