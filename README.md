# E-Bike Motor Overheat & Overload Protection System

This project protects an electric bike motor from overheating and excessive current load during operation. A temperature sensor and a current sensor continuously monitor the motor’s condition. The controller processes these readings and automatically applies safety measures whenever the motor reaches unsafe operating limits.

If the temperature or current exceeds the predefined threshold, the motor PWM output is reduced to lower the mechanical and thermal load. A warning message is displayed on the LCD, allowing the rider or developer to instantly understand the motor health status. Under normal conditions, the system restores full drive output and continues monitoring in real time.

This system is valuable for electric bikes, scooters, and light EVs that face heavy-load situations such as uphill climbs, rapid acceleration, or extended riding durations. It helps improve component lifespan, prevents damage, and supports safer, more reliable EV motor operation.

## Features
- Continuous temperature and current monitoring  
- Automatic PWM reduction on overload  
- LCD display for real-time motor status  
- Protects motor from overheating and excess current  
- Useful for performance tuning and EV system development  

## Applications
- Electric motorcycles and scooters  
- Student EV prototypes  
- Motor testing environments  
- Low-cost EV safety modules  
- Embedded automotive electronics projects  

## Hardware Requirements
- Arduino board  
- Temperature sensor (e.g., LM35)  
- Current sensor (e.g., ACS712)  
- Motor driver and BLDC/DC motor  
- 16x2 LCD display  

## Author
👨‍💻 **K. Viswanadh**
