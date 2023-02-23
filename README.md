# STM32F4_MorseCode_Transmitter

This is a project that transmits a user string into Morse code, as the output of an LED. A Morse Code is defined as a combination of dots ( . ), represented as OFF LED, and dashes ( - ), represented as ON LED. 

*Used Board: STM32F407VG Discovery Board.

The Current version (v1.0):
- Reads a string pre-defined by the user.
- Only capable of alphabets (A~Z).

The table below shows the used Morse Code (left-to-right) and their Binarized Form (right-to-left):

| Character | Morse Code | Binarized |
| --- | --- | --- |
| A | . - | 0b |
| B | - . . . | 0b |
| C | - . - . | 0b |
| D | - . . | 0b |
| E | . | 0b |
| F | . . - . | 0b |
| G | - - . | 0b |
| H | . . . . | 0b |
| I | . . | 0b |
| J | . - - - | 0b |
| K | - . - | 0b |
| L | . - . . | 0b |
| M | - - | 0b |
| N | - . | 0b |
| O | - - - | 0b |
| P | . - - . | 0b |
| Q | - - . - | 0b |
| R | . - . | 0b |
| S | . . . | 0b |
| T | - | 0b |
| U | . . - | 0b |
| V | . . . - | 0b |
| W | . - - | 0b |
| X | - . . - | 0b |
| Y | - . - - | 0b |
| Z | - - . . | 0b |
