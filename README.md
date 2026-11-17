# Smart Haptics accessibility integrated Prosthetics Hand 

Haptix Prosthetics is an engineering project exploring an affordable, sensor-driven upper-limb prosthetic terminal device for people with partial-hand amputations.

This repository is an early project space. The initial concept notes describe a prototype direction; firmware, CAD files, schematics, test data, and clinical validation have not yet been added.

## Concept

The proposed device combines hand movement with touch feedback:

- **Sensing:** touch, pressure, and piezoelectric fingertip sensors detect contact.
- **Control:** a microcontroller interprets sensor input and drives the hand mechanism.
- **Actuation:** a servo motor and gear mechanism control grip movement. A relay module is included in the initial system concept.
- **Feedback:** a vibration motor provides tactile feedback to the wearer.
- **Fabrication:** the concept notes describe custom plaster and resin fabrication, with CATIA design and ANSYS simulation.

A tap-gesture band and an RF-connected revision are possible future directions. They are not implemented features.

## Current status

**Concept and prototype planning.** No code, CAD, circuit design, or reproducible test results have been added yet.

Suggested next steps:

1. Define user needs, intended use, and measurable acceptance criteria with prosthetics and rehabilitation specialists.
2. Document the hand mechanism, sensor choices, microcontroller, power system, and wiring.
3. Add CAD exports, circuit diagrams, firmware, and a bill of materials as they become available.
4. Record repeatable bench tests for grip force, response, battery life, comfort, durability, and failure behavior.
5. Review electrical, mechanical, usability, and applicable regulatory requirements before any human use.

## Claims to validate

The concept notes propose a price below ₹50,000, grip force up to 45 N, 12–16 hours of battery life, and water/dust resistance. These are targets, not verified specifications. Publish supporting test methods and results before treating them as product specifications.

## Repository layout

- docs/ — design notes, requirements, and test records
- firmware/ — controller source code
- hardware/ — schematics, PCB files, and bills of materials
- mechanical/ — CAD exports and fabrication notes
- tests/ — test procedures and results

Directories will be added as project files become available.

## Safety

This repository describes an engineering project, not medical advice or a ready-to-use medical device. Do not use an unvalidated prototype on a person. Evaluate mechanical pinch/crush hazards, electrical and thermal risks, battery protection, skin-contact materials, and loss-of-control behavior. Human testing requires appropriate clinical supervision, informed consent, and applicable approvals.
