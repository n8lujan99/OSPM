# OSPM

## Orbit Superposition Modeling — Version 3

OSPM is a computational framework for stellar-dynamical modeling using
orbit-superposition methods.

The code combines a Python control and data-processing layer with Julia-based
numerical dynamics. Galaxy-specific observations and model assumptions are
provided through configuration files. The main dynamical machinery remains
shared between systems.

OSPM v3 is the first public release of the actively developed OSPM codebase.

## Current galaxy configurations

The repository currently contains configurations and model products for:

- Draco
- Segue 1
- Carina

## Repository structure

```text
OSPM/
├── Data/
│   └── Galaxy_Profiles/
│       ├── Carina/
│       ├── Draco/
│       └── Segue1/
│
├── OSPM/
│   ├── AI/
│   ├── Controllers/
│   ├── Data_Prep/
│   ├── Fortran/
│   ├── Observables/
│   ├── Physics/
│   └── Xar/
│
├── Plotting/
├── docs/
├── utils/
├── Project.toml
├── Manifest.toml
├── VERSION
└── LICENSE

Now citation metadata. This gives GitHub a proper **Cite this repository** entry:

```bash
cat > CITATION.cff <<'EOF'
cff-version: 1.2.0
message: "If you use OSPM in scientific work, please cite this software and the associated scientific publications."
title: "OSPM: Orbit Superposition Modeling"
version: 3.0.0
date-released: 2026-09-27
authors:
  - family-names: Lujan
    given-names: Nathaniel R.
license: MIT
repository-code: "https://github.com/n8lujan99/OSPM"
