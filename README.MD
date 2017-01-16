#GPU Based Fluid Structure Interaction using Immersed Boundary Methods
##Author: Christopher Minar
##Advisor: Kyle Niemeyer
###Abstract:  
Engineering applications often require fast, accurate solutions of fluid flow around freely moving bodies. 
The massive parallelism enabled by graphics processing unit (GPU) architecture enables high performance, offering a promising alternative to traditional solver acceleration via multicore central processing units (CPU). 
However, fully harnessing GPU parallelism requires specialized algorithms and computing strategies. 
This work modifies direct-forcing immersed boundary methods to model fluid-structure interaction and investigates this behavior on GPUs. 
I performed solver verification using lid-driven cavity flow, impulsively started flow over a cylinder, flow over a forced oscillating cylinder and vortex-induced vibration.
  
###Table of contents:  
1. Introlduction  
2. Numerical Methods  
3. Implementization and Discretization
4. Verification and Validation  
5. Solver Characterization  
6. Summary  

###Acknowledgements:  
We gratefully acknowledge the support of NVIDIA Corporation with the donation of the Tesla K20 GPU used for this research.
We also thank the Barba Group for developing, maintaining, and distributing their cuIBM code. 
Thank you to my committee, everyone in the Niemeyer research group, and the NNMREC lab.
