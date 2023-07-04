# CymA-simulations
Gromacs input topology and parameter files for simulation of CymA transporter.

## Overview
Gromacs input topology and parameter files for MD simulation of cationic cyclodextrin substrate translocation through native CymA pore at pH 4.5 and pH 8.</br>
The files-native-pH4.5 and file-native-pH8 folders contain two structure files (gro file: em.gro-a MD energy minimized structure and equilibration.gro-an equilibrated structure) of the simulation systems at pH 4.5 and 8, respectively.</br>
The corresponding gromacs topology files are provided in topol.top file and inside the toppar folder: the parameter files for the protein, lipid, ligand, ions and tip3p water are provided. </br>
In the MDP folder we provide four MD parameter or mdp files: step6.0\_minimization.mdp-an energy minimization mdp, step6.6\_equilibration.mdp-an equilibration mdp file, steered\_MD.mdp-a mdp file for running the non-equilibrium pulling of the substrate through the native CymA pore i.e., the steered MD and a sample mdp file for running umbrella sampling simulation: umbrella\_sampling.mdp. In addition to the gro and mdp files, we provide an index file (index.ndx) where several index groups used in the mdp files are defined.</br>
Animation showing the am6αCD translocation through the native CymA pore (anime2.mp4 or anime2.gif) at pH 8 describing the correlation between the substrate translocation and movement of the flexible N terminus segment. The protein (residue 16-324) is shown in a ribbon representation (gray) and  the N terminus (residue 1-15) is shown in a thick tube (red) representation. The ligand is shown in a space filling sphere (green) representation. It is important to note this is not a time-continuous MD simulation trajectory. The animation was prepared using multiple snapshots obtained from steered MD and umbrella sampling simulations of the ligand translocation process. This captures the role of the flexible N terminus segment in substrate translocation through native CymA pore with atomistic resolution.
