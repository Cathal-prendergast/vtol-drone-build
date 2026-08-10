# GPS and Compass

## Component

**HGLRC M100-5883 GPS & Compass Module**

The GPS module provides the aircraft with information about its geographical position and movement.

The integrated compass provides heading information.

---

## Purpose

The GPS is required for several functions of the aircraft, including:

- Position information
- GPS-assisted flight
- Autonomous navigation
- Waypoint missions
- Return-to-home functionality

The compass provides additional heading information that can be used by the flight controller for navigation and orientation.

---

## Connection

The GPS and compass module is connected to the Matek F405-VTOL flight controller.

The flight controller processes the navigation information and makes it available to ArduPilot.

---

## Autonomous Navigation

During an autonomous mission, ArduPilot uses GPS information to determine the aircraft's position relative to the planned route.

The aircraft can then follow set waypoints without requiring continuous manual control.

---

## Installation

The GPS module will be mounted away from sources of electrical interference where possible.

The final mounting position will be selected to keep the compass away from high-current wiring and other magnetic interference.

---

## Testing

Before autonomous flight, the GPS will be tested to ensure:

- A reliable satellite fix can be obtained.
- Position information is being received correctly.
- The compass provides a reasonable heading.
- ArduPilot recognises the GPS correctly.

Testing results will be added after installation.
