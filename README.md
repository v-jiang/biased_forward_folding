# biased_forward_folding
Ab initio structure prediction provides a very stringent test of the compatibility between sequence and structure of de novo protein designs. Funnel-shaped energy landscapes where the designed structure is the global energy minima and has a substantial energy gap with respect to alternative conformations is usually considered as a good indicator of the quality of the design. It is, however, a computationally expensive technique and can only be run for a handful of designs. Instead, Biased forward folding simulations allow to quickly identify those designs more likely to achieve near-native conformational sampling in standard ab initio folding simulations. Folding simulations are biased towards the designed conformation by using a smaller subset (three) of fragments at each residue position and with the lowest RMSD (9- and 3-mers) to the designed structure. If near-native sampling cannot be reached under these favoring conditions it is very unlikely that this will occur in standard ab initio trajectories. Additionally, the use of a smaller number of fragments reduces the amount of conformational space to be explored and therefore the number of simulated trajectories and overall computational cost. Thousands of designs can be quickly screened in this way, and dedicate standard ab initio simulations to the characterization of the most promising designs.

Here we provide scripts to setup a biased forward simulation.
