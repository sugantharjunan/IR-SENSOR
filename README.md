# IR Sensor Module – KiCad PCB Design

A compact and efficient **IR Sensor Module** designed using **KiCad EDA** for schematic design and PCB layout. This project uses an **IR LED transmitter**, **photodiode receiver**, and **LM393 comparator** to detect nearby objects through infrared reflection.

The module is suitable for robotics, obstacle detection, automation systems, and embedded electronics applications.

---

# Project Overview

This project demonstrates:

* IR object detection circuit
* PCB layout design in KiCad
* Compact sensor module design
* Comparator-based signal processing
* Adjustable detection sensitivity
* 3D PCB visualization

---

# Features

* Infrared object detection
* Adjustable sensing range
* Compact PCB design
* LM393 comparator output
* LED indication for detection status
* 3-pin output connector
* Designed using KiCad

---

# Software Used

* KiCad

Official Website: [KiCad Official Website](https://www.kicad.org?utm_source=chatgpt.com)

---

# Hardware Components

| Component     | Description                  |
| ------------- | ---------------------------- |
| LM393         | Voltage Comparator IC        |
| IR LED        | Infrared transmitter         |
| Photodiode    | IR receiver                  |
| Potentiometer | Sensitivity adjustment       |
| LEDs          | Status indication            |
| Resistors     | Current limiting and biasing |
| Capacitors    | Noise filtering              |
| 3-Pin Header  | Output connection            |

---

# Project Structure

```bash id="g5u2yi"
IR-SENSOR/
│
├── Schematic/
│   └── ir_sensor.kicad_sch
│
├── PCB/
│   └── ir_sensor.kicad_pcb
│
├── Gerber/
│   └── Manufacturing_Files
│
├── Images/
│   ├── IR_3D1.png
│   ├── IR_3D2.png
│   ├── IR_PCB.png
│   └── IR_SCHEMATIC.png
│
└── README.md
```

---

# Circuit Description

The IR sensor module works using infrared reflection.

## Working Principle

1. The IR LED emits infrared light continuously.
2. When an object comes near the sensor:

   * Infrared light reflects back.
3. The photodiode detects the reflected IR signal.
4. The LM393 comparator processes the signal.
5. Output pin changes state when detection occurs.
6. Indicator LED turns ON during object detection.

---

# PCB Design

The PCB was designed with:

* Compact component placement
* Proper grounding
* Short signal routing
* Easy connector access
* Single-layer routing structure
* Optimized IR sensor positioning

---
# Pin Configuration

| Pin | Description    |
| --- | -------------- |
| VCC | +5V Supply     |
| GND | Ground         |
| OUT | Digital Output |

---

# Electrical Specifications

| Parameter         | Value                |
| ----------------- | -------------------- |
| Operating Voltage | 5V DC                |
| Comparator IC     | LM393                |
| Sensor Type       | IR Reflective Sensor |
| Output Type       | Digital              |
| PCB Tool          | KiCad                |

---

# Applications

* Obstacle Avoiding Robots
* Line Following Robots
* Proximity Detection
* Industrial Automation
* Smart Vehicles
* Embedded Systems Projects
* IoT Applications

---

# Sensitivity Adjustment

The onboard potentiometer allows adjustment of detection sensitivity:

* Rotate clockwise → Increase sensitivity
* Rotate counterclockwise → Reduce sensitivity

---

# Future Improvements

* Add analog output support
* Add distance calibration
* Add onboard microcontroller
* Improve ambient light filtering
* Add SMT compact version

---
