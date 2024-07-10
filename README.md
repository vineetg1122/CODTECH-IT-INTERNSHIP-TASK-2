# CODTECH-IT-INTERNSHIP-TASK-2

Overview: Interfacing a DHT Sensor with Arduino Using Tinkercad

Objective
To measure temperature and humidity using a DHT11 sensor and display the readings on a 16x2 LCD using Arduino, simulated in Tinkercad.

Components Needed
Arduino Uno
DHT11 Sensor
16x2 LCD Screen
Breadboard
Jumper Wires
10kΩ Resistor

Set Up Components in Tinkercad:
Add Arduino Uno, DHT11, 16x2 LCD, and breadboard.

Connect VCC and GND of DHT11 to 5V and GND on Arduino.
Connect DATA pin of DHT11 to digital pin 2 on Arduino with a 10kΩ pull-up resistor.
Connect LCD:

Connect VCC to 5V and GND to GND.
Connect SDA to A4 and SCL to A5 (for I2C module).
Write Code:

Include DHT and LiquidCrystal_I2C libraries.
Initialize DHT sensor and LCD.
Read temperature and humidity in the loop.
Display readings on the LCD.
Upload and Simulate:

Upload the code in Tinkercad.
upload the code given in my file and simulate 

