# Wiring Plan

## Main Components

- ESP32 controller
- SSR-40DA relays
- K-type thermocouples
- Heater elements
- OLED display (optional)
- Cooling or circulation fan (future)

## Preliminary Signal Flow

```text
Thermocouple -> MAX thermocouple interface -> ESP32
ESP32 GPIO -> SSR input -> Heater elements
ESP32 -> OLED display
ESP32 -> Wi-Fi dashboard (future)
```

## Wiring Concepts

### AC Side

- High-temperature wire routing
- SSRs mounted to aluminum plate/heatsink
- Chassis grounding verification
- Heater isolation and strain relief

### Low Voltage Side

- Isolated logic wiring paths
- Separate thermocouple routing away from heater wiring
- External control enclosure preferred

## Planned Safety Features

- Thermal fuse
- Emergency cutoff logic
- Watchdog reset handling
- SSR temperature monitoring
