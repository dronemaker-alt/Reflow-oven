# Reflow Oven Ideas

## Current Hardware Direction

- Bench-top toaster oven conversion
- Dual SSR configuration for heating control with one backup SSR available
- ESP32-based controller platform
- Thermocouple feedback system
- External electronics enclosure mounted to oven body
- Internal aluminum thermal spreading plates
- Additional insulation planned around oven chamber

## Thermal Concepts

### Aluminum Heat Spreader

Ideas explored:

- 6x6 inch aluminum plates used as thermal spreaders
- Stacked plate arrangement approximately 1.6 mm total thickness
- U-channel spacers between plates to increase thermal spreading and airflow paths
- Possible rivet removal beneath SSR mounting locations for better thermal transfer

### Insulation

- Additional sheet metal liner and insulation around oven cavity
- Wooden shipping crate repurposed as outer thermal enclosure
- Interior dimensions measured around 21 x 20 inches
- Additional aluminum lining planned inside enclosure

## Electrical System

### Control System

- ESP32 selected over ESP8266 due to stability concerns
- Breadboard validation planned before permanent install
- OLED display support possible for temperature and profile display
- Potential future web interface for monitoring and profile upload

### Power Control

- Multiple SSR-40DA modules available
- Separate heater zone control possible
- High-temperature heater wire acquired
- High-temp shrink wrap planned for terminal cleanup

### Sensors

- K-type thermocouples acquired
- Multi-point temperature monitoring possible
- Potential chamber mapping using several thermocouples during calibration

## Mechanical Layout Ideas

- External project box mounted to side of oven
- Original rheostats and knobs removed
- Brackets fabricated from scrap aluminum
- Internal circulation fan under consideration
- Sheet metal reinforcement and shielding

## Software Features

### Desired Features

- Reflow profile storage
- Live temperature graphing
- PID temperature control
- Manual override mode
- Safety cutoff monitoring
- Profile presets:
  - Leaded solder
  - Lead-free solder
  - Low-temp experimental profiles

### Future Features

- Wi-Fi monitoring
- Browser-based dashboard
- Data logging
- OTA firmware updates
- SD card logging
- Remote emergency stop

## Safety Concepts

- Thermal fuse backup
- Watchdog shutdown logic
- SSR heatsink temperature monitoring
- High-temperature wire routing separation
- Grounded chassis verification
- Ventilation considerations

## Fabrication Notes

### Available Materials

- Scrap aluminum plate
- Sheet metal panels
- 20x20 extrusion inventory available for future framing
- Fiberglass cloth inventory may be useful for insulation experiments

## Expansion Ideas

- Multi-zone reflow control
- Hot plate preheater integration
- BGA rework assist mode
- PCB drying mode
- Composite curing oven mode
- Filament drying mode
- Environmental chamber experiments
