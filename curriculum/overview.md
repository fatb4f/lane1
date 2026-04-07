# Overview

## Artifact

**PyPI Package Intelligence Workbench**

Given a PyPI package, generate a developer-facing intelligence report and interactive marimo workbench using:

- PyPI metadata
- Ruff diagnostics
- Ty diagnostics
- a required Rust extension via PyO3/maturin

## Learning shape

### Core lane

- Python first
- marimo as the analysis and demo surface
- Ruff and Ty as modern Python intelligence inputs
- PyO3/maturin as a required native boundary

### v1 goal

Ship a package-intelligence workbench for one package at a time, with Rust responsible for diagnostics normalization and aggregation.

### v2 goal

Add Rust-backed AST/fact extraction for structural package intelligence, keeping Python as the orchestration and presentation layer.

## Guardrails

- one artifact at a time
- no runtime/tooling rabbit holes
- Rust is mandatory, but only in a narrow box
- v2 is blocked until v1 ships
