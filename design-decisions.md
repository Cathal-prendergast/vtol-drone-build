# Design Decisions

This document explains the reasoning behind the design choices made throughout the development of the aircraft.

---

## VTOL Configuration

A VTOL configuration was selected to combine the advantages of multirotor and fixed-wing aircraft.

Benefits include:

- Vertical take-off and landing without a runway.
- Improved endurance compared to a conventional multirotor.
- Ability to complete autonomous missions over greater distances.

---

## Airframe Size

The aircraft has a wingspan of 1.2 m and a wing chord of 235.83 mm.

These dimensions were selected to provide sufficient wing area for a stall speed of approximately 10 m/s while keeping the aircraft compact and easy to transport.

---

## Airfoil Selection

The NACA 2412 airfoil was selected because it provides good lift at relatively low airspeeds and has predictable stall characteristics.

These make it well suited to a VTOL aircraft transitioning between hover and forward flight.

---

## Material Selection

The airframe is manufactured primarily from PETG.

PETG was chosen because it provides greater impact resistance than PLA which is more brittle while remaining suitable for 3D printing.

Carbon fibre spars are used to increase wing stiffness while keeping structural weight low.

---

## Flight Controller

The Matek F405-VTOL flight controller was chosen because it is designed specifically for fixed-wing VTOL aircraft.

Its integrated power distribution board simplifies wiring and reduces the number of separate components required.

---

## Flight Software

ArduPilot was selected because it supports:

- VTOL aircraft
- Autonomous waypoint missions
- GPS navigation
- Flight logging
- Extensive tuning and configuration options

---

## Propulsion System

The aircraft uses:

- Four lift motors for VTOL flight.
- One cruise motor for forward flight.

Separating vertical lift from forward propulsion allows the aircraft to hover efficiently while maintaining the endurance advantages of a fixed-wing aircraft.

---

## Battery Selection

A 4S 5000 mAh LiPo battery was selected to provide sufficient power for the propulsion system while maintaining an acceptable aircraft weight.

---

## Control System

ELRS was selected as the radio communication system due to its long range, low latency and reliability.

---

## Design Priorities

Throughout the project the following priorities guided design decisions:

1. Stable flight
2. Reliable VTOL transition
3. Low aircraft weight
4. Ease of manufacture
5. Modular construction
