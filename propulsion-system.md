# Propulsion System

## Overview

The aircraft uses a five-motor propulsion system consisting of four vertical-lift motors and one forward propulsion motor.

This allows the aircraft to take off and land vertically while using a conventional fixed-wing propulsion system during forward flight.

---

## Vertical Lift

The aircraft uses four:

**SunnySky X2814 900KV brushless motors**

Each motor is controlled by its own ESC.

The four motors are responsible for:

- Vertical take-off
- Hover
- VTOL stabilisation
- Vertical landing

Each motor uses an **11×5.5 inch propeller**.

---

## Forward Propulsion

Forward flight is provided by one:

**SunnySky X2216 brushless motor**

The motor is controlled by its own ESC and uses a **9x4.5 inch** propeller.

The forward motor provides the thrust required to accelerate the aircraft and maintain forward flight once the wings are producing sufficient lift.

---

## Electronic Speed Controllers

Five **HobbyWing Skywalker 60A V2 UBEC 3–6S ESCs** are used.

Each motor has its own ESC.

The ESCs receive:

1. Battery power from the Matek F405-VTOL power distribution system.
2. A control signal from the flight controller.
3. The motor connection through the three-phase motor wires.

The ESC controls the speed of its motor by varying the electrical power supplied to it through pulse width modulation.

---

## Motor Arrangement

The four VTOL motors are positioned symmetrically around the aircraft.

Two motors rotate clockwise and two rotate counter-clockwise.

This allows the aircraft to control yaw during hover by changing the relative thrust of the motors.

The exact motor numbering and rotation directions will be documented in the final wiring diagram.

---

## Thrust Testing

The total available VTOL thrust will be determined using the four lift motors with the selected 11×5.5 inch propellers and 4S LiPo battery.

The measured thrust will be compared with the aircraft's estimated weight to determine the final thrust-to-weight ratio.

Results will be added after testing.
