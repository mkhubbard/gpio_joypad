# gpio_joypad
GamePad emulator using GPIO and analog multiplexer for Odroid C

This tool requires WiringPi. It creates a Gamepad using linux's uinput and reads states from GPIO.
This tool has been designed to work with a MC14051 analog multiplexer and 2 PSP thumbsticks.

It has been created for my GameOdroiD C0, a home made portable retrogaming console based on an Odroid C0 SBC.
More on http://www.bluemind.org/gamodroid-c0-odroid-based-portable-retrogaming

How to compile: 
gcc -o gpio_joypad gpio_joypad.c -lwiringPi -lpthread
