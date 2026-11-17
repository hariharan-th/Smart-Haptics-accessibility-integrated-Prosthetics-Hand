# ASHA-SPARSH Prosthetic Device

ASHA-SPARSH is a concept for an affordable, sensor-driven upper-limb prosthetic terminal device for people with partial-hand amputations. The idea was presented by team GOODFELLAS1 for Smart India Hackathon 2024, problem statement SIH25146 (MedTech / BioTech, hardware).

This repository is the starting point for the project. The source presentation describes the concept and a prototype direction; it does not include firmware, CAD files, schematics, test data, or a clinically validated device yet.

## Concept

The proposed device combines hand movement with touch feedback:

- **Sensing:** touch, pressure, and piezoelectric fingertip sensors detect contact.
- **Control:** a microcontroller interprets sensor input and drives the hand mechanism.
- **Actuation:** a servo motor and gear mechanism control grip movement. A relay module is shown in the presentation's system diagram.
- **Feedback:** a vibration motor provides tactile feedback to the wearer.
- **Fabrication:** the presentation describes custom plaster and resin fabrication, with CATIA design and ANSYS simulation.

The presentation also suggests a future tap-gesture band and an RF-connected revision of the prototype. These are future concepts, not implemented features.

## Current status

**Idea / prototype planning.** No code, CAD, circuit design, or reproducible test results have been added yet.

Suggested next steps:

1. Define user needs, intended use, and measurable acceptance criteria with prosthetics and rehabilitation specialists.
2. Document the hand mechanism, sensor choices, microcontroller, power system, and wiring.
3. Add CAD exports, circuit diagrams, firmware, and a bill of materials as they become available.
4. Record repeatable bench tests for grip force, response, battery life, comfort, durability, and failure behavior.
5. Review electrical, mechanical, usability, and applicable regulatory requirements before any human use.

## Claims to validate

The presentation proposes a price below ₹50,000, grip force up to 45 N, 12–16 hours of battery life, and water/dust resistance. These are presentation claims and targets, not verified specifications. Publish supporting test methods and results before treating them as product specifications. The presentation also mentions patent-pending protection; this repository makes no independent claim about patent status.

## Repository layout

- docs/ — design notes, requirements, and test records
- firmware/ — controller source code
- hardware/ — schematics, PCB files, and bills of materials
- mechanical/ — CAD exports and fabrication notes
- tests/ — test procedures and results

Directories will be added as project files become available.

## Safety

This repository describes an engineering project, not medical advice or a ready-to-use medical device. Do not use an unvalidated prototype on a person. Evaluate mechanical pinch/crush hazards, electrical and thermal risks, battery protection, skin-contact materials, and loss-of-control behavior. Human testing requires appropriate clinical supervision, informed consent, and applicable approvals.

## Source

Initial concept summary is based on the team's ideas.pptx submission (Smart India Hackathon 2024). The presentation remains in the project owner's source folder and has not been uploaded to this repository.
