# Execution-Time Phase Exposure in Quantum Circuits

**Author:** A. R. Wells  
**Affiliation:** Dual-Frame Research Group  
**License:** CC BY 4.0  
**Contact:** No solicitation for correspondence or media contact  
**Paper email:** arwells.research@proton.me  

---

## Overview

This repository contains a public whitepaper on execution-time phase exposure as a diagnostic layer for quantum circuit evaluation.

The central observation is that coherence risk is not determined by total idle time alone. Idle time becomes consequential when it overlaps a phase-bearing execution window: an interval in which a qubit carries phase-sensitive structure relevant to a later readout.

The whitepaper frames this distinction from a compact-fiber readout perspective. Observable circuit behavior is treated as readout-conditioned structure, so the diagnostic question is not only how much time elapses, but where elapsed time falls relative to phase creation, phase transport, entanglement dependencies, and readout.

## Hardware validation

The whitepaper reports sanitized aggregate validation results from contemporary superconducting quantum hardware. The validation compares logically equivalent or task-equivalent circuit variants designed to isolate execution-time exposure placement while controlling aggregate metrics where applicable, including gate count, logical depth, total idle time, and hardware coherence parameters.

The reported results support the central claim: variants with greater idle exposure inside phase-bearing windows exhibited degraded measured outcomes relative to lower-exposure variants, even when aggregate metrics alone did not distinguish them.

## Scope

This repository is a public whitepaper release. It describes the diagnostic principle, compact-fiber interpretation, validation summary, and engineering motivation at a whitepaper level.

It does not include circuit definitions, job identifiers, report schemas, implementation details, or non-public workflow material.

## Files

    phase_exposure_whitepaper.pdf      Whitepaper PDF
    phase_exposure_whitepaper.tex      Main LaTeX source
    figures/phase-exposure-schematic.pdf   Illustrative schematic figure
    README.md                          Repository overview
    CITATION.cff                       Citation metadata
    LICENSE                            CC BY 4.0 license notice

## License

This work is released under CC BY 4.0. Reuse is permitted with attribution.