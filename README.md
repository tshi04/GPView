# GPView 
The GPView program is a C++ package for wave function analysis and visualization. It was developed and maintained by Tian Shi and Ping Wang.

Please cite the following paper if you are using GPView:
```
@article{shi2016gpview,
  title={GPView: a program for wave function analysis and visualization},
  author={Shi, Tian and Wang, Ping},
  journal={Journal of Molecular Graphics and Modelling},
  volume={70},
  pages={305--314},
  year={2016},
  publisher={Elsevier}
}
```

## Usuage

### Graphics

- Display molecular structures. GPView can read data from G09 gjf (or com), G09 fchk, G09 wfx, G09 log files, XYZ file, PDB file, and show molecular structures. It can also read molecular structures from input files of GAMESS, MOPAC, Q-chem, Mopro and NWchem.

- Animate single MD trajectories. Structures are from XYZ files.

- Display electronic structures. GPView can read data from CUB (or CUBE) file and display iso-surface for molecular orbitals and electron densities. One can also view a couple of cubes together, which is very convenient for visualizing HOMO-LUMO, Hole-Particle simultaneously.

- Contour Plot and Matrix Color Map, e.g. plot transition density matrices

- Plot Density of States and Spectrum (Oscillator Strength).

- Interface with outputs of GPV-ESMD program, which is a package for Non-Adiabatic Excited-State MD, and simulate the results of single MD trajectories, including molecular structures, potential energy surfaces, non-adibatic coupling terms, hopping probability and bond lengths. It can plot the average state populations as well.

