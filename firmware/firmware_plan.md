# Firmware Plan

## Controller Platform

ESP32

## Planned Features

- PID temperature control
- Reflow profile execution
- Manual heater override
- Safety timeout handling
- Multi-stage thermal ramping
- OLED status display
- Serial debug logging
- Future Wi-Fi dashboard

## Planned Inputs

- Thermocouple interface
- Button/menu controls
- Optional rotary encoder

## Planned Outputs

- SSR heater control
- Status LEDs
- OLED display updates
- Serial/Wi-Fi telemetry

## Suggested Firmware Layout

```text
firmware/
├── experiments/
├── pid_testing/
├── thermocouple_tests/
├── display_tests/
└── main_controller/
```

## Future Enhancements

- OTA firmware updates
- SD card profile storage
- Browser UI
- Data logging
- Multi-zone heater support
