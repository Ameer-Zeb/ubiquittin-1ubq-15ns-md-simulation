# 15 ns Molecular Dynamics Simulation of Ubiquitin (1UBQ)

## Project Overview

This project presents a 15 ns molecular dynamics (MD) simulation of the ubiquitin protein (PDB ID: 1UBQ) using GROMACS.

The objective was to investigate the structural stability and dynamic behavior of ubiquitin during the simulation using trajectory-based analyses.

## Objectives

- Perform a complete molecular dynamics simulation of ubiquitin.
- Evaluate structural stability throughout the 15 ns simulation.
- Analyze protein flexibility and compactness.
- Examine solvent exposure and hydrogen-bond behavior.
- Develop a reproducible GROMACS MD workflow.

## System Information

| Parameter | Details |
||  |
| Protein | Ubiquitin |
| PDB ID | 1UBQ |
| Simulation length | 15 ns |
| Simulation software | GROMACS |
| Force field | ["oplsaa.ff/forcefield.itp"] |
| Water model | [TIP3P |
| Temperature | [300] K |
| Ensemble | NVT → NPT → Production MD |
| Production time step | [15000] fs |

## Simulation Workflow

The molecular dynamics workflow consisted of:

1. Protein structure preparation
2. Topology generation
3. Solvation
4. Addition of ions
5. Energy minimization
6. NVT equilibration
7. NPT equilibration
8. 15 ns production molecular dynamics
9. Trajectory analysis

## Simulation Pipeline

  text
1UBQ structure
      ↓
Topology generation
      ↓
Solvation
      ↓
Ion addition
      ↓
Energy minimization
      ↓
NVT equilibration
      ↓
NPT equilibration
      ↓
15 ns Production MD
      ↓
Trajectory analysis
      ↓
RMSD / RMSF / Radius of Gyration / SASA / Hydrogen bonds