# AREPO–MESA Profile Tools

Python tools for processing, visualizing, and converting stellar merger simulation profiles between **AREPO** and **MESA** workflows.

## Overview

This repository contains scripts used to analyse post-impact stellar remnant profiles from hydrodynamical simulations and prepare them for further stellar evolution calculations.

The main goal is to compare and transform radial profiles from AREPO simulations into formats that can be used or compared with MESA stellar models.

## What this repository does

* Reads AREPO remnant profile data
* Processes composition profiles as a function of mass coordinate
* Converts isotope abundances into a MESA-compatible format
* Compares AREPO and MESA profiles
* Plots physical quantities such as composition, entropy, density, temperature, and radius
* Helps prepare relaxation inputs for MESA

## Scientific context

Hydrodynamical simulations can capture complex stellar merger or impact events, while stellar evolution codes such as MESA are useful for following the long-term evolution of the remnant.

This workflow helps bridge the two stages by mapping the output of AREPO simulations into profiles that can be inspected, compared, and used in MESA-based follow-up calculations.

## Technologies used

* Python
* NumPy
* Matplotlib
* Scientific data processing
* Stellar evolution modelling
* Hydrodynamical simulation analysis

## Repository structure

```text
.
├── MESA_files/        # MESA (1D) files for relaxation and evolving the star
├── Input_files/           # input data files from Arepo (3D)
├── figures/        # output figures
├── README.md
└── requirements.txt
```

## Example output

Add an example figure here:

```markdown
![Example profile](figures/example_profile.png)
```

## Getting started

Clone the repository:

```bash
git clone https://github.com/AbinayaSwaruba/Arepo-MESA.git
cd Arepo-MESA
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

Run an example script:

```bash
python scripts/example_plot.py
```

## Example use cases

* Inspecting post-impact remnant composition profiles
* Comparing AREPO and MESA radial profiles
* Preparing MESA relaxation inputs
* Visualizing stellar structure quantities after hydrodynamical simulations

## Author

**Abinaya Swaruba Rajamuthukumar**
Postdoctoral Researcher, Max Planck Institute for Astrophysics
Computational astrophysics | Scientific computing | Stellar evolution


