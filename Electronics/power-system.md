# Power System

## Overview

The aircraft is powered by a single 4S 5000mAh LiPo battery with an XT90 connector.

The battery provides the main electrical power for the propulsion system and onboard electronics.

---

## Battery

**Battery: Turnigy Rapid 4S 5000mAh 14.8V 100C Lipo**

The battery has a voltage of approximately 14.8V.

It was selected to provide sufficient voltage and capacity for the five-motor propulsion system while keeping the aircraft's overall weight within the design target.

The battery is connected to the Matek F405-VTOL using an XT90 connection soldered to the microcontroller.

---

## Power Distribution

The Matek F405-VTOL has an integrated power distribution system.

The battery connects to the board, which distributes battery power to the five ESCs.

The power system can therefore be represented as:

4S LiPo  
↓  
Matek F405-VTOL integrated power distribution  
↓  
Five ESCs  
↓  
Five motors

The flight controller and other electronics are also supplied through the flight controller's power system.

---

## ESC Power

Each of the five ESCs receives power from the aircraft's main battery through the Matek F405-VTOL power distribution system.

The five ESCs are:

- ESC 1 → VTOL Motor 1
- ESC 2 → VTOL Motor 2
- ESC 3 → VTOL Motor 3
- ESC 4 → VTOL Motor 4
- ESC 5 → Forward propulsion motor

---

## Power Monitoring

The Matek F405-VTOL provides voltage and current monitoring.

This allows the flight controller to monitor the aircraft's electrical power consumption and battery state.

---

## Design Considerations

Using the integrated power distribution system reduces the number of separate electrical components required.

It also allows the five ESCs to receive power from the Flight Controller while the ESCs themselves can be physically distributed throughout the aircraft.

The final physical cable routing will be documented during assembly.
