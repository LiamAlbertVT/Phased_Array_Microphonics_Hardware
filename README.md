## Recent Updates
- Slightly modified schematic.
  - Incorporated all stages of dual op-amps.
  - Replaced VT_BIAS op-amp buffer with capacitor in accordance with the SSI2100 datasheet.
  - Adjusted symbol graphics.
- Resolved all footprint errors (all components now have matching footprints).
- Reflected changes in the parts list.

## TODO (Upcoming Commits)
- Draw PCB traces.
- Simulate passive blocks and those without ICs to verify intended behavior.
- Produce documentation to indicate:
  - Future plans & needs.
  - **Detailed** overview of the schematic.
    - It isn't crucial to overview the PCB, as it is simply a physical representation of the schematic.
    - I will likely provide a small section on it for debugging purposes.

## Future Plans
- Enable communication with Raspberry Pi Pico.
  - Will eventually add embedded directory to this repo with sample code.
- Revise schematic upon review (likely necessary--this is my first major PCB design).
