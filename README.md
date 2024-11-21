# Smart-Irrigation-System

The Smart Irrigation System aims at identifying plants that require water through the soil moisture content the system is programmed to show environmental factors such as temperature and humidity. It consists of sensors, an LCD and a water pump hence a more efficient, cheap system that help conserve water as well as reduce human effort when watering. This prototype mitigates problems encountered in conventional irrigation systems by maximizing the use of water and encouraging smart farming on a small scale.


## Prerequisites
To work with this prototype, you will need:
- **Software**: Arduino IDE (version 1.8.13 or later)
- **Libraries or Dependencies**:
  - DHT sensor library (for temperature and humidity)
  - LiquidCrystal library (for LCD display)
- **Hardware Requirements**:
  - Arduino Uno
  - DHT11 temperature and humidity sensor
  - Soil moisture sensor
  - Relay module (HW 307)
  - 9V water pump and battery
  - LCD display (16x2)


## Installation
### Steps to Set Up the Prototype:
- Download and install the Arduino IDE from the official Arduino website.
- Clone the repository containing the code for the project:
  ```bash
   git clone https://github.com/shahparamh/Smart-Irrigation-System
   cd Smart-Irrigation-System
- Install the required libraries for Arduino:
  - Open the Arduino IDE.
  - Go to **Sketch** > **Include Library** > **Manage Libraries**....
  - Search for **DHT sensor library** and install it.
  - Search for **LiquidCrystal** and install it.

## How to Run
1. Connect the hardware components as per the provided circuit diagram.
2. Open the Arduino IDE.
3. Upload the provided code to the Arduino Uno board:
- Open the .ino file in the Arduino IDE.
- Select the correct Board and Port under the Tools menu.
- Click on the Upload button.
Once uploaded, power the Arduino and observe the system in action:
- The LCD displays the soil moisture, temperature, and humidity readings.
- The water pump activates automatically when the soil moisture level is low.
