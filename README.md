# This repository contains important topology and configuration files used for PM6:Y6 and P3HT:O-IDTBR interfaces.


The data has been taken from the following papers. Please cite the references if you are using this data:  
(1) Agarwala, P.; Gomez, E. D.; Milner, S. T. Crystalline and Amorphous Interface Simulations of Donor–Acceptor Blends. J. Chem. Theory Comput. 2024, 20 (15), 6848–6857. https://doi.org/10.1021/acs.jctc.4c00667.
(2) Mahajan, C. L.; Gomez, E. D.; Milner, S. T. Resolving the Atomistic Morphology of Domains and Interfaces in PM6:Y6 with Molecular Dynamics. Macromolecules 2025, 58 (5), 2765–2778. https://doi.org/10.1021/acs.macromol.4c02588.


christine.ff contains molecule .itp files needed to run simulations in GROMACS.  
This is needed to run any project.

Other project folders will contain a .top file, .mdp file, and sample .gro files before and after a production run.  
The project folders are:

P3HTIDTBRinterface-contains interface input files for O-IDTBR:P3HT interfaces.  
Configuration files are after equilibration at melt temperature [1] and after cooling to room temperature [2].     


PM6Y6interface-contains interface data for PM6:Y6 interfaces.
Configuration files are a mixed and demixed initial starting configuration,
after equilibration at melt temperature, and after cooling to room temperature (anneal) [2].  

PM6anneal-contains pure phase data for decamer PM6.
Configuration files are the initial configuration (resize) and after cooling from melt to room temperature (anneal). [2] 


Y6anneal-contains pure phase data for Y6.  
Configuration files are the initial configuration (resize) and after cooling from melt to room temperature (anneal). [2]


Y6crystal-contains pure phase data for Y6 crystals.  
Configuration files are unwrapped unit cells (JACS and NATCOMM unit cells),
initial configuration (JACS and NATCOMM slabs),
and after equilibration at room temperature (equilibrate). [2]


