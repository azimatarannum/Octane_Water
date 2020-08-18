# Octane in a Water Box
Octane in a water box under CHARMM36 forcefield.

The following steps are to be completed:

  - [ ] Create a water box
  - [ ] Insert octane molecules into the box
  - [ ] Do energy minimization, NVT and NPT equilibration
  - [ ] Run the full simulation for ~10ns
  
  The files required for this:
  
  - GROMACS, which can be downloaded from here: http://manual.gromacs.org/documentation/2020.1/download.html
  - CHARMM36.ff forcefield folder, which can be found here: http://www.gromacs.org/@api/deki/files/184/=charmm36.ff_4.5.7_ref.tgz
  - PDB file of octane: https://ww2.chemistry.gatech.edu/~lw26/structure/small_molecules/octane.pdb (it has to be changed to match the forcefield)
  - minim.mdp file, nvt.mdp and npt.mdp files: these are all uploaded in the mdp file section
    
It is also recommended to do this on a supercomputer, or just run shorter mdrun. 

