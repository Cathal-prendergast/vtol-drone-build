# Micro-Servos

## Components

The aircraft uses four:

**EMAX ES08MA II micro servos**

The servos operate the aircraft's control surfaces during forward flight.

---

## Purpose

The servos convert electrical control signals from the flight controller into mechanical movement of the control surfaces.

This allows the aircraft to control Pitch and Roll

---

## Control System

The flight controller sends a PWM signal to each servo.

The servo moves to the position commanded by the flight controller.

During manual flight, the flight controller receives the pilot's control inputs and moves the servos accordingly.

During stabilised or autonomous flight, ArduPilot can make its own corrections to the servo positions.

---

## Servo Arrangement

The final servo arrangement will be:

- Servo 1 → Horizontal stabiliser/Elevator
- Servo 2 → Horizontal stabiliser/Elevator
- Servo 3 → Aileron
- Servo 4 → Aileron


---

## Installation

The servos will be mounted securely in the airframe.

Control linkages will be adjusted so that the control surfaces are centred when the servos are at their neutral positions.

The servo direction and maximum travel will be configured before flight.

---

## Testing

Each servo will be tested individually before flight.

Testing will verify:

- Correct movement
- Correct direction
- Correct neutral position
- Appropriate maximum travel
- Secure mechanical connections
