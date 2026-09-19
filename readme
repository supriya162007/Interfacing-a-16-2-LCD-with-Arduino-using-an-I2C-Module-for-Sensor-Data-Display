## EXP — INTERFACING A 16×2 LCD WITH ARDUINO USING AN I2C MODULE FOR SENSOR DATA DISPLAY

## AIM

To interface a **16×2 LCD display with Arduino using an I2C module** and display sensor data on the LCD.

## OBJECTIVES

- To understand the operation of a 16×2 LCD.
- To interface the LCD with Arduino using an I2C module.
- To reduce the number of GPIO pins required for LCD communication.
- To read sensor data using Arduino.
- To display the sensor readings on the LCD.

## HARDWARE / SOFTWARE TOOLS REQUIRED

### Hardware

- Arduino UNO
- 16×2 LCD Display
- I2C LCD Module (PCF8574-based)
- DHT11 Temperature and Humidity Sensor
- Breadboard
- Jumper Wires
- USB Cable

### Software

- Arduino IDE
- Arduino C/C++ Programming Language
- LiquidCrystal_I2C Library
- DHT Sensor Library

## COMPONENTS

### 16×2 LCD

### I2C Module

### Circuit Connections

### I2C Communication

### Working Principle

1. The DHT11 sensor measures temperature and humidity.
2. Arduino reads the sensor values through the digital data pin.
3. The Arduino processes the received sensor data.
4. The processed values are sent to the LCD through the I2C interface.
5. The LCD displays the temperature on one line.
6. The humidity is displayed on the second line.
7. The readings are periodically updated.

## ARDUINO PROGRAM

```cpp
#include <Wire.h>
#include <LiquidCrystal_I2C.h>

LiquidCrystal_I2C lcd(0x27, 16, 2);

void setup() {
  lcd.init();
  lcd.backlight();

  lcd.setCursor(0, 0);
  lcd.print("HELLO");

  lcd.setCursor(0, 1);
  lcd.print("RAJA");
}

void loop() {
}
````

## OBSERVATION

<img width="1423" height="1105" alt="image" src="https://github.com/user-attachments/assets/4e6e0d96-216f-41c4-a4d7-ca7d4e03cf5a" />

## RESULT

Thus, the **16×2 LCD was successfully interfaced with Arduino UNO using an I2C module**, and the temperature and humidity values obtained from the DHT11 sensor were successfully displayed on the LCD. The experiment demonstrates the use of **I2C communication for efficient sensor-data display** in embedded and IoT applications.


