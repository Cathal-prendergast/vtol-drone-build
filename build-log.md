**# 2026-04-08 to 2026-04-10**

## What I did
Designed the electronics bay section of the fuselage in Onshape. 
This component will house all electronics apart from the battery, 
which will be mounted in a separate section.

## Problems
Had not used Onshape since 2023 so the first session was
spent getting back up to speed. Comfortable with it again now.

## Decisions 
Separated the battery into its own chamber — it is too large to
fit alongside the other electronics, and a separate compartment
also allows better weight distribution and CG management.

Chose a flat oval cross-section for the fuselage so all electronics
sit neatly in the interior without wasted space.

## Next
Duplicate the current chamber and replace the platform to hold the
battery securely in place.

---

# 2026-05-04

## What I did
Redesigned the battery fuselage bay after figuring out the 
original shape and size wouldn't accomadate a 5000mAh 4s 50C LiPo battery.
The fuselage is now in the shape of a 80x80mm square with curved edges of a radius of 15mm.

## Problems
I will most likely be unable to place pusher propeller at the back of the drone
now since the square nature of the fuselage will block significant airflow into the propeller.

## Decisions
I will have to relocate the forward propeller into either a tractor or a twin-prop configuration. 
I will likely place it in the tractor configuration.

## Next
I will redesign the electronics fuselage bay into the same configuration as the battery bay.
I will also start to design the nose cone and tail, before I decide where to place the wing.

---

# 2026-05-08 to 2026-05-10

## What I did
Decreased the width of the fuselage walls to 1.5mm due to the original fuselage modules being overweight.
Finished designing the nose cone and almost finished the tail module which will house the motor for the pusher propeller.

## Decisions
I decided that the pusher propeller configuration could work with 11" propellers.
The tail section angles inwards towards the end of the tail to allow more airflow into the propeller.

## Next
I will finish off the tail section to fit the propeller motor and the H-tail.
I will start to design the fixed wing and assign it to the most optimal point based on the cg.

---

# Late May 2026 to 2026-06-10

## What I did
Designed the horizontal stabiliser and the elavators that will be controlled by a micro-servo.

## Decisions
I decided to begin to build a conventional tail to reduce the amount of PLA for the build and to make it a simpler build.

## Next
I will finish the horizontal stabiliser so it can accomadate a micro-servo on each side and design the rudder.
I will start to design the fixed wing and assign it to the most optimal point based on the cg.

---

# 2026-06-10 to 2026-06-25

## What I did
During this time period I continued to design the frame of the build along with planning and purchasing all the parts that will be included in the build.

---

# 2026-06-26

## What I did
I placed the connector for the wing at the centre of gravity of the fuselage of the aircraft. 
I calculated the optimal area of the wing to be 283,000mm^2 using the lift equation on nasa.gov and rearanging it to A = (2mg)/CrV^2 where L = W = mg in horizontal flight.

## Decisions
I chose the chord length of the wing to be 235.83mm to ensure it is able to print on the 220x220x250mm bed of the Sovol SV06 Ace.
The length of each wing will be 600mm, which will create an overall wingspan of 1.2 metres.
I decided to have the micro-servos controlling the elavators to instead rotate the entire horizontal stabilisers. I did this because the elavators on the horizontal stabilisers would be to small for the micro-servos to move.

## Next
I will continue to design each wing segment to connect up to eachother and allow a 1 metre 12mm carbon fibre tube inside it to be used as a wing spar.

---

# 2026-07-01 to 2026-07-14
## What I did
I had to wait to start 3D printing the fuselage because my Sovol SV06 Ace's power supply unit malfunctioned. As a result, I had to wait until the 14th of july before i could start printing again.
In this time I finished designing the ailerons on the wings and have a surface area of []. I also soldered the GPS and Compass module(HGLRC M100) and the Reciever(Radiomaster RP4TD) to the Flight Controller.

## Decisions
I decided to solder the GPS and Compass module and the Reciever directly to the Flight Controller rather than using the pins that accompany the FC. 
I did this mainly due to reliability: a soldered joint is less likely to work loose from vibration and disconnect mid-flight.

