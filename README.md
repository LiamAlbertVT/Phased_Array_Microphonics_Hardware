## Recent Updates
- Added switching stage to the input to allow one to compare the beamforming model with a single microphone (unoptimized).
- Incorporated THAT1200 differential amplifiers to precisely combine the hot and cold channels of the XLR cable outputs.
- Determined a necesseceary separation between phantom power (+48V) and general power (for the remainder of the circuit).
  - Designed buck converters and other circuits (with inverting ICs and linear regulators) to provide fixed voltages throughout the circuit.
- General improvements.
- Updated schematic image and removed high-level diagram (obsolete).

## TODO (Next Commit)
- Determine component values (this will take a while... I'll work to have it done by the beginning of March).
- Determine specific component types.
- Get design reviewed.
- Provide design documentation.

## Future Plans
- Translate schematic into PCB.
- Enable communication with Raspberry Pi Pico.
  - Will eventually add embedded directory to this repo with sample code.