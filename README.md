# This repository contains important topology and configuration files used for PM6:Y6 and P3HT:O-IDTBR interfaces.


The data has been taken from the following papers. Please cite the references if you are using this data:   
[1] Agarwala, P.; Gomez, E. D.; Milner, S. T. Crystalline and Amorphous Interface Simulations of Donor–Acceptor Blends. J. Chem. Theory Comput. 2024, 20 (15), 6848–6857. https://doi.org/10.1021/acs.jctc.4c00667.  
[2] Mahajan, C. L.; Gomez, E. D.; Milner, S. T. Resolving the Atomistic Morphology of Domains and Interfaces in PM6:Y6 with Molecular Dynamics. Macromolecules 2025, 58 (5), 2765–2778. https://doi.org/10.1021/acs.macromol.4c02588.  
[3] Agarwala, P.; Gomez, E. D.; Milner, S. T. Fast, Faithful Simulations of Donor–Acceptor Interface Morphology. J. Chem. Theory Comput. 2022, 18 (11), 6932–6939. https://doi.org/10.1021/acs.jctc.2c00470.
  

christine.ff contains molecule input topology and potentials (.itp) needed to run simulations in GROMACS. 
Note: this is an archived copy used in the cited work. Future modifications (if any) to potentials or topology files would be found in the christine.ff repository (https://github.com/cmlaport/christine.ff)

Project folders will contain a .top file, .mdp file, and sample .gro files before and after a production run.  
The project folders are:

P3HTIDTBRinterface-contains interface files for O-IDTBR:P3HT interfaces.  
Configuration files are after equilibration at melt temperature [1] and after cooling to room temperature [2].     


PM6Y6interface-contains interface files for PM6:Y6 interfaces.
Configuration files are a mixed and demixed initial starting configuration,
after equilibration at melt temperature, and after cooling to room temperature (anneal) [2].  


PM6anneal-contains pure phase files for decamer PM6.
Configuration files are the initial configuration (resize) and after cooling from melt to room temperature. [2] 


Y6anneal-contains pure phase files for Y6.  
Configuration files are the initial configuration (resize) and after cooling from melt to room temperature. [2]


Y6crystal-contains pure phase files for Y6 crystals.  
Configuration files are unwrapped unit cells (JACS and NATCOMM unit cells),
initial configuration (JACS and NATCOMM slabs),
and after equilibration at room temperature (equilibrated). [2]
Crystal data extracted from: Nat. Commun. 2020, 11 (1), 3943. https://doi.org/10.1038/s41467-020-17867-1.  
J. Am. Chem. Soc. 2020, 142 (34), 14532–14547. https://doi.org/10.1021/jacs.0c05560.  
  

P3HTmelt-contains pure phase files for 24-mer P3HT.
Configuration files extracted from an initial configuration from [2] (resize) and after simulation at 600K. [1]


IDTBRanneal-contains pure phase files for O-IDTBR.
Configuration files extracted from an initial configuration from [2] (resize) and after cooling from melt to room temperature (anneal).


IDTBRcrystal-ontains pure phase files for O-IDTBR crystals. 
Configuration files are an initial configuration (excel_format),
and after equilibration at room temperature (equilibrated). [3]
Crystal data extracted from: J. Org. Chem. 2020, 85, 1, 52–61. https://doi.org/10.1021/acs.joc.9b01654
