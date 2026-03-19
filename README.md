## Recent Updates
- Updated schematic with optimized op amps and buck converter components.
- Revised parts list to reflect these changes.
- Added footprints for all components.
- Generated PCB without traces.
  - There were warnings and errors. See *Motherboard* &rarr; *PCB_UPDATE_REPORT* (listed at the bottom).
  - I'm pushing to make these changes available to the cloud, but I will to determine how catastrophic the errors are before making significant trace designs.

## TODO (Upcomming Commits)
- Rectify pad errors when generating PCB.
- Draw PCB traces.
  - Will likely use a four-layer board for ease of design. If I can work with two, we'll do it to save on cost.
- Revise schematic upon review (likely necessary--this is my first major PCB design).

## Future Plans
- Enable communication with Raspberry Pi Pico.
  - Will eventually add embedded directory to this repo with sample code.
- Produce documentation to provide insight into the design.
  - I will not discuss design revisions... I will only discuss the final version that I produce this semester.
  - I will primarily discuss the schematic because the PCB only concerns routing.