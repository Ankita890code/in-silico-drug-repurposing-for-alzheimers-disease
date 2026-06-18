# in-silico-drug-repurposing-for-alzheimers-disease
Multi-stage computational drug discovery project involving virtual screening, molecular docking, ADMET prediction, and molecular dynamics simulation to identify potential FDA-approved BACE1 inhibitors for Alzheimer's disease.
# Design and Computational Evaluation of BACE1 Inhibitors: A Multi-Stage Drug Discovery Approach Against Alzheimer's Disease

# Overview:

This repository contains my M.Sc. Bioinformatics dissertation project focused on the identification of potential BACE1 inhibitors for Alzheimer's disease using an integrated computational drug discovery workflow.

The study combines virtual screening, molecular docking, ADMET prediction, molecular dynamics simulation, and protein–ligand interaction analysis to identify promising FDA-approved drug candidates for repurposing against Beta-Secretase 1 (BACE1), a key therapeutic target involved in amyloid-beta plaque formation.

# Research Objective:

To identify potential BACE1 inhibitors capable of crossing the blood-brain barrier and exhibiting favorable pharmacokinetic properties using computational drug discovery approaches.

# Biological Background:

Alzheimer's disease is a progressive neurodegenerative disorder characterized by memory loss, cognitive decline, and accumulation of amyloid-beta plaques in the brain.

Beta-Secretase 1 (BACE1) is a critical enzyme involved in amyloid-beta production. Inhibition of BACE1 has emerged as a promising therapeutic strategy for reducing amyloid plaque formation and slowing disease progression.

# Methodology:

# 1. Protein Preparation:

* Protein Data Bank (PDB) structure selected: **4D8C**
* Protein preparation performed using Schrödinger Maestro
* Optimization of hydrogen bonding network
* Removal of unnecessary water molecules
* Energy minimization using OPLS force field

# 2. Virtual Screening:

* FDA-approved drug library (~3600 compounds)
* Ligand preparation using LigPrep
* Glide docking workflow:

  * HTVS
  * Standard Precision (SP)
  * Extra Precision (XP)

# 3. Molecular Docking:

* Identification of top-ranked compounds
* Binding affinity analysis
* Protein-ligand interaction analysis
* Comparison with reference ligand NVP-BXD552

# 4. ADMET Prediction:

ADMET profiling performed using SwissADME:

* Gastrointestinal absorption
* Blood-brain barrier permeability
* Drug-likeness filters
* Cytochrome P450 inhibition
* PAINS and Brenk alerts

# 5. Molecular Dynamics Simulation:

* Desmond Molecular Dynamics
* 50 ns simulation
* OPLS4 force field
* TIP3P water model
* NPT ensemble conditions

# 6. Post-Simulation Analysis:

* RMSD analysis
* RMSF analysis
* Protein-ligand interaction profiling
* Stability assessment
* Binding behavior evaluation

# Key Results:

* Screened approximately 3600 FDA-approved compounds.
* Identified DB08669 and DB07377 as promising BACE1 inhibitors.
* Demonstrated favorable docking interactions with key catalytic residues.
* ADMET analysis indicated acceptable pharmacokinetic properties and BBB permeability.
* Molecular dynamics simulations confirmed stable protein-ligand interactions.
* RMSD and RMSF analyses supported structural stability throughout the simulation period.

# Skills Demonstrated:

* Structure-Based Drug Discovery
* Virtual Screening
* Molecular Docking
* ADMET Prediction
* Molecular Dynamics Simulation
* Structural Bioinformatics
* Drug Repurposing
* Protein-Ligand Interaction Analysis
* Computational Pharmacology
* Scientific Data Analysis

# Software and Tools:

* Schrödinger Maestro
* Glide
* LigPrep
* Desmond
* SwissADME
* PyMOL
* DrugBank
* Protein Data Bank (PDB)

# Repository Structure:

```text
├── README.md
├── LICENSE
├── Dissertation/
│   └── Dissertation_Report.pdf
├── Presentation/
│   └── Dissertation_Presentation.pptx
├── Figures/
│   ├── Workflow.png
│   ├── Binding_Pocket.png
│   ├── Docking_Results.png
│   ├── DB08669_Binding_Pose.png
│   ├── DB07377_Binding_Pose.png
│   ├── Protein_Ligand_Interactions.png
│   ├── RMSD_Analysis.png
│   ├── RMSF_Analysis.png
│   └── ADMET_Results.png
├── Results/
│   ├── Docking_Results.xlsx
│   ├── ADMET_Results.xlsx
│   └── MD_Analysis.xlsx
└── References/
```


# Academic Context
This work was completed as part of the M.Sc. Bioinformatics dissertation at the Central University of South Bihar under the supervision of Dr. Durg Vijay Singh.

# Author
**Ankita Mondal**

M.Sc. Bioinformatics

