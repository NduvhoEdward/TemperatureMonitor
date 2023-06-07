
# Temperature Monitoring Assembly Implementation

This repository contains an assembly language program for monitoring temperature and displaying it on three seven-segment displays. The program is designed for the ATmega328P microcontroller.

## Description

The `main.asm` file in this repository contains a program that reads the temperature using an analog-to-digital converter (ADC) and displays the temperature digits on three seven-segment displays. The program utilizes timers and interrupts to control the display and conversion processes.

The program follows the following main steps:

1. Setting up the ADC and enabling the ADC interrupt.
2. Configuring the timer for handling display on-time delays.
3. Configuring another timer for triggering temperature conversions at defined intervals.
4. Enabling interrupts and setting up the sleep mode for power-saving.
5. Displaying the separated digits of the temperature on the seven-segment displays.
6. Splitting the temperature into individual digits for display.
7. Disabling the ADC and returning to the main loop.

## Hardware Setup

To use this program, you need the following hardware components:

- ATmega328P microcontroller.
- Three seven-segment displays.
- Analog temperature sensor.
- Supporting circuitry (resistors, capacitors, etc.).

Please refer to the microcontroller datasheet and the specific circuit diagram for proper connections and component values.

## Usage

To use this program, follow these steps:

1. Set up the hardware components as per the circuit diagram and connections.
2. Install the appropriate compiler and development environment for programming the ATmega328P microcontroller.
3. Copy the `main.asm` file from this repository into your project folder.
4. Open the file in your assembly language development environment.
5. Compile and upload the program to the microcontroller.
6. Connect the power supply and observe the temperature displayed on the seven-segment displays.

**Note:** Ensure that you have the necessary knowledge and experience in working with microcontrollers and assembly language programming.

## Limitations

- This program is specific to the ATmega328P microcontroller and may not work with other microcontrollers without modifications.
- The accuracy and precision of temperature measurement depend on the analog sensor used and the calibration of the system.
- The program assumes a specific hardware configuration and pin assignments, which may need adjustment based on your setup.

## License

This assembly implementation is provided under the [MIT License](LICENSE), allowing you to use, modify, and distribute the code for both commercial and non-commercial purposes. However, please note that the author shall not be liable for any damages or misuse of the code.

## Author

This program was created by Nduvho (ID: 1490804).

## References

- ATmega328P Datasheet (Refer to the official datasheet for detailed information on the microcontroller)
- Assembly Language Programming Resources
```
