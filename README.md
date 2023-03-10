# Molecule Charge Datasets Collection
This repository contains the datasets used in the development of nerual network potential in charge prediction and charge transfer.
## Carbon Chain(Hirshfeld charge)
The data was generated from 5000 MD steps at a temperature of 300K with a timestep of 0.5fs of C10H2 and C10H3 respectively. Trajectory obtained from local geometry relaxations were added as well. (10019 structures in total) 
## [small organic molecule](https://pubs.acs.org/doi/10.1021/acs.jctc.1c00821)(Hirshfeld charge)
 - rotamer data:  sets of rotamers developed in this work, focusing on ionic systems 
 - [hutchison conformers](https://github.com/ghutchis/conformer-benchmark):  A subset of the data reported in Folmsbee & Hutchison, IJQC 121 (2020)
 - ionic conformers:  conformer test set constructed from ionic molecules from ZINC
 - [tautobase](https://github.com/WahlOya/Tautobase):  Tautomer pairs extracted from the tautobase Wahl & Sander J. Chem. Inf. Model 60 (2020)

## [QM7-X](https://zenodo.org/record/4288677)(Hirshfeld charge)
The comprehensive dataset contains 42 physicochemical properties for ≈4.2 million equilibrium and non-equilibrium structures of small organic molecules with up to seven non-hydrogen (C, N, O, S, Cl) atoms.

## [Dataset for training and testing the SCFNN model](https://zenodo.org/record/5760191#.ZAshuhVBzBU)(Hirshfeld charge,Mulliken charge)  
train_test_data.tar.gz contains the DFT calculation results of water cubic box under various strength of external electric field. This dataset is used to train and test the SCFNN model. HirshfeldMullikenCharges.tar.gz contains the DFT calculation results of Hirshfeld and Mulliken charges for the same water box. This dataset is used to train the 4G-HDNN model.

## [WS22](https://zenodo.org/record/7032334#.ZAXDdD1BzBU)(Mulliken charge)    
The WS22 database provides a collection of molecular datasets that explores a broad configurational space of flexible organic molecules with varying sizes and complexity. It includes several chemical properties calculated with a quantum chemical (QM) method. Complementary to the structured datasets, this repository also provides the molecular geometries for the equilibrium structures together with the corresponding output of the QM frequency calculations. 

## [QMdrugs](https://doi.org/10.3929/ethz-b-000482129)(Mulliken charge)  
The QMdrugs data collection comprises quantum mechanical properties of more than 665k biologically and pharmacologically relevant molecules extracted from the ChEMBL27 database (http://www.ebi.ac.uk/chembl), totaling ~2M conformers. QMdrugs contains (i) their optimized geometries and thermodynamic properties (including vibrational frequencies) obtained via the semi-empirical method GFN2-xTB, (ii) atomic and molecular properties (e.g., partial charges, bond orders, energies, and dipoles) on both the GFN2-xTB and on the DFT (ωB97X-D/def2-SVP) levels of theory, and (iii) quantum mechanical wavefunction as local basises of atomic orbitals (DFT density and orbital matrices), totaling over 7 terabytes of uncompressed data. This dataset is intended to facilitate the development of machine learning models that learn from molecular data on different levels of theory while also providing insight into the corresponding relationships between molecular structure and biological activity.
