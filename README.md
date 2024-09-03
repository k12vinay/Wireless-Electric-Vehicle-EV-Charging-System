# Wireless-Electric-Vehicle-EV-Charging-System

This project models a wireless electric vehicle (EV) charging system using MATLAB Simulink. The system demonstrates how an EV can be charged while in motion using wireless power transmission from coils embedded in the road.

## Project Overview

The system includes:
- **Solar Panel**: Generates DC power.
- **Battery**: Stores the generated power.
- **Charge Controller**: Regulates the charging process.
- **Transformer**: Converts DC to AC power for transmission.
- **Regulator Circuitry**: Ensures stable power transmission.
- **Transmitter and Receiver Coils**: Facilitate wireless power transmission.
- **AC to DC Converter**: Converts the transmitted power back to DC to charge the EV battery.
- **Atmega Controller**: Manages the system operations and displays voltage readings.

## Simulation Model

The Simulink model for this project can be found in the `SimulinkModel` directory.

![System Overview](Documentation/SystemOverview.png)

## How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Wireless-EV-Charging-System.git
   ```
2. Open MATLAB and navigate to the `SimulinkModel` directory.
3. Open `WirelessEVCharging.slx` in Simulink.
4. Run the simulation to see the system in action.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

