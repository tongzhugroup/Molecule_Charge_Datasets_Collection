# Molecule Charge Datasets Collection 
This repository contains the datasets used in the development of nerual network potential in charge prediction and charge transfer.
## Carbon Chain
The data was generated from 5000 MD steps at a temperature of 300K with a timestep of 0.5fs of C10H2 and C10H3 respectively. Trajectory obtained from local geometry relaxations were added as well. (10019 structures in total) 
## [small organic molecule](https://pubs.acs.org/doi/10.1021/acs.jctc.1c00821)
 - rotamer data:  sets of rotamers developed in this work, focusing on ionic systems 
 - [hutchison conformers](https://github.com/ghutchis/conformer-benchmark):  A subset of the data reported in Folmsbee & Hutchison, IJQC 121 (2020)
 - ionic conformers:  conformer test set constructed from ionic molecules from ZINC
 - [tautobase](https://github.com/WahlOya/Tautobase):  Tautomer pairs extracted from the tautobase Wahl & Sander J. Chem. Inf. Model 60 (2020)

## [QM7-X](https://zenodo.org/record/4288677)
The comprehensive dataset contains 42 physicochemical properties for ≈4.2 million equilibrium and non-equilibrium structures of small organic molecules with up to seven non-hydrogen (C, N, O, S, Cl) atoms.

## [Dataset for training and testing the SCFNN model](https://zenodo.org/record/5760191#.ZAshuhVBzBU)  
train_test_data.tar.gz contains the DFT calculation results of water cubic box under various strength of external electric field. This dataset is used to train and test the SCFNN model. HirshfeldMullikenCharges.tar.gz contains the DFT calculation results of Hirshfeld and Mulliken charges for the same water box. This dataset is used to train the 4G-HDNN model.
