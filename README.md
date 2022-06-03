# ESP32 Plotter Controller PCB
 
Released under an MIT licence, no warranty implied or given, use at own risk etc etc.

This is a two axis stepper controller based on the ESP32 and TMC2130 stepper drivers. It is intended to be used with drawing machines and plotters.

Firmware https://github.com/theworkisthework/Grbl_Esp32 (This is a Fork of Grbl_Esp32, if its out of date, you probably only need the config file from this fork). Tested with standard and corexy kinematics and a solenoid/relay for the spindle.

Revision B (aka 'Emerald Dingo') embeds an ESP32 module on the board along with comms and USB C connector. The peripheral connectors are all JST PH2.0 connectors. Also added E-Stop connector (J18).

[Schematic]( https://github.com/theworkisthework/ESP32_Plotter_Controller/blob/main/ESP32_Plotter_Controller_Schematic_RevB1.pdf )

![Pinmap]( https://github.com/theworkisthework/ESP32_Plotter_Controller/blob/main/Plotter_pinmap.png )
