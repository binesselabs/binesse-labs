# Welcome to Binesse Labs.

Binesse Labs is the open-source engineering initiative behind the Binesse Clock.

We believe hardware should be owned, not licensed. That’s why we built the Binesse Clock with standard M3 machine screws, a break-out I2C header, and open firmware.

This organization hosts the source of truth for the entire project.

## The Repositories

1. binesse-firmware

The C++ / Arduino code running on the clock.

Core Logic: Circadian Shift, Binary Timekeeping, Auto-Dimming.

SDK: Easy functions to control the 20-pixel grid.

Status: Stable v1.0

2. binesse-hardware

The physical blueprints.

PCB: Gerber files, EasyEDA schematics, and BOM.

CAD: .step and .stl files for the Unibody Faceplate and Docking Base.

Pinouts: Documentation for the internal Expansion Header.

3. community-hacks

A collection of user-submitted modes and integrations.

Examples: Stock tickers, Server monitors, Pomodoro timers.

Contributing: Have a cool mod? Submit a Pull Request here.

## The "Hacker Header"

Every Binesse Clock ships with an internal 1x4 Expansion Header on the PCB. This exposes the I2C Bus directly to you.

Pinout (Left to Right):

3V3 (Power)

GND (Ground)

SDA (Data - GPIO D4)

SCL (Clock - GPIO D5)

Use this to add temperature sensors (BME280), air quality monitors (SGP30), or OLED displays without soldering.

License
All hardware and software in Binesse Labs is released under the MIT License. Hack it, fork it, build it.
