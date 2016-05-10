HIDIRT for STM32F103C8T6-DevBoard
=================================

A PCB that contains the most neccessary components to operate the HIDIRT firmware on the common and cheap STM32F103C8T6 DEV BOARD. All parts are THT components. As only a small number of traces is needed one could even solder it onto a breadboard.

Pictures of the STM32F103C8T6 DEV BOARD can be found [here](https://www.mikrocontroller.net/topic/350400#4343199) and a schematic [here](https://www.mikrocontroller.net/topic/350400#4042953).

Unfortunately this microcontroller only incorporates a USART bootloader, but none for USB. Therefore any USART interface is needed to flash a USB bootloader once. This will also work with a USB-USART bridge.