# Communication Protocols

![Verilog](https://img.shields.io/badge/HDL-Verilog-blue?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

## Overview

This repository serves as an index of **hardware communication protocols** implemented in Verilog HDL, with each protocol maintained in its own dedicated repository containing RTL, testbenches, documentation, waveform analysis, and verification results.

The collection currently includes:

- UART
- SPI
- I²C

## Protocols

| Protocol | Communication Type | Key Concepts | Repository |
|:---:|:---:|:---:|:---:|
| **UART** | Asynchronous | Baud-rate generation, framing, parity, receiver sampling | [UART](https://github.com/theYash856/UART_Transceiver) |
| **SPI** | Synchronous | Full-duplex communication, Master/Slave architecture, `CS`, `CPOL`, `CPHA` | [SPI](https://github.com/theYash856/SPI_Controller) |
| **I²C** | Synchronous | Shared bus, 7-bit addressing, `ACK`/`NACK`, open-drain communication, pull-ups | [I²C](https://github.com/theYash856/I2C_Controller) |

## Verification

Each implementation includes **task-based, self-checking testbenches** with automated PASS/FAIL reporting, waveform analysis, module-level verification, and top-level integration testing.

## Future Additions

This repository will continue to expand as additional hardware communication protocols are implemented and verified.
