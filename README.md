# RAPID-TRI (Raspberry Pi-based Amateur Pulsar Identification and Detection - TRIangulation)

## Introduction
RAPID-TRI is a backyard-style project exploring the concept of using pulsars as radio beacons for navigation, simulating a mock journey to a destination like Proxima Centauri.

## Project Description
The goal of this project is to create a simple and educational mock representation of using pulsars as radio beacons for navigation within our galaxy. The project involves Raspberry Pi devices as pulsar emitters and a central device simulating a spacecraft. It aims to provide a basic understanding of pulsar-based navigation concepts.

## Identified Pulsars
1. **Crab Pulsar:**
   - Suggested Frequency: 2.402 GHz

2. **B0329+54:**
   - Suggested Frequency: 2.422 GHz

3. **Vela Pulsar:**
   - Suggested Frequency: 2.442 GHz

4. **J0437-4715:**
   - Suggested Frequency: 2.462 GHz

## Steps
1. **Set up Raspberry Pi Zeros:**
   - Install the Raspberry Pi OS on each Pi Zero.
   - Configure an ad-hoc or local network.

2. **NTP Synchronization:**
   - Designate one Pi as the master clock for NTP synchronization.
   - Sync the clocks of other Pis to the master clock.

3. **Define Broadcast Frequencies and Time Packet Format:**
   - Choose frequencies for each Pi's GPIO pin.
   - Define a time packet format for broadcasting.

4. **Implement Broadcasting and Receiving:**
   - Develop scripts for transmitting time packets.
   - Implement scripts on other Pis for receiving and processing packets.

5. **Testing and Calibration:**
   - Test the setup in a backyard environment.
   - Calibrate timing synchronization and evaluate discrepancies.

## Initial Testing Frequencies
- Pulsar Emitters (Raspberry Pis): 
  - Crab Pulsar: 2.402 GHz
  - B0329+54: 2.422 GHz
  - Vela Pulsar: 2.442 GHz
  - J0437-4715: 2.462 GHz

- Central Device (Spacecraft):
  - Receive Frequency: 2.4 GHz

## To-Do List
- [ ] Detailed testing of synchronization accuracy.
- [ ] Refinement of time packet format.
- [ ] Exploration of additional pulsar-like behaviors.
- [ ] Enhancement of the overall system accuracy.

## File Layout (Suggested)
- `docs/`: Documentation files.
- `src/`: Source code files.
- `tests/`: Test scripts and data.
- `README.md`: Project overview.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

