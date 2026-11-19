## Recent Updates

- Corrected the 48 V phantom-power wiring on all four XLR microphone inputs and added a filter before each delay chip.
- Reduced open PCB connections from 64 to 11. All 11 are in the power section.

## TODO (Upcoming Commits)

- Review the Q6 gate drive and the pin assignments on regulators U16 and U18 before finishing the power routing.

## Future Plans

- Test the Raspberry Pi Pico's delay clocks and its connection to the ADC.
  - Add Pico sample code in an `embedded/` directory.
- Build one microphone channel on a breadboard and check its gain, filter response, and delay before ordering the PCB.
