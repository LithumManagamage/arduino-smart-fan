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
The Arduino reads temperature and motion sensor inputs and uses programmed conditions to control the fan and LEDs. The fan remains OFF when the temperature is below 10°C, operates at low speed when the temperature is between 10°C and below 25°C, runs at medium speed when the temperature is between 25°C and below 30°C, and operates at high speed when the temperature is 30°C or above. PWM is used to adjust the fan speed according to the temperature readings. The system activates appropriate outputs only when motion is detected. When motion stops, the fan remains ON for an additional 15 seconds before turning OFF.

## Design and Implementation
<img width="440" height="350" alt="image" src="https://github.com/user-attachments/assets/66d2ef43-438f-4f87-9d1d-5312c49b7b90" />

[Respective Code for the Smart Fan](https://github.com/LithumManagamage/arduino-smart-fan/blob/main/Code)

## Challenges and Improvements
### Challenges
- **Programming:** As a beginner to programming, I initially found it challenging to write the Arduino code and understand how to implement the required functions. With practice and help from my lecturer, I was able to overcome these difficulties and get the system working.

- **Visual Design:** I also struggled to make the circuit layout visually pleasing and well-organised. With feedback and assistance from my peers, I improved the overall arrangement and presentation of the design.

### Improvements
- **Code Documentation:** I could add more comments throughout the Arduino code to explain the purpose of each function and important section, making it easier to understand, debug and maintain.

- **Serial Monitor Output:** I could display useful information on the Arduino Serial Monitor, such as temperature readings, motion detection status and current fan speed. This would make testing and troubleshooting easier and provide better insight into how the system operates.

## Skills Demonstrated
Arduino, C/C++, sensors, circuit design, PWM, electronics and troubleshooting.
