# DHT11 Arduino Project

This project demonstrates how to interface a DHT11 temperature and humidity sensor with an Arduino. The code is provided in the `DHT11.ino` file.

## Features
- Reads temperature and humidity data from the DHT11 sensor
- Displays the readings via Serial Monitor

## Requirements
- Arduino board (Uno, Mega, Nano, etc.)
- DHT11 temperature and humidity sensor
- Jumper wires
- Resistor
- Breadboard (optional)
- Arduino IDE

## Wiring
- Connect the DHT11 sensor's VCC to 5V on Arduino
- Connect GND to GND
- Connect the data pin to a digital pin (as specified in the code)

## Usage
1. Open `DHT11.ino` in the Arduino IDE.
2. Select the correct board and port from the Tools menu.
3. Upload the code to your Arduino.
4. Open the Serial Monitor to view temperature and humidity readings.

## File Structure
- `DHT11.ino` - Main Arduino sketch for reading DHT11 sensor data
- 'Setup_guide.png' - a guide on how to setup the components. 
- `README.md` - Project documentation (this file)


## Libraries

- Search DHT sensor library → install the one by Adafruit
- Search Adafruit Unified Sensor → install it (required by DHT)


## License
This project is provided for educational purposes.
