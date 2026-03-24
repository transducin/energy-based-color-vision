# energy-based-color-vision
This repository documents an exploratory model probing whether  semantic-like states can emerge from energy-constrained,  binary decision dynamics under minimal computation.
# OBA Color Vision — Energy-Coupled Perceptual Dynamics

## Overview

This project explores a simple but fundamental hypothesis:

> When a system passively receives physical signals, and evaluates only its own internal energy changes under a constraint of minimizing further computation, it may spontaneously produce diverse intermediate semantic states.

The goal is not to reproduce biological vision, nor to optimize performance,
but to probe whether **semantic diversity can emerge from energy-constrained decision processes**.

---

## Core Assumptions

The model is built on the following principles:

1. **Physical signals are treated as native encoded inputs**
   (no symbolic preprocessing or supervised labels)

2. **The system has no predefined response goal**

3. **Perception arises from coupling between input energy and internal energy dynamics**

4. **Each computation step favors early stopping**
   (to avoid further energy consumption)

5. **Decisions are fundamentally binary at the lowest level**

---

## What This Model Demonstrates

Using visual spectral inputs, the system shows:

* Emergence of **multiple semantic intermediate states**
* Formation of **stable vs. metastable trajectories**
* Early-stage divergence between competing interpretations (e.g., color vs. brightness)
* Output diversity driven by **energy fluctuation and stopping dynamics**, rather than explicit objectives

---

## Structure of the Project

* `light_sommelier/`
  Core implementation for visual spectral processing

* `notebooks/`
  Experimental runs and visualization (UMAP, trajectory plots, etc.)

* `figures/`
  Generated plots illustrating system dynamics

---

## Notes

* This is an **exploratory system**, not an optimized model
* No training data, labels, or loss functions are used
* All observed structures (clusters, attractors, flows) are **emergent**

---

## Ongoing Directions

The same framework is being tested across other sensory modalities:

* Auditory signals (time-structured input)
* Olfactory patterns
* Gustatory signals
* Tactile inputs

---

## Intent

This project is not meant to assert how perception works.

It is an attempt to ask:

> Under minimal assumptions, what kind of structure is *forced to appear*?

---

## Author Notes

Designed as a conceptual experiment by a long-term researcher in biological perception,
implemented and extended in collaboration with a computational partner.

---
