**# Wiring**

## Overview

The aircraft uses a centralised electrical system based around the Matek F405-VTOL flight controller.

The integrated power distribution board supplies battery power to all five ESCs while the flight controller sends control signals to each ESC and servo.

---

## Power Distribution

The aircraft is powered by a single 4S LiPo battery.

The battery connects directly to the Matek F405-VTOL integrated power distribution board.

The power distribution board supplies battery voltage to:

- ESC 1 (VTOL Motor 1)
- ESC 2 (VTOL Motor 2)
- ESC 3 (VTOL Motor 3)
- ESC 4 (VTOL Motor 4)
- ESC 5 (Forward propulsion motor)

The flight controller also receives power through the integrated power distribution board.

---

## Signal Connections

The flight controller sends Pulse Width Modulation signals to:

- Four VTOL ESCs
- One forward propulsion ESC
- Elevator servos
- Left aileron servo
- Right aileron servo

The GPS, receiver and airspeed sensor communicate directly with the flight controller.

---

**## Design Considerations**

The integrated power distribution board reduces wiring complexity by distributing battery power directly to all ESCs while simultaneously powering the flight controller.

Keeping the flight controller near the centre of the aircraft also minimises wire lengths and improves weight distribution.

---

## Future Work

The wiring layout will be updated during assembly to reflect the final cable routing and connector placement.

---

## Wiring Diagram

```
       4S LiPo Battery       GPS
              |               |
              -------|---------          
                     |
        Matek F405-VTOL Integrated PDB
                     |
Receiver ----------- FC ----------- Airspeed Sensor
                     |
        -------------|--------------------------------------
        |            |            |           |            |
      ESC1         ESC2         ESC3        ESC4          ESC5
        │            │            │           |            |
      Motor1       Motor2       Motor3      Motor4     Cruise Motor 

