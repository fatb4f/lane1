# lane1

Python-first package intelligence workbench for a given PyPI package.

## Focus

This repo tracks a constrained learning/build lane centered on:

- modern Python
- marimo
- Ruff and Ty
- PyO3/maturin
- developer-facing analytical tooling

The artifact is a **PyPI Package Intelligence Workbench**.

## Project sentence

Build a Python-first package intelligence workbench for a given PyPI package using PyPI metadata, Ruff, Ty, marimo, and a required PyO3/maturin Rust kernel for diagnostics normalization and aggregation.

## Roadmap

- [curriculum/overview.md](curriculum/overview.md)
- [curriculum/v1.md](curriculum/v1.md)
- [curriculum/v2.md](curriculum/v2.md)

## v1

v1 ships a usable analysis workflow for a single PyPI package with:

- package metadata acquisition
- Ruff diagnostics
- Ty diagnostics
- Rust-backed normalization and aggregation
- marimo workbench views

## v2

v2 extends the workbench with Rust-backed AST/fact extraction for structural package intelligence, with `sem-core` as the primary candidate substrate.

## Constraints

- Python is the control plane.
- Rust is mandatory in v1, but tightly scoped.
- No AST work in v1.
- No tree-sitter or `sem` integration in v1.
- The workbench is the artifact; framework exploration is not the artifact.

Python lane focused on package intelligence and analytical tooling.

## Focus

- Python-first development
- marimo workbench and app patterns
- PyO3/maturin native boundary
- developer-facing code/package intelligence

## Current artifact

PyPI Package Intelligence Workbench.

## Scope

Early work should stay narrow: package metadata, diagnostics, normalization, aggregation, and a usable analysis surface.
