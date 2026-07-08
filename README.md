# Autonomous-Victim-Detection-System-for-Rescue-Missions-
The **Autonomous Victim Detection System for Rescue Missions** is a Proteus-based simulation of a search-and-rescue robot designed for post-landslide scenarios. It uses IR, temperature, and heartbeat sensors in a multi-stage detection process to identify potential survivors while reducing false detections.

## Project Details

The **Autonomous Victim Detection System for Rescue Missions** was developed as a semester project for the **Microcontroller Laboratory** course. The project focuses on the simulation of an autonomous search-and-rescue robot intended for disaster response scenarios, particularly **landslide-affected areas**. The objective is to assist rescue teams by identifying the possible presence of trapped victims using multiple sensor inputs.

The system follows a multi-stage detection approach to improve detection reliability. Initially, an **IR sensor** detects the presence of an obstacle. Once an object is detected, a **temperature sensor** measures its surface temperature. If the measured temperature exceeds a predefined threshold consistent with the human body, a **heartbeat sensor** is activated to verify the presence of a living person. This layered sensing methodology helps minimize false detections while improving the accuracy of victim identification.

The project was developed and validated entirely through simulation using Proteus, demonstrating the system's functionality and operational logic without constructing a physical prototype.

---

# Images
simulation video:[https://github.com/neeraj-madhavarapu/Autonomous-Victim-Detection-System-for-Rescue-Missions-/tree/main/Image%20%26%20video]

---

# Role and Contributions

- Developed the complete system simulation in Proteus.
- Designed and implemented the victim detection logic.
- Integrated and tested the sensor workflow for sequential detection.
  
---

# Hardware & Software

> **Note:** No hardware implementation is done.

## Software Tools

- Proteus Design Suite

## Simulated Components

- Microcontroller
- IR Obstacle Sensor
- Temperature Sensor
- Heartbeat Sensor
- Buzzer/Alert Module
- Power Supply

---

# Role and Contributions

- Developed the complete system simulation in Proteus.
- Designed and implemented the victim detection logic.
- Integrated and tested the sensor workflow for sequential detection.
- Verified the operational flow through simulation and debugging.

---

# Working Principle

1. The robot continuously scans its surroundings using the IR sensor.
2. When an obstacle is detected, the system measures its temperature.
3. If the measured temperature exceeds the predefined threshold, the heartbeat sensor is activated.
4. Detection of a valid heartbeat confirms the probable presence of a living victim.
5. The system generates an alert.

This sequential sensing approach improves reliability by reducing false positives compared to relying on a single sensor.


---

# What Makes This Project Unique?

- Implements a **multi-stage sensor verification** process instead of relying on a single sensor for victim detection.
- Reduces false positives by validating obstacle detection with both temperature and heartbeat measurements.
- Designed specifically for disaster-response scenarios such as landslides, where locating survivors quickly is critical.
- Demonstrates a practical search-and-rescue concept entirely through simulation, validating the detection logic before hardware implementation.

---
