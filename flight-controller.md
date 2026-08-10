# Flight Controller

## Component

**Matek F405-VTOL**

The Matek F405-VTOL is the main flight controller of the aircraft. It is responsible for processing sensor data, receiving pilot commands, controlling the motors and servos, and managing the different flight modes.

---

## Role in the Aircraft

The flight controller is the central control system of the aircraft.

It receives information from:

- GPS and compass
- Airspeed sensor
- Radio receiver
- Internal flight sensors

It then uses this information to control:

- Four VTOL motors
- Forward propulsion motor
- Aircraft servos

This allows the aircraft to maintain stability during hover, forward flight, and VTOL transition.

---

## VTOL Operation

During hover, the flight controller continuously adjusts the four VTOL motor outputs to keep the aircraft stable.

For example, if the aircraft begins to roll to one side, the flight controller can change the thrust of individual motors to correct the roll.

During forward flight, the flight controller controls the aircraft's control surfaces and forward propulsion.

---

## Power Distribution

The Matek F405-VTOL includes an integrated power distribution system.

The 4S LiPo battery connects to the board, which distributes battery power to the five ESCs and provides power to the flight controller and other electronics.

This removes the need for a separate external power distribution board.

---

## Flight Software

The flight controller will run **ArduPilot ArduPlane** with the QuadPlane functionality required for VTOL operation.

ArduPilot will be configured to manage:

- VTOL flight
- Fixed-wing flight
- VTOL-to-forward-flight transition
- Forward-flight-to-VTOL transition
- GPS navigation
- Autonomous waypoint missions
- Flight stabilisation

---

## Integration

The flight controller acts as the central connection point between the aircraft's electrical and control systems.

The final wiring is documented in [Wiring.md](../main/Wiring.md).
