# MyD1
This is stuffs for my Micromake D1 including modified Repetier firmware basing on Repetier version 0.92.9 that fits to my Micromake D1 3D printer.

Current changes:
* Disable pull-up resistors of X, Y, Z endstops to use optical endstops.
* G29 to strobes at 3 points of a triangles.
* Default parameters for:
  * Extruder steps/mm (459.18)
  * Z probe offset (7.48)

Models:
* Belt tensioner x3 (4mm thick).
* Remixed mini z-probe.

## Upload firmware to board
Using the hex file (without bootloader) in the HEX folder to upload to board.
