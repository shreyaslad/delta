# Delta

<p align="middle">
    <img src="./docs/deltav4-front.png" width=300>
    <img src="./docs/deltav4-back.png" width=323>
</p>

Delta is a minature, custom-made board that aims to remotely control vehicles by connecting to the Onboard Diagnostics (OBD-II) port, streaming real-time onboard sensor data such as:

- Speed
- Acceleration
- Gyroscopic Tilt
- Throttle & Steering Position
- Gear
- Engine RPM

and integrating external cameras and sensors.

Delta supports WiFi and Bluetooth LE, running a dual-core ESP32-S3R8V based on the 32-bit Xtensa architecture. The current prototype is only 32mm * 37mm with single-sided assembly, packing a ton of components into an incredibly small area. The board is can be powered by a computer or independantly with a car battery.

## Hardware

Features:
- USB Type-C connector
- 12v -> 5v @ 3A Buck Converter
- 5v -> 3.3v @ 700mA Low Dropout Regulator
- Dual Core ESP32-S3R8V microcontroller
- 16MB QSPI Flash
- 8MB QSPI PSRAM
- 2.4GHz 802.11/b/g/n WiFi
- Bluetooth Low Energy
- CAN bus communication
- Neopixel strip support
- Ultra-low current deep sleep
