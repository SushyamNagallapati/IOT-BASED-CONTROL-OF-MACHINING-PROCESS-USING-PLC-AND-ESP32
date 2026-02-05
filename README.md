# IoT-Based Machining Control using PLC & ESP32

This project demonstrates how a machining process can be controlled wirelessly using IoT, a PLC, and an ESP32 microcontroller.

The main idea is to let operators monitor and control a machining operation remotely using a mobile app, instead of relying on manual switches or long wiring.

---

## What this project does

- Controls a machining process (drilling operation) remotely  
- Uses an ESP32 to send wireless commands  
- Triggers PLC inputs through relay modules  
- Allows control using the Blynk mobile app  
- Reduces manual intervention and wiring  
- Improves safety and flexibility  

---

## How the system works

1. The user presses buttons in the Blynk mobile app  
2. Commands are sent over WiFi to the ESP32  
3. The ESP32 activates relay modules  
4. Relays trigger digital inputs on the PLC  
5. The PLC executes ladder logic to control the machine  

**Flow:**  
Mobile App → ESP32 → Relay → PLC → Machine

---

## Components used

### Hardware
- ESP32 WiFi microcontroller  
- Delta PLC  
- Relay modules  
- Drilling machine setup  
- DC motors (12V / 16V)  
- Switch Mode Power Supply (SMPS)  

### Software
- Arduino IDE  
- Blynk mobile application  
- PLC ladder logic software  

---

## Features

- Wireless control of PLC inputs  
- Real-time operation  
- Local WiFi-based control  
- Safe remote operation  
- Suitable for small-scale industrial automation  

---

## Setup overview

1. Upload the ESP32 code using Arduino IDE  
2. Configure WiFi credentials and Blynk Auth Token  
3. Connect ESP32 pins to relay modules  
4. Connect relays to PLC digital inputs  
5. Load the ladder logic program into the PLC  
6. Use the Blynk app to control the machining process  

---

## Use cases

- PLC and IoT learning projects  
- Industrial automation demos  
- Remote machine control experiments  
- Industry 4.0 academic projects  

---

## Limitations

- Designed for small-scale setups  
- Requires stable WiFi connection  
- Not intended for high-risk industrial use without extra safety systems  

---

## Future improvements

- Sensor feedback (RPM, load, temperature)  
- Cloud data logging  
- Access control and user roles  
- Safety interlocks  
- Monitoring dashboard  

---

## License

This project is intended for educational and learning purposes.  
You are free to explore, modify, and build upon it.
