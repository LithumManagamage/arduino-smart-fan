# Arduino Smart Fan
## Project Overview
This project involves developing an Arduino-based fan system that uses temperature and motion sensors to control fan operation.

## Objectives
- Measure temperature using a TMP36 sensor.
- Detect motion using a PIR sensor.
- Control fan speed using PWM.
- Use an L293D motor driver to control the DC fan.
- Indicate operating conditions using LEDs.

## Components
- Arduino Uno
- TMP36 temperature sensor
- PIR motion sensor
- L293D motor driver
- DC fan
- LEDs and resistors
- Power supply and connecting wires

## How it works
The Arduino reads temperature and motion sensor inputs and uses programmed conditions to control the fan and LEDs. The fan remains OFF when the temperature is below 10°C, operates at low speed when the temperature is between 10°C and below 25°C, runs at medium speed when the temperature is between 25°C and below 30°C, and operates at high speed when the temperature is 30°C or above. PWM is used to adjust the fan speed according to the temperature readings. When motion is detected, the system activates the appropriate outputs. When motion stops, the fan remains ON for an additional 15 seconds before turning OFF.

## Design and Implementation
<img width="440" height="350" alt="image" src="https://github.com/user-attachments/assets/66d2ef43-438f-4f87-9d1d-5312c49b7b90" />

[Respective Code for the Smart Fan](https://github.com/LithumManagamage/arduino-smart-fan/blob/main/Code)
