# Reflow Oven

DIY ESP32-controlled reflow oven conversion for soldering electronics, built from a toaster oven with SSR heater control, thermocouple feedback, improved insulation, and an external electronics enclosure.

## Project goals

- Convert a toaster oven into a controlled PCB reflow oven.
- Use ESP32 instead of ESP8266 for improved reliability and available inventory.
- Control the heating elements with SSR-40DA solid-state relays.
- Read chamber temperature using K-type thermocouples.
- Add insulation, aluminum thermal spreading, and mechanical shielding where useful.
- Breadboard and validate the controller before cutting into the oven.
- Keep wiring, firmware, CAD, test logs, and design notes together in this repo.

## Current direction

- External project box mounted to the side/front area of the oven.
- Original knobs/rheostats removed or bypassed as needed.
- Dual SSR setup for heater control, with a third SSR as backup.
- High-temperature heater wire and high-temp shrink wrap for terminal cleanup.
- Aluminum plates considered for SSR mounting and heat spreading.
- Thermocouples acquired for temperature feedback and calibration mapping.

## Repository layout

```text
Reflow-oven/
├── cad/
├── docs/
├── firmware/
├── hardware/
├── project_logs/
├── safety/
├── software/
└── tests/
```

## First build phase

1. Breadboard ESP32, thermocouple interface, display, and SSR control outputs.
2. Confirm thermocouple readings and logging.
3. Test SSR control with a low-voltage indicator load before switching heater power.
4. Map oven thermal response with existing heater system.
5. Install project enclosure and high-temperature wiring.
6. Add insulation and aluminum thermal spreaders after baseline testing.
7. Tune reflow profile control.

## Notes

This is a working project repo. Add measurements, test results, wiring changes, and firmware experiments as they happen.
