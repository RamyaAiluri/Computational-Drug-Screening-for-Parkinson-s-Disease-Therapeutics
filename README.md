# Computational-Drug-Screening-for-Parkinson-s-Disease-Therapeutics
## Identification and Characterization of Small Molecules for Inhibition of DJ-1 Aggregates for Prevention of Parkinson’s Disease by Allosteric Inhibition
## Overview
**Parkinson’s disease (PD):** Progressive neurodegenerative disorder marked by loss of dopaminergic neurons and protein aggregates (alpha-synuclein).
**DJ-1:** Potential therapeutic target due to its role in oxidative stress response and protein regulation.
**Study Goal:** Inhibit DJ-1 protein aggregates using small molecules identified through computational molecular docking and dynamics.
**Methodology:**
Screened small molecules (e.g., Foscarbidopa, Tavapadone) using AutoDock Vina and PyRx.
Visualized interactions with Biovia Discovery Studio.
**Findings:** Small molecules can bind DJ-1 and modulate its activity, offering potential therapeutic interventions for PD.

## Introduction
**Parkinson’s Disease (PD):** Degeneration of dopaminergic neurons, decrease in dopamine, and oxidative stress as contributing factors.
**DJ-1 protein:** Linked to familial and sporadic forms of PD, oxidative stress response, and protein regulation.
**Protein Aggregation:** Harmful soluble oligomers (protofibrils) disrupt cellular balance and cause neuron death.
**Current Treatments:** Focus on symptom management, with limitations in long-term efficacy.

## Materials and Methods
### 1. Data Acquisition
**Target Protein:** DJ-1 protein structure (PDB ID: 7C62) from Protein Data Bank.
**Small Molecules:** Identified from DrugBank database (e.g., Foscarbidopa, Inosine, Levodopa, Tavapadone).
### 2. Data Preparation
**Protein Preparation:**
Water molecules and heteroatoms removed using AutoDock Tools and PyMOL.
Structures converted to pdbqt format for docking.
**Molecular Docking:**
PyRx (AutoDock Vina) used to predict binding affinities.
Docking grid box configured for the DJ-1 binding pocket.
### 3. Docking Visualization
**Visualization Tool:** Biovia Discovery Studio used to analyze and visualize protein-ligand interactions.

## Results
### 1. Binding Affinity of Ligands
Top Ligands (Based on Affinity):
Tavapadone: -7.7 kcal/mol
Sifanamide: -6.3 kcal/mol
Levodopa: -5.4 kcal/mol
### 2. Molecular Interactions
Key Interactions: Hydrogen bonds, hydrophobic interactions, and pi-alkyl interactions with residues in DJ-1 protein.

## Conclusion
Tavapadone demonstrated the highest binding affinity, indicating its potential as a DJ-1 inhibitor.
Computational docking provided insights into protein-ligand interactions.

## Future Directions
Experimental validation (in-vitro/in-vivo studies).
Structure-activity relationship studies to optimize compounds.
Potential translation to other neurodegenerative disorders.


