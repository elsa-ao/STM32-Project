# STM32F103C8T6 Custom Dev Board

Custom STM32F103C8T6 USB dev board, designed from scratch in STM32CubeMX (pinout) and KiCad (schematic + PCB), following Phil's STM32 Udemy course.

## Features

- STM32F103C8T6, powered over USB (AMS1117-3.3 regulator)
- Native USB device (Micro-B connector)
- UART and I²C broken out to headers
- SWD header for programming/debugging
- 16MHz crystal, BOOT0 select switch, power LED

## Repository structure

```
stm32-udemy-project/
├── cubemx/   # STM32CubeMX .ioc project
├── kicad/    # KiCad schematic + PCB
└── docs/     # Exported images/renders
```
