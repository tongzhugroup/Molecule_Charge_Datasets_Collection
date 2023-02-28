you can download the file from 
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3905361.svg)](https://doi.org/10.5281/zenodo.3905361)

QM7-X conclusion:
- 40 physicochemical properties
- about 4.2 M equilibrium and non-equilibrium structures 
- small organic molecules with up to seven non-hydrogen (C, N, O, S, Cl) atoms.  
- computed at the tightly converged quantum-mechanical PBE0+MBD level of theory.
- QM7-X contains global (molecular) and local (atom-in-a-molecule) properties in each structure
	- 'atNUM': Atomic numbers (N)
	- 'atXYZ': Atoms coordinates [Ang] (Nx3)
	- 'sRMSD': RMSD to optimized structure [Ang] (1)
	- 'sMIT': Momente of inertia tensor [amu.Ang^2] (9)
	
	- 'ePBE0+MBD': Total PBE0+MBD energy [eV] (1)
	- 'eDFTB+MBD': Total DFTB+MBD energy [eV] (1)
	- 'eAT': PBE0 atomization energy [eV] (1)
	- 'ePBE0': PBE0 energy [eV] (1)
	- 'eMBD': MBD energy [eV] (1)
	- 'eTS': TS dispersion energy [eV] (1)
	- 'eNN': Nuclear-nuclear repulsion energy [eV] (1)
	- 'eKIN': Kinetic energy [eV] (1)
	- 'eNE': Nuclear-electron attracttion [eV] (1)
	- 'eEE': Classical coulomb energy (el-el) [eV] (1)
	- 'eXC': Exchange-correlation energy [eV] (1)
	- 'eX': Exchange energy [eV] (1)
	- 'eC': Correlation energy [eV] (1)
	- 'eXX': Exact exchange energy [eV] (1)
	- 'eKSE': Sum of Kohn-Sham eigenvalues [eV] (1)
	- 'KSE': Kohn-Sham eigenvalues [eV] (depends on the molecule)
	- 'eH': HOMO energy [eV] (1)
	- 'eL': LUMO energy [eV] (1)
	- 'HLgap': HOMO-LUMO gap [eV] (1)
	- 'DIP': Total dipole moment [e.Ang] (1)
	- 'vDIP': Dipole moment components [e.Ang] (3)
	- 'vTQ': Total quadrupole moment components [e.Ang^2] (3)
	- 'vIQ': Ionic quadrupole moment components [e.Ang^2] (3)
	- 'vEQ': Electronic quadrupole moment components [eAng^2] (3)
	- 'mC6': Molecular C6 coefficient [hartree.bohr^6] (computed using SCS) (1)
	- 'mPOL': Molecular polarizability [bohr^3] (computed using SCS) (1)
	- 'mTPOL': Molecular polarizability tensor [bohr^3] (9)
	
	- 'totFOR': Total PBE0+MBD atomic forces (unitary forces cleaned) [eV/Ang] (Nx3)
	- 'vdwFOR': MBD atomic forces [eV/Ang] (Nx3)
	- 'pbe0FOR': PBE0 atomic forces [eV/Ang] (Nx3)
	- 'hVOL': Hirshfeld volumes [bohr^3] (N)
	- 'hRAT': Hirshfeld ratios (N)
	- 'hCHG': Hirshfeld charges [e] (N)
	- 'hDIP': Hirshfeld dipole moments [e.bohr] (N)
	- 'hVDIP': Components of Hirshfeld dipole moments [e.bohr] (Nx3)
	- 'atC6': Atomic C6 coefficients [hartree.bohr^6] (N)
	- 'atPOL': Atomic polarizabilities [bohr^3] (N)
	- 'vdwR': van der Waals radii [bohr] (N)
