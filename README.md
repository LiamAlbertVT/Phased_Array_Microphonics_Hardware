## Recent Updates
- Determined that new delay modules are needed (shocker, right?). Researched a bit and found the [SSI2100 IC](https://www.soundsemiconductor.com/downloads/ssi2100datasheet.pdf). This is a modern [bucket-brigade device (BBD)](https://en.wikipedia.org/wiki/Bucket-brigade_device) with high clock speeds (up to 2MHz) compared to other BBDs which are clocked much slower. Use the equation in the hardware documentation to optimize spacing.
- Appended high-frequency filtration logic to the output of the SSI2100. I need to know which frequencies to attenuate before I override them.
- Improved logic throughout the circuit to avoid discrepancies.

## TODO
- Determine microphone connectivity (I/O current, port type, etc.).
- Determine resistor values (will complete after rudimentary design is finished).
- Assess feedback module.
- Add design documentation and maintain it.

## Future Plans
- Translate schematic into PCB.
- Enable communication with Raspberry Pi Pico.
  - Will eventually add embedded directory to this repo.
