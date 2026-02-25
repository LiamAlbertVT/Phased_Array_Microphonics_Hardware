## Recent Updates
- Calculated/estimated component values for *most* of the circuit (see TODO).
- Added power circuitry to handle voltage drops and avoid the use of phantom power for areas other than the XLR I/O.
- Removed redundant circuits/components.
- Organized schematic for readability.
- Updated schematic image.

## TODO (Next Commit)
- Design buck (DC-DC) converter (need to choose component values and optimize layout if possible).
- Find specific and optimal parts for all active and passive components.
- Find optimal ±15V supplies (dual-power supplies).

## Future Plans
- Translate schematic into PCB.
  - Design/import footprints for each component (this will be fun...).
  - Determine number of PCB layers (we can probably use 4 thanks to budget).
  - Trace valid connections to mimic schematic.
- Get schematic reviewed (can be done during PCB design process).
- Enable communication with Raspberry Pi Pico.
  - Will eventually add embedded directory to this repo with sample code.