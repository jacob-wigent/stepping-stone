# Project Title (remove once image added)
![Project-Name](./assets/title-logo-dark.png#gh-dark-mode-only)
![Project-Name](./assets/title-logo-light.png#gh-light-mode-only)
---

This is where you describe the project. What does it do? Why does it matter? Who knows...

## Block Diagram

> CREATE DRAW.IO DOCUMENT AND SAVE TO THIS REPOSITORY AS `diagram.drawio`

![Layout](./diagram.png)

### Navigate

| |  |  |
|-----------|---------|---------|
| **[Hardware](./hardware/README.md)** | Contents | File types or technologies |
| **[Firmware](./firmware/README.md)** | Contents | File types or technologies |
| **[Software](./software/README.md)** | Contents | File types or technologies |

## Target Capabilities

### Motion Control

- Four-axis stepper motor control
- Coordinated multi-axis motion
- StallGuard-based sensorless homing
- Hardware limit switch support
- Emergency stop support
- Optional closed-loop motion experiments via encoder feedback

### Connectivity

- USB programming and communication
- CAN bus networking for distributed robotics systems
- Expansion interfaces for sensors and peripherals

### Development & Debugging

- Native debugging and firmware development support
- Driver diagnostics and telemetry
- Motion data logging
- Accessible test points and expansion headers
- Standalone operation capability

### Position Feedback

- Incremental encoder support
- Absolute encoder support
- General-purpose analog and digital position sensing

### Power & Protection

- Flexible power input options
- Motor and system power monitoring
- Hardware safety interlocks
- Fault detection and reporting
- Reverse polarity and overcurrent protection

## Roadmap

- [ ] System architecture defined  
- [ ] Component selection finalized
- [ ] Schematic capture
- [ ] PCB layout
- [ ] Total project redesign

> UPDATE URL

See the [open issues](https://github.com/jacob-wigent/embedded-systems-tempalte/issues) for a full list of proposed features (and known issues).

## Tools
> EXAMPLES
- **Hardware Design:** KiCad 10.0 for schematic capture and PCB layout
- **Simulation:** LTSpice / MATLAB for analog characterization
- **Firmware:** STM32CubeIDE or PlatformIO (planned)
- **Software:** JavaFX for desktop interface (planned)

## License

This project is released under the **CERN Open Hardware Licence Version 2 – Strongly Reciprocal (CERN-OHL-S v2)**.  

You are free to use, modify, and distribute the hardware and design files, provided that derivative works are also shared under the same license.  

For full license details, see the [LICENSE](LICENSE) file.
