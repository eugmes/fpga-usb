# USB Interface Extension
This is a small board that uses MAX3453E chip to add a USB interface for an FPGA board.
This extension is designed to fit inta an extension connector on Numato Mimas V2 FPGA board, but it
probably could be used with other boards that use 6x2 connectors.

# Connector Pinout

| Pin    | Function | Description                           |
|--------|----------|---------------------------------------|
| 1      | ENUM     | Enumerate function select input       |
| 2      | BD       | Bus detection output                  |
| 3      | RCV      | Differential receiver output          |
| 4      | NC       | No connection                         |
| 5      | V-       | Negative receiver output/driver input |
| 6      | V+       | Positive receiver output/driver input |
| 7      | SUS      | Suspend input                         |
| 8      | #OE      | Output enable                         |
| 9, 10  | GND      | Ground                                |
| 11, 12 | VCC      | Logic supply (1.65V to 3.6V)          |

See also MAX3453E datasheet.

# PCB Layout
The PCB layout project is also shared on [OSH Park](https://oshpark.com/projects/5NEpfuXA).

# License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />
<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">USB Interface Extension</span>
by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Ievgenii Meshcheriakov</span>
is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
