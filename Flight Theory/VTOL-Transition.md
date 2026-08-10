# VTOL Transition 

## Overview

The aircraft combines the vertical take-off capability of a multirotor with the efficiency of a fixed-wing aircraft.

Transition between these flight modes is managed automatically by ArduPilot.

---

## Vertical Flight

During take-off and hover:

- The four VTOL motors generate all lift.
- The forward propulsion motor remains off.
- The flight controller continuously adjusts motor speeds to maintain a stable hover.

---

## Transition to Forward Flight

After reaching a safe altitude:

1. The forward propulsion motor begins producing thrust.
2. The aircraft accelerates.
3. Airspeed increases.
4. The wings begin generating lift.
5. The flight controller gradually reduces thrust from the VTOL motors.
6. Once sufficient lift is produced by the wings, the VTOL motors are switched off.

---

## Forward Flight

During forward flight:

- The wings support the aircraft.
- The forward propulsion motor provides thrust.
- Control surfaces control the aircraft.
- The VTOL motors remain off.

This flight mode is significantly more energy efficient than hovering.

---

## Transition to Landing

Landing follows the reverse sequence.

1. The VTOL motors restart.
2. Their thrust gradually increases.
3. The forward propulsion motor slows.
4. The wings generate less lift as airspeed decreases.
5. The VTOL motors support the full weight of the aircraft.
6. The aircraft lands vertically.

---

## Design Considerations

Several design choices improve transition performance:

- Moderate wing loading
- NACA 2412 airfoil
- Center of gravity at approximately 30% of the wing chord
- Symmetrical placement of the VTOL motors
- ArduPilot flight controller for automatic transition management

---

## Future Work

Transition performance will be evaluated during flight testing and this document will be updated with any tuning changes made.
