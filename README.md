# SSBI-Project
# In Silico Prediction of Protein–Protein Interactions (CAPRI Targets)

## Overview

This project focuses on the computational prediction and analysis of protein–protein interactions using CAPRI (Critical Assessment of Predicted Interactions) benchmark targets.

The project involves structure-based protein–protein docking, where protein structures are prepared, receptor and ligand chains are identified, and docking simulations are performed to predict possible binding orientations between interacting proteins.

Docking calculations are carried out using **FRODOCK**, with docking potential maps generated through **FRODOCKGRID**. The resulting docking poses are further processed, clustered, and ranked using **FRODOCKCLUSTER** and **FRODOCKVIEW** to identify high-quality protein complex models.

The top-ranked docking solutions are analyzed through structural evaluation, including ligand RMSD (LRMSD) calculations and protein interaction assessment using computational tools such as **BioPython** and **PyMOL**.

## Objectives

- Predict protein–protein interaction models using computational docking approaches.
- Prepare and analyze protein structures from PDB databases.
- Generate and evaluate docking solutions for CAPRI targets.
- Identify reliable protein complex models through ranking and structural analysis.
- Assess docking accuracy using RMSD and interaction analysis.

## Tools and Technologies

- **FRODOCKGRID** – Generation of docking potential maps  
- **FRODOCK** – Protein–protein docking simulation  
- **FRODOCKCLUSTER** – Clustering docking solutions  
- **FRODOCKVIEW** – Visualization and ranking of docking models  
- **BioPython** – Structural data analysis and RMSD calculation  
- **PyMOL** – Molecular visualization and interaction analysis  
- **AWS Linux Environment** – Computational execution platform

## Workflow

1. Obtain protein structures from PDB databases.
2. Prepare receptor and ligand chains for docking.
3. Generate docking grids using FRODOCKGRID.
4. Perform protein–protein docking using FRODOCK.
5. Cluster and rank docking solutions.
6. Select top-ranked protein complex models.
7. Evaluate structural quality using RMSD and interaction analysis.

## Outcome

The project demonstrates the application of computational structural biology methods for predicting protein–protein interactions and evaluating docking models. The analysis provides insights into protein binding mechanisms and the effectiveness of in silico docking approaches.
