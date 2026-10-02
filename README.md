# Vehicle Cabin Guardian Collision Warning

Build a smart vehicles prototype that uses GPS module, cellular modem to warn about close obstacles. Include setup instructions, a circuit diagram, tested firmware, and sample output.

> Build and test at safe low voltage. Real machinery, vehicles, aircraft, pumps, and power systems require qualified engineering review and certified safeguards.

## Project details

| Field | Value |
| --- | --- |
| Roadmap ID | 792 |
| Category | Smart Vehicles |
| Platform | Teensy 4.1 |
| Difficulty | Beginner |
| Estimated build time | 16 hours |
| Connectivity | CAN bus |
| Core components | GPS module, cellular modem |
| Control mode | threshold alert |

## Repository layout

- `firmware/vehicle-cabin-guardian-collision-warning/vehicle-cabin-guardian-collision-warning.ino`: runnable firmware or application
- `docs/wiring.md`: suggested low-voltage wiring plan
- `docs/architecture.md`: system data flow
- `docs/test-plan.md`: repeatable verification steps
- `sample-data/example.json`: example telemetry record
- `tools/validate.py`: dependency-free repository validation

## Quick start

1. Open `firmware/vehicle-cabin-guardian-collision-warning/vehicle-cabin-guardian-collision-warning.ino` in Arduino IDE or Arduino CLI.
2. Select the board matching **Teensy 4.1**.
3. Compile and upload, then open the serial monitor at 115200 baud.

## Expected behavior

Collision Warning demonstration with repeatable test steps. The default implementation supports simulated or generic analog inputs so the control path can be exercised before hardware-specific drivers are added.

## Hardware adaptation

The included code is a safe reference implementation. Update pin assignments and sensor conversions from the exact component datasheets, then repeat the test plan before connecting actuators.

## License

MIT
