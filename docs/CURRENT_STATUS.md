# Current Research Status — v0.3

## Verified findings

- Device under investigation: Swissphone Memo, 4 m variant presumed.
- IF receiver IC identified: MC3367DW.
- Quartz marking: `QS421 / 20.94 / TEW5E`.
- Measured peaks include approximately 20.99 MHz, 41.88 MHz and 83.76–83.78 MHz.
- Oscillator signal disappears when the stacked boards are disconnected.
- Pager contacts Pin 2 and Pin 3 idle near 3.0 V.
- Logic analyzer mapping: CH0 = Pin 2, CH1 = Pin 3.
- TEST002 showed no transitions during a 20 s idle capture.
- Pin 4 showed no activity in the available idle and power-on captures.
- The external connector on the photographed charging-cradle PCB is a BNC connector. Earlier RJ45/USB-B identifications were incorrect and have been withdrawn.

## Working hypotheses

- Pin 2 and Pin 3 form a low-voltage serial interface.
- The interface is likely CMOS/UART-like rather than true ±RS-232.
- Pin 1 may be associated with charging, cradle detection or power management.
- The BNC connector may route an antenna or RF test path; electrical tracing is still required.

## Open questions

- Exact function of all six pager contacts.
- Baud rate, framing and programming protocol.
- Role of the charging-cradle logic.
- Configuration storage location in the pager.
