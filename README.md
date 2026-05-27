# Bluetooth Controlled Mini RC Car using ESP32-C3

## Overview

This project is a miniature Bluetooth-controlled RC car designed using ESP32-C3 microcontroller, HC-05 Bluetooth module, DRV8833 motor driver, and N12 gear motors.

The RC car is controlled wirelessly through a smartphone using Bluetooth communication.

The project demonstrates:

- Embedded systems
- Wireless communication
- PWM motor control
- Differential steering
- Miniature robotics

---

# Features

- Bluetooth control using HC-05
- ESP32-C3 microcontroller
- PWM speed control
- Differential steering
- Forward, backward, left, right movement
- Rechargeable battery system
- Compact Hot Wheels sized chassis

---

# Components Used

| Component | Quantity |
|---|---|
| ESP32-C3 Mini | 1 |
| HC-05 Bluetooth Module | 1 |
| DRV8833 Motor Driver | 1 |
| N12 Gear Motors | 2 |
| 3.7V Lithium-Ion Battery | 1 |
| TP4056 Charging Module | 1 |
| 1000µF Capacitor | 1 |
| Wheels | 2 |

---

# Circuit Connections

## HC-05 to ESP32-C3

| HC-05 | ESP32-C3 |
|---|---|
| VCC | VIN |
| GND | GND |
| TXD | GPIO20 |
| RXD | GPIO21 |

---

## DRV8833 to ESP32-C3

| DRV8833 | ESP32-C3 |
|---|---|
| IN1 | GPIO4 |
| IN2 | GPIO5 |
| IN3 | GPIO6 |
| IN4 | GPIO7 |
| EEP | 3.3V |
| ULT | 3.3V |

---

# Working Principle

1. Smartphone sends Bluetooth command.
2. HC-05 receives the command.
3. ESP32-C3 processes the command.
4. DRV8833 controls motor speed and direction.
5. Motors rotate wheels.
