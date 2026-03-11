## Recent Updates
- Completed schematic design, i.e.:
  - Chose all component values.
  - Selected specific parts for all active components (except for RLC---will use generic ones).
  - Revised logic and parts to obtain desired performance.
    - Removed second stage of summation amplifier.
    - Replaced THAT 1200 ICs with THAT 1512 ICs to provide preamplification[^1].
    - Switched status LED configuration to be in parallel with the NMOS bias path.
  - Completed power design[^2].
  - Revised schematic image & replaced *Images* directory with *Documents*. The schematic is found here.
  - Uploaded parts list with datasheets, purchase links, and amounts needed to *Documents*. I did not provide links to passive components (i.e. RLC).

## TODO (Next Commit)
- Design/acquire footprints for each part.
- Trace connections onto PCB layout.
  - Will likely be a four-layer board for ease of design. If I can work with two, we'll do it to save on cost.
- Revise schematic upon review (only if necessary; otherwise, you won't see it updated).

## Future Plans
- Enable communication with Raspberry Pi Pico.
  - Will eventually add embedded directory to this repo with sample code.
- Produce documentation to provide insight into the design.
  - I will not discuss design revisions... I will only discuss the final version that I produce this semester.
  - I will primarily discuss the schematic because the PCB only concerns routing.

[^1]: This is necessary to convert the small microphone outputs (μV) into signals that are readable (mV). The THAT 1200 ICs did not amplify.
[^2]: We will use a wall mount to convert the AC from an outlet to +15V, 1A DC, followed by a DC-DC converter to acquire two independent channels (±15V, 500mA each). The full power design will be outlined in the final documentation (see future plans).