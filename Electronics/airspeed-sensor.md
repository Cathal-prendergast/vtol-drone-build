# Airspeed Sensor

## Overview

The aircraft uses an airspeed sensor connected to a pitot tube to measure the speed of air flowing around the aircraft.

Airspeed is particularly important for a fixed-wing VTOL because the aircraft must maintain sufficient airspeed during forward flight and transition.

---

## Pitot Tube

The pitot tube measures the pressure of the air moving around the aircraft.

The airspeed sensor uses this pressure information to calculate the aircraft's airspeed.

The pitot tube will be mounted in the nose cone where it receives undisturbed airflow.

---

## Purpose

The airspeed sensor provides information that can be used for:

- Monitoring forward-flight speed
- Maintaining an appropriate airspeed
- VTOL transition
- Avoiding excessively low airspeed
- Flight testing

Airspeed is different from GPS ground speed because wind can cause the aircraft's airspeed and ground speed to differ.

---

## Connection

The airspeed sensor is connected to the Matek F405-VTOL flight controller.

ArduPilot can then use the measured airspeed during flight.

---

## Importance During VTOL Transition

During transition, the aircraft needs to accelerate enough for the wings to generate sufficient lift.

Airspeed information can then be used to help determine whether the aircraft has reached an appropriate speed for the transition between VTOL and fixed-wing flight.

---

## Installation and Testing

The pitot tube will be positioned  on the nose cone where it is away from propeller wash and other disturbed airflow.

Before flight, the sensor will be checked to ensure that:

- It reports a sensible reading while stationary.
- The pressure tubing is correctly connected.
- Airspeed increases when airflow is applied to the pitot tube.
- ArduPilot receives the sensor data correctly.
