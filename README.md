# RISPE: Retinomorphic Mid-Wave Infrared In-Sensor Processing Engine

M.S. thesis (NJIT, 2026) on analog in-sensor computation for energy-efficient MWIR vision, featuring a field-effect-gated PbSe photodiode and device-to-architecture co-design.

## Summary

This thesis introduces RISPE, a retinomorphic in-sensor processing architecture for mid-wave infrared (MWIR) machine vision. A field-effect-gated PbSe photodiode generates programmable positive, negative, and near-zero photocurrents, enabling analog multiply-and-accumulate (MAC) operations directly within the sensor array. This reduces data movement and enables early-stage feature extraction before digitization.

## Key Contributions

- Field-effect-gated, reconfigurable PbSe MWIR photodiode with TCAD-validated device modeling, achieving programmable bipolar (positive/negative) photocurrent generation
- TCAD-calibrated compact device model implemented in HSPICE, validated to 0.63% mean relative error across 4,900 operating points
- Mixed-signal CMOS readout chain design (180nm) integrating current-domain biasing, R–2R DAC, sample-and-hold, and a flash ADC with StrongARM comparators
- RISPE crossbar architecture performing in-sensor analog multiply-and-accumulate (MAC) operations via current summation
- Cross-layer evaluation framework spanning device (TCAD), circuit (HSPICE/Spectre), and architecture levels, demonstrating 1.538 µJ/frame energy and over 4.5 kFPS throughput

## Full Thesis

📄 [Full PDF](https://digitalcommons.njit.edu/theses/3554/)
