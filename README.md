# Using SED-ML with SBML Qual
This is 
(1) work in progress
(2) going to be a set of examples showcasing how (extended) SED-ML can be applied to SBML Qual models. 
The idea of a github-based, fully featured showcase is taken from the [CombineArchiveShowcase](https://github.com/SemsProject/CombineArchiveShowCase).  

# Examples contained in this showcase

We use four examples to demonstrate how SED-ML would be used for experiments run on SBML Qual models:

 * Toy model: taken from the SBML Qual Specification [Section 4.1](http://co.mbine.org/specifications/sbml.level-3.version-1.qual.version-1.release-1.pdf)
 * Petri net model: taken from the SBML Qual Specification [Section 4.2](http://co.mbine.org/specifications/sbml.level-3.version-1.qual.version-1.release-1.pdf)
 * Lambda phage model: taken from the [GinSim tutorial](http://compbio.igc.gulbenkian.pt/nmd/sites/compbio.igc.gulbenkian.pt.nmd/files/Practical_GINsim.pdf)
 * MAPK model: taken from the [GinSim repository](http://ginsim.org/node/173)

# Organisation of files
The files in each of the four example folders are organised as follows:
**models:** Files that describe and encode the biological system, using SBML L3 with SBML Qual extension. 
**simulations:** Files that encode the simulation setup, using SED-ML L1V2 plus the proposed extensions necessary for discrete simulations
**figures:** Graphical representations of the models and of the results obtained from the simulation experiments, using png format.

I chose this structure because it is a convenient way for me to organise my COMBINE Archive. However, the structure is not mandatory.
