# Dual-HC-SR04-on-STM32F4
A Example of "How to drive 2 or more HC-SR04 via Timer" for STM32F407G-DISC1.

I think it's very interesting see different way to reach the same objetive.
In this case, I enabled/disabled the interrupt of different channel of the timers instead of determinate which channel produced the interrupt. For the trigger pins, I configured a PWM signal of a period of 100ms and a Ton= 10us using one of the timmer of 32 bits
