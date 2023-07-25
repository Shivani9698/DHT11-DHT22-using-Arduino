# DHT11-DHT22-using-Arduino

# DHT11 Temperature and Humidity Sensor Readings

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Description

This Arduino project reads temperature and humidity data from a DHT11 sensor and displays the readings on the serial monitor. It utilizes the Adafruit_Sensor and DHT libraries to interface with the DHT11 sensor and compute the heat index.


## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [Author]

## Introduction

The DHT11 Temperature and Humidity Sensor is a low-cost digital sensor that provides accurate temperature and humidity measurements. This project demonstrates how to use the DHT11 sensor with an Arduino board to obtain real-time temperature and humidity readings and display them on the serial monitor.

## Setup

### Components Required

- Arduino board (e.g., Arduino Uno)
- DHT11 Temperature and Humidity Sensor
- Jumper wires

### Circuit Connection

Connect the DHT11 sensor to the Arduino board as follows:


DHT11    Arduino
  VCC  ->   5V
  GND  ->   GND
  OUT  ->   D5

## Library Installation
To read from the DHT sensor, we’ll use the DHT library from Adafruit. To use this library you also need to install the Adafruit Unified Sensor library. Follow the next steps to install those libraries.

1.Open your Arduino IDE and go to Sketch > Include Library > Manage Libraries. The Library Manager should open.

2.Search for “DHT” on the Search box and install the DHT library from Adafruit.
![image](https://github.com/Shivani9698/DHT11-DHT22-using-Arduino/assets/119753029/7abb0cc1-8a77-4a10-af67-509eb9d1b2a5)


3.Installing Adafruit DHT library
4.After installing the DHT library from Adafruit, type “Adafruit Unified Sensor” in the search box. Scroll all the way down to find the library and install it.
![image](https://github.com/Shivani9698/DHT11-DHT22-using-Arduino/assets/119753029/15be6f6d-67ac-4f75-b169-4a9a042d8e1a)


5.Installing Adafruit Unified Sensor driver library


## Usage

1. Install the Arduino IDE from the official website if you haven't already.
2. Connect the DHT11 sensor to the Arduino board as described in the circuit connection section.
3. Open the Arduino IDE, and navigate to `Sketch -> Include Library -> Manage Libraries`.
4. Search for "DHT" in the Library Manager and install the "DHT sensor library" by Adafruit.
5. Upload the provided code (`dht_sensor_readings.ino`) to your Arduino board.
6. Open the Serial Monitor (`Tools -> Serial Monitor`) with a baud rate of `115200`.
7. The Serial Monitor will display the temperature and humidity readings in Celsius and percentage, respectively, at 2-second intervals.

## Contributing

Contributions to this project are welcome! If you find any issues or want to improve the code, please feel free to open an issue or submit a pull request. Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Submit a pull request.

Please ensure your pull request adheres to the following guidelines:
- Follow the existing coding style and naming conventions.
- Include appropriate comments in the code for better understanding.
- Test your changes thoroughly.

## Author

Shivani Raj

