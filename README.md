# STM32F4_MorseCode_Transmitter

This is a project that transmits a user string into Morse code, as the output of an LED. A Morse Code is defined as a combination of dots ( . ), represented as OFF LED, and dashes ( - ), represented as ON LED. 

*Used Board: STM32F407VG Discovery Board.

The Current version (v1.0):
- Reads a string pre-defined by the user.
- Only capable of alphabets (A~Z).

The table below shows the used Morse Code and their Binarized Form (Message is transmitted from right to left):
| Character | Morse Code | Binarized |
| --- | --- | --- |
| A | - . | 0x10 |
| B | . . . - | 0x0001 |
| C | . - . - | 0x0101 |
| D | . . - | 0x001 |
| E | . | 0x0 |
| F | . - . . | 0x0100 |
| G | . - - | 0x011 |
| H | . . . . | 0bx0000 |
| I | . . | 0x00 |
| J | - - - . | 0x1110 |
| K | - . - | 0x101 |
| L | . . - . | 0x0010 |
| M | - - | 0x11 |
| N | . - | 0x01 |
| O | - - - | 0x111 |
| P | . - - . | 0x0110 |
| Q | - . - - | 0x1011 |
| R | . - . | 0x010 |
| S | . . . | 0x000 |
| T | - | 0x1 |
| U | - . . | 0x100 |
| V | - . . . | 0x1000 |
| W | - - . | 0x110 |
| X | - . . - | 0x1001 |
| Y | - - . - | 0x1101 |
| Z | . . - - | 0x0011 |
