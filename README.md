# 4-DOF Robotic Arm (Arduino → ROS2 Digital Twin)

## Overview
This project is a 4-DOF robotic arm built using Arduino Uno and MG90S servos.  
The system is designed with a modular architecture to later integrate with ROS2 and a digital twin simulation.

---

## Demo
Coming soon...

---

## Features
- Serial-based control interface
- Smooth servo motion
- External 5V power system
- Modular design for ROS integration

---

## System Architecture
- Arduino Uno → controls servos
- External 5V supply → powers servos
- Common ground → ensures signal stability

---

## Hardware Used

| Component        | Description |
|----------------|------------|
| Arduino Uno     | Main controller |
| MG90S Servos    | Actuators |
| 5V Power Supply | External regulated supply |
| EEZYbotARM      | Mechanical structure |

---

## Wiring Diagram
![Wiring Diagram](docs/diagrams/wiring.jpeg)

---

## Usage

1. Upload Arduino code from `/arduino/v1.ino`
2. Connect wiring as per diagram
3. Power the system
4. Open Serial Monitor (9600 baud, newline)

##Example Command:
    90 90 90 90

---

## Notes
- Do NOT power servos from Arduino 5V pin
- Use ≥2A regulated 5V supply
- Ensure all grounds are connected
- You can also use SG90S for more power

---

## Future Work
- ROS2 integration
- Digital twin (URDF + RViz)
- Camera + AI control
