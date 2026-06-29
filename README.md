# MCU Data Logger PCB

A 4-layer PCB designed in KiCad for an ATmega328P-AU based microcontroller data logger. The board integrates a DS1337 real-time clock, dual 24LC1025 EEPROMs, ICSP programming interface, UART, I²C, and GPIO expansion headers.

## Features

- ATmega328P-AU Microcontroller
- DS1337 Real-Time Clock (RTC)
- Dual 24LC1025 EEPROMs
- 16 MHz System Crystal
- 32.768 kHz RTC Crystal
- ICSP Programming Header
- UART Header
- I²C Expansion Header
- GPIO Expansion Header
- Battery Input Header
- Status LEDs
- Four Mounting Holes
- Custom PCB Artwork

## PCB Specifications

| Parameter | Value |
|----------|-------|
| PCB CAD | KiCad |
| PCB Layers | 4 |
| MCU | ATmega328P-AU |
| RTC | DS1337 |
| EEPROM | 2 × 24LC1025 |
| Crystal | 16 MHz |
| RTC Crystal | 32.768 kHz |

## Project Structure

```
.
├── .gitignore
├── MCU-Datalogger.kicad_pcb
├── MCU-Datalogger.kicad_pro
├── MCU-Datalogger.kicad_sch
└── README.md
```

## Verification

- ✅ Electrical Rules Check (ERC) Passed
- ✅ Design Rules Check (DRC) Passed
- ✅ Fully Routed PCB
- ✅ 3D PCB Model Generated

## Software Used

- KiCad


## Author

**Parthiv K R**

