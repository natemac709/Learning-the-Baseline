# 🗜️ Learning the Baseline: The Pedestal Product Line R&D

This document serves as the master engineering sandbox and prototyping file for **The Pedestal** product family. The Pedestal line consists of standalone, single-verse desktop displays that exist independently of the main smartphone "Book Box" hardware framework. 

Use this file to log mechanical, optical, and kinetic electronic drafts for physical tabletop units.

---

## 👁️ 1. Core Vision & Product Split

While the main Book Box framework focuses on physical containment and device locking, the Pedestal product family is designed to elevate a single, unchanging weekly record in common living spaces (desks, counters, entryways). 

We are incubating two separate product tracks under this lineage:
1. **The Analog Prism:** A heavy, museum-grade cast acrylic block that physically anchors a single printed card.
2. **The Kinetic Loom:** A dedicated, standalone electronic device (non-smartphone) that sweeps text into mid-air using physical motion and light persistence.

---

## 🪵 2. Track A: The Analog Acrylic Block Prism

### The Philosophy
By sliding a premium printed scriptural record beneath or inside a heavy, solid block of light-refracting acrylic, the truth is given immediate physical volume, gravity, and presence on a surface. It forces the human eye to slow down and focus.

### Material & Form Factor Targets
* **Substrate Type:** 100% crystal-clear cast acrylic (PMMA / Lucite) with flame-polished, chamfered bevel edges to reduce glare and maximize internal light refraction.
* **Dimensions (Prototype P-1.0):** $3.0\text{"} \times 3.0\text{"} \times 1.0\text{"}$ solid block. Weight profile targeted at approximately 0.5 lbs to act as an un-yielding desktop paperweight.

---

## ⚡ 3. Track B: The Kinetic Loom (POV Waving-Arm Display)

### The Philosophy
Inspired by retro-futuristic mechanical desk clocks, this track explores using **Persistence of Vision (POV)** kinetics to display the weekly text. Instead of a flat, glowing glass consumer screen that invites scrolling, the text is woven dynamically into thin air by a physical, swinging pendulum. This provides an analog, hypnotic rhythm that demands attention.

### Technical & Electronic Architecture Concepts
* **The Motion Mechanism:** A silent, precision-balanced mechanical pendulum arm or oscillating vertical propeller driven by a low-voltage DC stepper motor or electromagnetic coil.
* **The Display Engine:** A tight line of micro-addressable RGB LEDs mounted along the sweeping edge of the pendulum blade. 
* **The POV Effect:** By micro-controlling the blink timing of the LEDs via an onboard microcontroller (e.g., Arduino Nano architecture) synchronized to the exact frequency of the physical sweep, characters appear to float completely detached in mid-air.
* **System Interface:** Completely offline. Text changes are updated via a local physical SD card slot or manual button dials to maintain zero internet connectivity and absolute data isolation.

---

## 📐 4. Experimental Prototyping Sandbox Matrix

| Iteration ID | Product Track | Substrate / Mechanics | Power Source | Form Factor Target |
| :--- | :--- | :--- | :--- | :--- |
| `P-v1.0-A` | Analog Prism | Cast Acrylic / Solid Block | N/A (Static) | Paperweight Cube Base |
| `P-v2.0-K` | Kinetic Loom | Oscillating Pendulum / POV LED | 5V USB-C Wall Power | Minimalist Desktop Plinth |
| `P-v2.1-K` | Kinetic Loom | Rotating Propeller Ring / POV | 5V USB-C Wall Power | Spherical Glass Orb Dock |

---

## 🎯 5. Process & Manufacturing Aspirations

* **Aspiration 01 (Mechanical Silence):** Optimize the pendulum swing geometry on Track B to ensure silent operation, allowing the unit to hum quietly on a nightstand or workspace without causing auditory fatigue.
* **Aspiration 02 (DPI Typographic Sharpness):** Calibrate the microsecond LED timing sequences so the floating text characters appear perfectly crisp, sharp, and stable, without ghosting or visible flickering.
* **Aspiration 03 (Dignity of Display):** Ensure both the analog acrylic block and the kinetic display present the verse with a timeless, architectural elegance that fits naturally into both corporate offices and family households.

---

## 🪵 6. ChangeLog & Project Graduation

Use this ledger to record when a physical display prototype is graduated out of this R&D incubator and into localized manufacturing blueprints.

* **2026-06-09:** R&D charter rewritten. Split the Pedestal concept away from the Book Box framework. Formally established Track A (Static Acrylic Block) and Track B (Kinetic POV Waving-Arm Display) design parameters.
