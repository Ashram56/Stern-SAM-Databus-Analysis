# Stern-SAM-Databus-Analysis

Goal of this repository is to host documents and tools used in reverse engineering the Stern SAM communication bus between CPU board and IO/Driver board.

This bus is connected on J1 on the IO driver board, and based on schematics available is essentially an 8 bit data (pins 1 to 8), 4 bit adress (pin 12, 14, 16 and 18), IOStrobe (pin 15) and NBReset (pin 13).

CSV files are logic analyzer capture, open with Pulseview. Channel names are already defined
