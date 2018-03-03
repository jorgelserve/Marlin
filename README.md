To download: use the download button (Download ZIP) at the top right -----^


=== IMPORTANT - READ THIS FIRST! ===

Marlin - The Diamond Hotend version
===

This is Marlin version 1.0 adapted to fit the bq Prusa i3 Hephestos printer by default

The precompiled HEX-files can be installed using the "Install custom firmware..." feature found in Cura

Supported boards are:
 * RAMPS (33)
 * RUMBA (80)

Prior to compiling, in Configuration.h you must select the appropriate board by uncommenting one of following lines:
* //  #define MOTHERBOARD BOARD_RAMPS_13_EFB
* //  #define MOTHERBOARD BOARD_RUMBA

This firmware is made to compile with Arduino IDE version 1.0.6

Using Arduino IDE version 1.5 or any higher will result in compile errors

General Marlin firmware documentation at http://www.marlinfirmware.org/
Documentation for the Diamond Hotend at http://reprap.org/wiki/Diamond_Hotend/
