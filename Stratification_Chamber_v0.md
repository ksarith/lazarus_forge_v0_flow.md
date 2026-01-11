# Stratification Chamber v0 — Selective Separation Module

## Purpose

The Stratification Chamber is a **pre-purification decision module** within the Lazarus Forge.
Its goal is to **divert material away from energy-intensive melting and refinement**
by recovering usable fractions earlier in the process.

It is not a smelter, refinery, or guarantee of purity.

Success is defined by *avoided processing*, not perfect separation.

---

## Position in System Flow

The Stratification Chamber operates **after Reduction** (cutting/shredding)
and **before Purification**.

---

## Design Philosophy

- Preserve function before destroying structure
- Prefer classification over purification
- Allow explicit “unknown” and “fail” outputs
- Optimize for learning and tunability, not peak throughput
- Replicate chambers to scale, do not over-enlarge

---

## Inputs

- Reduced metallic feedstock (non-powdered)
- Mixed alloys, fasteners, coatings, or contamination allowed
- Known upstream envelope (particle size, mass range)

---

## Core Subsystems (v0)

### 1. Rotational Drum / Rotor

- Provides controlled angular acceleration
- Operates across tunable RPM bands
- No requirement for high temperature operation

Purpose: expose differences in density, geometry, ductility, and inertia.

---

### 2. Optional Field Bias (Deferred)

- Magnetic or electromagnetic biasing may be added in later versions
- Not required for v0 validation
- Must never force separation beyond observable stability

---

### 3. Collection Zones

- Radial or axial bins
- Capture fractions that stabilize under rotation
- Geometry favors repeatable, low-chaos trajectories

---

### 4. Fail / Eject Path

- Unstable, bouncing, or ambiguous material is explicitly rejected
- Failures are logged, not hidden
- Fail output is routed to further reduction or bulk stock

---

## Outputs

- **Class A:** Usable components or near-components  
- **Class B:** Downgraded material (repurpose / lower-precision use)  
- **Class C:** Mixed bulk → Purification  
- **Fail:** Unclassifiable → Reduction or discard  

The system must always be able to say “no.”

---

## Scaling Strategy

- Multiple small chambers are preferred over single large units
- Scaling occurs by replication, not enlargement
- Chambers may be tuned for specific material classes

Scaling triggers include:
- Input backlog exceeding dwell capacity
- Wear rate exceeding maintenance window
- Declining classification confidence

---

## Falsifiable Performance Metric (Primary)

**Material Diversion Rate**

Target for v0 exploration (not a guarantee):
- ≥ 30% diversion indicates viability
- < 10% indicates redesign or removal

This metric exists to test whether the chamber meaningfully reduces
energy and complexity downstream.

---

## Explicit Non-Goals (v0)

- Achieving high-purity metal output
- Replacing smelting or electrorefining
- Handling powdered feedstock
- Solving all alloy separation problems

---

## Notes

- The Stratification Chamber is a *decision amplifier*, not a solution by itself
- Its value increases as upstream reduction and downstream logic improve
- Honest failure improves system learning
