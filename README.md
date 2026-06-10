# Project Overview

This project demonstrates a reproducible computational drug discovery workflow for evaluating a candidate small molecule against the human Glucagon-Like Peptide-1 Receptor (GLP1R).

## Candidate Molecule

SMILES:

O=C(O)c1ccc2nc(CN3CCC(c4ccc(F)c(OCC)n4)CC3)n(CC3CCO3)c2c1

## Objective

To investigate whether the candidate molecule exhibits structural similarity to known GLP1R-associated ligands and to establish a computational framework for further receptor-based evaluation.

## Data Sources

* ChEMBL API
* UniProt REST API
* AlphaFold Protein Structure Database

## Workflow

1. Identification of the human GLP-1 receptor target in ChEMBL (CHEMBL1784)
2. Retrieval of published GLP1R bioactivity records
3. Collection of known GLP1R-associated ligands
4. Molecular fingerprint generation using RDKit
5. Tanimoto similarity analysis against known ligands
6. UniProt protein annotation retrieval
7. AlphaFold structure retrieval for future structure-based studies

## Key Findings

* Human GLP1R target identified: CHEMBL1784
* Known activity records retrieved: 1000+
* Known ligands analyzed: 200
* Maximum Tanimoto similarity observed: 0.2162

## Interpretation

The candidate molecule exhibits low structural similarity to the sampled known GLP1R ligands. This suggests that the molecule represents a structurally distinct scaffold rather than an obvious analog of previously reported GLP1R compounds.

A low similarity score does not prove inactivity. Instead, it indicates that additional target-specific computational and experimental validation is required.

## Next Steps

* RDKit descriptor analysis
* Physicochemical property profiling
* Lipinski and oral bioavailability assessment
* ADMET prediction
* GLP1R binding pocket identification
* Molecular docking using AutoDock Vina
* Molecular dynamics simulations
* QSAR modeling using known GLP1R activity data
* Experimental validation through receptor activation assays

## Disclaimer

This project does not claim that the candidate molecule is a GLP-1 receptor agonist. The analysis presented here is intended as an exploratory chemoinformatics workflow and foundation for future computational drug discovery studies.
