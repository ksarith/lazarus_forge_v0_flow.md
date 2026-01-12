Lazarus Forge — Component Triage System

> Role: Decision gateway between reuse and destruction.

The Component Triage System exists to answer one question with speed, honesty, and minimal energy:

Can this component or subassembly still function—or be restored to function—at lower total cost than fabricating a new one?



Everything that passes triage is preserved as embodied complexity.
Everything that fails triage enters material recovery.

Triage always occurs before any material enters destructive processing.


---

I. Core Principles

1. Non-Destructive First
Never destroy or disassemble a component if a non-invasive test can establish viability.


2. Progressive Depth
Begin with the fastest, lowest-energy test. Escalate only when value is plausible.


3. Human–Machine Hybrid
Early forges rely on human judgment. Automation increases only after repeatable patterns emerge.


4. Energy & Time Accounting
Each test has a known energy/time cost. A component must justify deeper testing.


5. Traceability
Every triaged item receives a physical provenance tag (QR, RFID, etched mark, or paint code).




---

II. Triage Workflow Overview

Incoming material is pre-sorted by humans or crude mechanical means (size, magnetism, bulk type).

Components then pass through modular triage stations. Stations may be skipped if earlier results are decisive.


---

III. Modular Triage Stations

Station 0 — Visual & Basic Mechanical (Human + Simple Tools)

Purpose: Rapid rejection of obvious failures.

Visual inspection for cracks, burns, deformation, corrosion

Manual spin, shake, and resistance checks

Electrical continuity check (where applicable)


Decision time: < 2 minutes per item

Tools:

Flashlight

Multimeter

Marker / paint pen

Bins labeled: Good / Maybe / Scrap



---

Station 1 — Electrical & Electronic Components

Priority Items:

Motors

Transformers

Batteries

Inverters

PCBs

Solenoids


Test Rigs:

Motor Test Bench

DC or AC supply

Variable load (resistive bank, dynamo, or friction brake)

Measures:

No-load current

Stall torque (approximate)

Winding resistance

Insulation resistance



Pass Guidance:

≥ ~70% of expected performance or “sufficient for forge duty”


Battery Test

Charge–discharge cycle

Accept partial capacity for stationary use


Electronics Screening

ESR and capacitance checks

Visual inspection for thermal damage



---

Station 2 — Mechanical Components

Priority Items:

Bearings

Gears

Linear rails

Pumps

Structural members


Methods:

Bearing Spin Rig

Motorized spindle

Vibration sensor (MEMS accelerometer acceptable)

Audible and spectral noise assessment


Gears & Linkages

Visual wear comparison charts

Go/no-go gauges (forge-made)

Lubricant inspection (color, smell, particulates)


Structural Metal

Ultrasonic thickness measurement

Simple bend or load testing jigs



---

Station 3 — Functional Subassembly Test

Targets:

Gearboxes

Power tools

Pumps

Fans


Method:

Standardized plug-and-play harnesses

Known loads (water column, inertia wheel, resistive load)

Runtime: 5–15 minutes


Outcomes:

Pass → Direct reuse stock

Partial → Repair queue

Fail → Disassemble for sub-components or scrap



---

Station 4 — Assisted Borderline Evaluation (Later-Stage Forge)

Introduced gradually as data accumulates.

Vision-based crack and wear detection

Acoustic analysis of motor hum

Comparison against historical triage outcomes

Predictive lifespan estimation


This station never overrides earlier stations—it only refines borderline calls.


---

IV. Data & Learning Loop

Each triage event records:

Component type

Source object

Tests performed

Energy/time spent testing

Decision outcome

Eventual fate (used, repaired, scrapped)


Early systems may log on paper. Later systems digitize and aggregate.

This data refines:

Pass/fail thresholds

Test ordering

Repair vs replace heuristics



---

V. Minimum Viable Triage (Gen-1 Forge)

A first-generation forge can operate with:

One skilled human operator

Multimeter

12 V / 48 V battery bank

Salvaged loads (lights, heaters, pumps)

Handwritten performance board for known-good components


This alone preserves the motors, bearings, and power hardware required to bootstrap the Forge.


---

VI. Guiding Axioms

Test cheap. Destroy expensive.

A marginal component today beats a perfect ingot tomorrow.

Doubt means test deeper. Certainty means move fast.



---

> Triage is not about hoarding. It is about respecting embodied work already paid for by the universe.



This document evolves only with demonstrated operational need.
