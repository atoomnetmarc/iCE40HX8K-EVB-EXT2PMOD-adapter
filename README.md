# iCE40HX8K-EVB-EXT to 4 PMOD port adapter.

![](Kicad/iCE40HX8K-EVB%20EXT2PMOD%20adapter.jpg)

# Soldering

Solder every SMD component. Measure if 5V gets regulates to 3V3.

Solder every through-hole component. Measure for shorts between any of the signal pins on the tiny 1.27 header J1, correct if needed.

Clean the PCB.

# Pin mapping from PMOD to iCE40HX8K

Header on adapter (J2, J3, J4, J5 column) ➔ pin number on EXT connector (EXT column) ➔ FPGA pin when using EXTx (EXT1, EXT2, EXT3, EXT4 column) connector on FPGA board.

| J2    | EXT   | EXT1  | EXT2  | EXT3  | EXT4  |
| --    | --    | --    | --    | --    | --    |
| 1     | 14    | A7    | K12   | D15   | M5    |
| 2     | 18    | D8    | L13   | F14   | M4    |
| 3     | 22    | F7    | L12   | D16   | N3    |
| 4     | 26    | F9    | M13   | E16   | M3    |
| 7     | 12    | C7    | M16   | F11   | R1    |
| 8     | 16    | B8    | L14   | F12   | P2    |
| 9     | 20    | B9    | N16   | G12   | P1    |
| 10    | 24    | C8    | M14   | G13   | L5    |

| J3    | EXT   | EXT1  | EXT2  | EXT3  | EXT4  |
| --    | --    | --    | --    | --    | --    |
| 1     | 21    | A16   | E6    | K16   | N12   |
| 2     | 17    | E11   | A5    | J15   | M11   |
| 3     | 13    | B14   | A6    | K13   | E13   |
| 4     | 9     | B15   | C6    | J11   | F13   |
| 7     | 19    | C13   | B5    | K15   | T13   |
| 8     | 15    | C12   | D6    | K14   | D14   |
| 9     | 11    | D13   | D7    | L16   | B16   |
| 10    | 7     | C14   | B6    | M15   | C16   |

| J4    | EXT   | EXT1  | EXT2  | EXT3  | EXT4  |
| --    | --    | --    | --    | --    | --    |
| 1     | 35    | B10   | B3    | H16   | L1    |
| 2     | 31    | D11   | C5    | H13   | K3    |
| 3     | 27    | E10   | D5    | J13   | J1    |
| 4     | 23    | A15   | B4    | J14   | M12   |
| 7     | 37    | B11   | D4    | H14   | K4    |
| 8     | 33    | B12   | C4    | H11   | L4    |
| 9     | 29    | C11   | A1    | J16   | K1    |
| 10    | 25    | B13   | A2    | J12   | R16   |

| J5    | EXT   | EXT1  | EXT2  | EXT3  | EXT4  |
| --    | --    | --    | --    | --    | --    |
| 1     | 28    | A9    | P16   | G14   | M6    |
| 2     | 32    | E9    | P14   | G11   | L7    |
| 3     | 36    | D10   | R14   | G10   | K5    |
| 4     | 40    | A10   | D3    | H12   | L6    |
| 7     | 30    | D9    | P15   | F15   | N2    |
| 8     | 34    | C9    | R15   | F16   | M2    |
| 9     | 38    | A11   | C3    | G15   | L3    |
| 10    | 39    | C10   | E5    | G16   | M1    |

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)