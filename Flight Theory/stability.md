# Stability 

## What is Stability?

Stability is the ability for an aircraft to return to its original flight position after being acted upon by forces such as wind or turbulence.

A stable aircraft is easier to control.
---

## Types of Stability

### Longitudinal Stability (Pitch)

Longitudinal stability refers to stability in the pitch axis.

It is influenced by:

- Center of gravity (CG)
- Horizontal stabiliser
- Wing position

A correctly positioned CG helps the aircraft naturally maintain its pitch during flight.

---

### Lateral Stability (Roll)

Lateral stability refers to stability in the roll axis.

For this drone, lateral stability is improved by:

- Symmetrical wing design
- Equal placement of the four VTOL motors
- Balanced mass distribution

---

### Directional Stability (Yaw)

Directional stability refers to stability in the yaw axis.

This is primarily provided by the vertical stabiliser, which helps keep the aircraft aligned with its direction of travel.
However, although there is a vertical stabiliser on the aircraft, there is no rudder. The vertical stabiliser still provides directional stability during forward flight.

---

## Stability During VTOL Flight

During hover, the aircraft is stabilised using the four vertical lift motors.

The flight controller continuously adjusts the speed of each motor to maintain level flight.

---

## Stability During Forward Flight

During forward flight, stability is provided by:

- The wings generating lift
- The horizontal stabiliser controlling pitch
- The vertical stabiliser stabilising yaw
- The flight controller making small corrections

---

## Application to this Project

The Drone has been designed with stability as a main priority.

Design decisions that improve stability:

- Target CG at 30% of the wing chord
- Moderate wing loading
- NACA 2412 airfoil
- Conventional tail configuration
- Four-motor VTOL layout for balanced hover
- ArduPilot flight controller for active stabilisation
