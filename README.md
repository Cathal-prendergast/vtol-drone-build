# vtol-drone-build

**My Project Goals:**

- Design a custom VTOL fixed-wing airframe from scratch in Onshape.
- 3D print and assemble the aircraft.
- Configure and tune ArduPlane for stable flight and VTOL transition.
- Achieve autonomous waypoint flight.

**Current Status:** Phase 4 – First Flight Test
Hover achieved on the second attempt (29 Oct 2026), with the wings off. , refit the wings and hover with them on. Details in the [build log](Build%20Log/build-log.md).

First hover attempt (11 Oct 2026) failed: the aircraft was unstable on take-off, the motors surged and it flipped, breaking part of the airframe. There was no SD card in the flight controller, so no log was recorded. The airframe has been repaired; the next hover attempt will be made with the wings removed. Details in the [build log](Build%20Log/build-log.md).

**Build Phases:**

1. Design: Airframe geometry, motor placement, and layout in Onshape
2. Print & Assemble: 3D printing components and assembling the airframe
3. Initial Configuration: ArduPlane setup
4. First Flight Test: First hover test, basic fixed-wing flight
5. VTOL Transition: Tuning the transition between multirotor and fixed-wing modes
6. Autonomous Flight: Waypoint navigation and automated mission

**Flight Tests:**

- 29 Oct 2026 – Hover attempt 2 (Successful) – [![Hover attempt 2 Video](https://img.youtube.com/vi/KN1wUZc8THk/0.jpg)](https://youtu.be/KN1wUZc8THk), [build log entry](Build%20Log/build-log.md)
- 11 Oct 2026 - Hover attempt 1 (Failed) - [Video](Hover-Attempt-1)

**Documentation:**

- [Build log](Build%20Log/build-log.md) – dated entries
- [Project overview](Documents/Project-Overview.md)
- [Design decisions](Documents/design-decisions.md)
- [Bill of materials](Documents/Bill-of-Materials.md)
- [Wiring](Documents/Wiring.md)
- [System architecture](Documents/system-architecture.md)
- [3D printing](Manufacturing/3D-printing.md)
- Electronics: [flight controller](Electronics/flight-controller.md) , [power](Electronics/power-system.md) , [propulsion](Electronics/propulsion-system.md) , [GPS](Electronics/gps.md) , [receiver](Electronics/receiver.md) , [airspeed sensor](Electronics/airspeed-sensor.md) , [servos](Electronics/micro-servos.md)
- Flight theory: [lift](Flight%20Theory/lift.md) , [wing loading](Flight%20Theory/Wing-Loading.md) , [thrust-to-weight](Flight%20Theory/thrust-to-weight.md) , [centre of gravity](Flight%20Theory/center-of-gravity.md) , [stability](Flight%20Theory/stability.md) , [VTOL transition](Flight%20Theory/VTOL-Transition.md)
- [Onshape CAD model](https://cad.onshape.com/documents/dc6c3d95712bc08a64883782/w/311f408924852cf70bd93cce/e/4d2703410e0329fb67e0ef8a?renderMode=0&uiState=69da57090b1882f0263f14a8)

**Tech Stack:**

- CAD: Onshape
- Flight Control: ArduPlane, Mission Planner, QGroundControl
