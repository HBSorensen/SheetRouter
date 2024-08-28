# Sheet router Project #
This project is an upgrade of my existing router project.

Design goal is to take a half size plywood sheet (800x1200 mm2) utilizing as much of the it as possible on the existing frame (tilting table).

## Project Structure ##
### Mechanical ###
Holds all the files related to the mechanical parts of the project. 
![Overall Design](https://github.com/HBSorensen/SheetRouter/blob/main/Overalldesign.png)

(Requires FreeCad with Assembly 4 plugin). 

### Electronics ###
Holdes all the files related to the electronics parts. 
GRBL is to be used on an Arduino Mega/Uno for controlling the hardware. 

Offline controller is planned to be a custom Linux image running on a Raspberry Pi.
