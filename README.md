# QuClab

**QuClab** is a slightly designed short name for **Quantum Circuit Laboratory**.

> **Beta status**
>
> QuClab is currently in the `0.x.x` beta series.
> All `0.x.x` releases are considered **beta builds**.

## What is QuClab?

QuClab is a desktop application for visually building, organizing, simulating, and inspecting quantum circuits.

The project is focused on providing a practical laboratory-style workflow for quantum circuit experiments, including:

- visual circuit construction
- structured property editing
- parameter references and reusable parameter storage
- complete / debug execution workflows
- result inspection and graphical result dialogs
- circuit navigation for larger designs
- generated circuit templates for common structures
- project save/load support
- user preferences, themes, and translation infrastructure

## Current Status

This repository is currently maintained as a **executable-releases-only repository**.

At the current stage:

- QuClab is **not open source**
- internal structure and implementation details may still change
- developer-facing documentation is being stabilized
- repository contents are intended for controlled beta development rather than public contribution

## Versioning Policy

QuClab uses the following versioning convention:

- `0.x.x` = beta releases
- `1.x.x` and later = stable/public release line

In the current beta phase, the application is still under active refinement in areas such as workflow polish, settings, persistence, translation, and documentation quality.

## Current Focus of the Beta Line

The current beta series focuses on:

- making circuit editing practical and stable
- improving execution workflow clarity
- refining result query and analysis tools
- organizing larger circuits through navigation and folded views
- stabilizing project persistence and user preferences
- improving maintainability before public release

## Dependencies

QuClab uses external components as part of its current development environment, including:

- [Qcdtr1](https://github.com/modulelife/Qcdtr1) as the backend integration library
- [Qulacs](https://github.com/qulacs/qulacs) as an important simulation dependency in the current backend toolchain

## License Status

### QuClab
This `0.x.x` beta line of QuClab is currently **proprietary** and **not open source**.

### Qcdtr1
The backend library **Qcdtr1** is maintained separately and uses its own license.

## Notes

This README is intentionally written in a **executable-releases-only repository** for the current beta stage.

It is meant to describe the product at a high level without exposing internal architectural details that are still being stabilized for future public release.

---
QuClab — Quantum Circuit Laboratory
