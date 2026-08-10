# Radio Receiver

## Component

**RadioMaster RP4TD ELRS 2.4GHz Receiver**

The receiver provides the communication link between the radio controller and the aircraft's flight controller.

---

## Purpose

The receiver allows the pilot to control the aircraft during manual flight and provide commands to ArduPilot.

The system will be used for:

- Manual flight
- Flight-mode selection
- Arming and disarming
- Control during testing
- Emergency intervention during autonomous flight

---

## Radio System

The aircraft uses the **ExpressLRS (ELRS)** 2.4GHz radio system.

The receiver communicates with the RadioMaster Pocket M2 transmitter.

ELRS was selected for its long range, low latency and suitability for model aircraft.

---

## Connection

The receiver is connected to the Matek F405-VTOL flight controller.

Pilot inputs are sent from the transmitter to the receiver and then passed to the flight controller.

The flight controller uses these inputs to control the aircraft according to the selected flight mode.

---

## Failsafe

A failsafe is required in case communication between the transmitter and aircraft is lost.

The aircraft's failsafe behaviour will be configured in ArduPilot before flight testing.

This will be tested on the ground before the aircraft is flown.

---

## Testing

Before flight, the radio system will be tested for:

- Successful binding
- Correct channel inputs
- Correct control directions
- Reliable signal
- Correct failsafe behaviour
