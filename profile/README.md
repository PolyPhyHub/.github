Polyphy, an interactive visualization and model fitting tool that provides a novel approach for investigating cosmological datasets. 
Through a fast computational simulation method inspired by the behavior of Physarum polycephalum, an unicellular slime mold organism that 
efficiently forages for nutrients, astrophysicists are able to extrapolate from sparse datasets, such as galaxy maps archived in the Sloan 
Digital Sky Survey, and then use these extrapolations to inform analyses of a wide range of other data, such as spectroscopic observations 
captured by the Hubble Space Telescope. Researchers can interactively update the simulation by adjusting model parameters, and then investigate 
the resulting visual output to form hypotheses about the data. We describe details of Polyphy's simulation model and its interaction and visualization 
modalities, and we evaluate Polyphy through three scientific use cases that demonstrate the effectiveness of our approach.

Polyphy has two tightly coupled main components: simulation and visualization.

The simulation component implements the MCPM algorithm to reconstruct an optimal transport network given a set of point data in 3D space. Such data 
can represent the distribution of galaxies or dark matter halos, typically on the scales of 100s of megaparsecs. MCPM uses a swarm of millions of 
particle-like agents to explore the simulation domain.

The visualization component facilitates analysis tasks of the estimated network. Thanks to the interactive nature of Polyphy we can observe 
changes of the estimate in response to changing MCPM parameters. The main concern is whether the reconstruction fits the input data 
(i.e. all the input points are contained in it) as well as the plausibility of the obtained filamentary structures.

- [Our Website ](https://polyphy.hyperspaceweb.net)

- [CROSS ](https://cross.ucsc.edu)

- [OSPO](https://ospo.ucsc.edu)
