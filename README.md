**Name :**     Vaishnav Kumar Devarasetty

**Company :**  CODTECH IT SOLUTIONS

**ID :**       CT08ES843

**Domain**     EMBEDDED SYSTEMS

**Duration**   June to August 2024   

**Mentor**     G.Sravani

## Overview Of The Project

## Project : TEMPERATURE AND HUMIDITY MONITORING WITH DHT SENSOR.

## Overview
**Aim :** To Interface a DHT sensor with an Arduino to measure temperature and humidity. Display the readings on an LCD screen or serial monitor.

![Screenshot 2024-07-16 142645](https://github.com/user-attachments/assets/4d156eb9-eefd-4c0f-987c-0bd668bd4d35)

## Explanation :

**The code includes two libraries:** 

LiquidCrystal_I2C (for interfacing with I2C-based LCD displays) and DHT (for reading data from DHT11 humidity and temperature sensor).

The I2C address for the LCD display is set to 0x27, and it’s configured with 16 columns and 2 rows.

The DHT sensor is connected to pin 2 and is of type DHT11 .

In the setup() function:

The DHT sensor is initialized using dht.begin().

The LCD display is initialized using lcd.init().

The backlight of the LCD is turned on with lcd.backlight().

In the loop() function:

A delay of 2 seconds (delay(2000)) is added to wait between measurements.

The humidity and temperature are read from the DHT sensor.

If either the humidity or temperature reading is invalid (NaN), the LCD displays “Failed.”

Otherwise:

The temperature in Celsius is displayed with the degree symbol (°C).

The humidity percentage is displayed.

## Conclusion:

This code snippet sets up an Arduino to read temperature and humidity data from a DHT11 sensor and display it on an I2C-based LCD screen.

