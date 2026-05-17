# Parts List

This file tracks the main components used for the solar panel power meter. Part numbers may change as the design is tested and revised.

## Main Components

| Category | Part | Value / Model | Quantity | Purpose | Source / Part Number | Notes |
|---|---|---:|---:|---|---|---|
| Solar source | Solar panel | Voltaic P124 / Adafruit 5368 | 1 | Input power source for testing | Adafruit 5368 | 1.22 W panel, about 6 V at max power |
| Controller | Arduino-compatible UNO | UNO R3 | 1 | Reads sensor values and controls LCD output | TBD | USB-powered during testing |
| Display | LCD1602 display | 16x2 LCD | 1 | Displays voltage, current, and power | TBD | Parallel LCD wiring |
| Op-amp | Microchip MCP6022 | MCP6022-I/P | 2 | Signal conditioning for current sensing | MCP6022-I/P-ND | DIP package for breadboard use |
| Diode | Rectifier diode | 1N4007 | 10 | Reverse-polarity/protection testing | 1N4007-E3/54GICT-ND | Through-hole diode |
| Potentiometer | Potentiometer | 10kΩ | 1 | LCD contrast adjustment / voltage divider testing | TBD | Breadboard-friendly preferred |
| Switch | Slide switch | SPDT | 2 | Power/control switching | Jameco SS-12E17-G020 | Already ordered |
| Battery connector | 9V snap connector | 9V battery snap | 3 | Battery testing and backup source | Jameco BS-IC-1007 | Already ordered |
| Clips | Alligator clips | Screw/barrel clips | 2 packs | Temporary test connections | Jameco SF-105B-R | Already ordered |

## Resistors

| Value | Quantity | Source / Part Number | Notes |
|---:|---:|---|---|
| 1Ω | 10 | CF14JT1R00CT-ND | 1/4W axial |
| 5Ω | 10 | 13-PNP1WVJR-52-5R1CT-ND | 1W axial |
| 10Ω | 10 | CF14JT10R0CT-ND | 1/4W axial |
| 50Ω | 10 | 13-MFR25SFBE52-50R-ND | 1/4W axial |
| 100Ω | 10 | CF14JT100RCT-ND | 1/4W axial |
| 220Ω | 10 | CF14JT220RCT-ND | 1/4W axial |
| 330Ω | 10 | CF14JT330RCT-ND | 1/4W axial |
| 500Ω | 10 | 13-MFR25SFBE52-500R-ND | 1/4W axial |
| 1kΩ | 10 | CF14JT1K00CT-ND | 1/4W axial |
| 1.5kΩ | 10 | CF14JT1K50CT-ND | 1/4W axial |
| 2kΩ | 10 | CF14JT2K00CT-ND | 1/4W axial |
| 5.1kΩ | 10 | CF14JT5K10CT-ND | Used in place of 5kΩ |
| 10kΩ | 10 | CF14JT10K0CT-ND | 1/4W axial |
| 20kΩ | 10 | CF14JT20K0CT-ND | 1/4W axial |
| 51kΩ | 10 | CF14JT51K0CT-ND | Used in place of 50kΩ |
| 100kΩ | 10 | CF14JT100KCT-ND | 1/4W axial |
| 200kΩ | 10 | CF14JT200KCT-ND | 1/4W axial |
| 500kΩ | 10 | 13-HHV-25JR-52-500KCT-ND | 1/4W axial |
| 1MΩ | 10 | CF14JT1M00CT-ND | 1/4W axial |

## Capacitors

| Value | Quantity | Source / Part Number | Notes |
|---:|---:|---|---|
| 0.1µF | 10 | BC1101CT-ND | Ceramic, non-polarized |
| 1µF | 10 | 732-8851-1-ND | Electrolytic, polarized |
| 10µF | 10 | P5148-ND | Electrolytic, polarized |
| 22µF | 10 | P1177-ND | Electrolytic, polarized |
| 47µF | 10 | 1572-1477-ND | Electrolytic, polarized |
| 220µF | 10 | P5153-ND | Electrolytic, polarized |

## Notes

- Electrolytic capacitors are polarized. The negative stripe must be connected to the lower-voltage side of the circuit.
- Low-value resistors can draw high current if connected directly across a power source. They should be used carefully during load testing.
- Part numbers are tracked so the build can be repeated or revised later.
