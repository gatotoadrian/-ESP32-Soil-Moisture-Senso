# ESP32 Soil Moisture Sensor

This project demonstrates how to use an ESP32 with a soil moisture sensor to measure soil moisture levels. The moisture level is calculated based on the analog input from the sensor and displayed as a percentage on the Serial Monitor.

## Requirements

- ESP32 board (NodeMCU-32S or similar)
- Soil Moisture Sensor
- Arduino IDE with ESP32 board support

## Libraries

Make sure to install the necessary libraries via the Arduino Library Manager:
- None specific are needed beyond the built-in ESP32 and Arduino core libraries.

## Hardware Setup

1. **Soil Moisture Sensor Connections:**
   - VCC to 3.3V
   - GND to GND
   - Analog output (AO) to GPIO 36 (A0)