## Next
I will mount the pusher motor onto the tail modue once it finishes printing and connect its dedicated ESC to it.
I will also order two 11x5.5 inch propellers but in the CCW configuration. The VTOL propellers are supposed to have 2 CW propellers and 2 CCW propellers rotating in the opposite direction to avoid rotating, but I mistakingly purchased all CWs

---

# 2026-07-15
## What I did
There was an error in the 3D printer overnight which stopped the print of the tail at exactly 60mm. This was likely an error in the G-Code.
I printed the remaining part of the print and super-glued it on top. I then came accross an error I made in the M3 holes that would connect the pusher motor to the fuselage; I originally designed it to accommodate the motor on the inside of the fuselage with the motor shaft sticking out the back,
but after analysing the motor dimensions I realised that the motor would have to be mounted on the outside of the fuselage, and as a result pushing the CG back. To fix this, I shortened the length of the tail module to the point where it can accommodate the ESC and the two Micro-Servos. 
The Motor will still be mounted on the outside but this brings the Center of Gravity back to its original position and reduces weight.
I rearranged the layout of the wing segments to allow the 12mm carbon fibre spar to fit through it uninterrupted after I realised it would get in the way of the 136 x 44 x 43.5mm battery. 
I created 16.1mm diameter holes in both the front and rear fuselage modules that will allow the 16mm carbon fibre tube of 1mm thickness to go through the fuselage and support the VTOL motors. 
I chose the location for these based off the Center of Gravity(180mm in both directions). Each 16.1mm hole accompanies a 14mm hole that will allow wire to pass through to the motors.
I started printing the front module of the fuselage that will hold the Flight Controller, GPS + Compass module, Reciever, and airspeed sensor with PETG but had to reprint multiple times becaus eoof print failures with the filament.
The module is printing currently after I adjusted the bed temperature, nozzle temperature, and speed of the printer and is printing well at the moment.
If this print fails again I will have to repring again and change the material to PLA.

## Decisions
I decided to shorten the tail module to bring the CG forward after I identified a mistake in the design.
Chose the VTOL motors position based off the CG of the aircraft.
I am printing the first module of the fuselage with PETG because of the impact resistance, fatigue resistance, and outdoor reliabilty.
Fatigue resistance is crucial for this module as it contains the Carbon Fibre tube that will accompany vibrations from the motors.

## Next
Finish printing the first module of the fuselage
Print the second module of the fuselage and so on.
Seperate the one metre 12mm carbon fibre tube into two equal tubes of length 500mm for the VTOL motor arms.
Connect the Flight Controller and electronics assigned to the front module into it.

---

# 2026-07-16
## What I did
The 3D printer fully clogged while printing the first module of the fuselage and I had to turn off the printer and end the print prematurely. The print ended as it was nearly done just before the connectors were printed.
To overcome this I will superglue the Nose Cone to the front of the fuselage instead of connecting it with nuts and bolts. It will be permenantly fixed to the first module of the fuselage but saves weight.
The Nose cone weighs roughly 30 grams and only contains the pitot tube so the First module will not be under any extra structural strain.
Reprinted the Nose Cone after I made modifications to the design: a 3.5mm hole for the pitot ube in the center, a thinner wall to save weight, and a large part of where the connector was as it isnt needed anymore.
I drilled a 4mm hole after the 3.5mm hole was to tight for the pitot tube.
Reprinted the Tail module after I made modifications to the design: shorter, a 4mm wall mount to prevent cracking due to the 1.5mm wall's fragility.

## Decisions
Decided to superglue the Nose Cone to the first module instead of reprinting the module again.
This would have taken an extra 11 hours.

## Next
The second module of the fuselage is currently printing.
I will continue to print the rest of the parts.
Once the second module finishes printing I will connect it up to the first module and install their dedicated electronics.
Will file the inside of the 16.1mm and 12.1mm hole to allow the 16mm and 12mm carbon fibre tube to pass through.
