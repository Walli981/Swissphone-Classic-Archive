# Current research status: Swissphone Memo

## Verified observations

- Crystal marking: `QS421 / 20.94 / TEW5E`
- IC in the RF/IF section: `MC3367DW`
- Measured spectral components: approximately 20.99 MHz, 41.88 MHz and 83.76–83.78 MHz
- The signal is present only while both PCB assemblies are connected.
- Pins 2 and 3 idle at approximately 3.0 V.
- TEST002 showed no transitions on pins 2 and 3 during a 20-second capture.
- Pin 4 remained low in all captures made so far.
- The external connector on the investigated charging cradle is a BNC socket.

## Supported interpretation

Pins 2 and 3 are very likely part of a serial interface using logic levels around 3 V. Direct connection to conventional RS-232 voltage levels is therefore not recommended.

## Working hypotheses

- Pin 1 may provide charging, cradle detection or power-management functionality.
- Pin 4 may be used only in a special operating state.
- Channel selection may use an electronically tuned oscillator circuit.

## Open questions

- TX and RX direction
- Baud rate and protocol
- Functions of pins 1 and 4
- Signal path of the BNC connector
- Configuration storage location
