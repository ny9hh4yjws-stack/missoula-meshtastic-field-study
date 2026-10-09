# missoula-meshtastic-field-study
Missoula Meshtastic Field Study

Overview

An ongoing, independent field study of Meshtastic LoRa communications in Missoula, Montana, beginning October 7, 2026.

The study examines off-grid communication, RF propagation, urban and mountainous terrain, mesh routing, antenna performance, fixed base stations, and mobile stations.

Research Objectives

* Establish repeatable RF coverage baselines.
* Compare successful acknowledgments with failed message deliveries.
* Evaluate terrain, obstructions, elevation, and antenna placement.
* Investigate direct and multi-hop mesh communications.
* Compare October 7 baseline tests with October 8 repeat tests.
* Explore Raspberry Pi integration, logging, and off-grid operation.
* Evaluate potential rooftop elevation and solar-powered deployments.

Equipment

* Ronin07: Fixed home-base Heltec Meshtastic radio.
* Shino: Mobile Meshtastic radio used during field testing.
* External 915 MHz antennas.
* Raspberry Pi for configuration and potential future logging.
* iPhone and iPad for radio interaction and documentation.

Field Study Timeline

October 7, 2026 — Baseline

Initial 15-location Missoula field testing documented delivery acknowledgments, failed transmissions, node observations, and terrain conditions.

Known observations include:

* Downtown Clearwater Credit Union: acknowledged direct message.
* North Davis Street: message reached maximum retransmissions without acknowledgment.
* Albertsons on North Reserve: acknowledged message.
* Location 15 near the VA Clinic area: acknowledged message.

October 8, 2026 — Repeat Testing

A second Meshtastic radio, Shino, was deployed as the mobile station while Ronin07 remained at home base.

The repeat study examined acknowledgment behavior, node discovery, routing observations, and the effect of base antenna placement.

An observation of a node reported four hops away is retained for further investigation rather than treated as proof that a four-hop message was delivered.

Analysis Method

October 9, 2026 — Phase 3 Field Testing

The complete Ronin07 base radio assembly was relocated above the roofline for further RF performance testing.

The original Missoula field-test route was repeated, with additional mobile and stationary observations extending to Arlee, Montana.

Testing documented mesh acknowledgments, node visibility, antenna placement, and possible effects of an earlier power interruption.

[Read the October 9 Phase 3 Field Study](docs/phase-3-field-study-2026-10-09.md)



Original screenshots, photographs, GPS records, timestamps, and device settings will be retained as primary evidence when available.

Observed results will be distinguished from estimated positions, modeled propagation, and hypotheses.

Acknowledgments alone do not necessarily establish the exact RF path or prove direct communication with the base station.

Planned Repository Structure

* field-tests/
* hardware/
* rf-analysis/
* evidence/
* diagrams/
* future-experiments/

Open Device Bridge Connection

This field study is related to the broader Open Device Bridge (ODB) initiative, which investigates cross-platform access to embedded devices, configuration, flashing, recovery, and hardware interoperability.

ODB repository: https://github.com/ny9hh4yjws-stack/open-device-bridge

Future Work

* Repeat field measurements with the entire base radio and antenna elevated above the roofline.
* Compare radio performance at different antenna elevations.
* Develop terrain-based RF coverage visualizations.
* Investigate logging and automated testing via Raspberry Pi.
* Evaluate solar-powered remote nodes.
* Publish reproducible measurement procedures and properly documented results.

Research Status

Active field study. Findings are preliminary and subject to validation.

Privacy

Public documentation should avoid disclosing private residential coordinates, identifying details, or unnecessary personal information.
