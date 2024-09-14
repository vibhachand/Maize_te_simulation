# Modelling transposable element dyanmics in maize

## Project Description
This project simulates transposable element (TE) dynamics and changing demography during the domestication of maize. In this simulation, the following parameters were added: TE disabling, epigenetic silencing and unsilencing, replication/propagation, and conversion of autonomous TEs to non-autonomous TEs. The model runs for a total of 5000 generations with a population bottleneck introduced at generation 500. This model uses SLiM, a population genetics software that comes with functions and features useful for building simulations and modeling genomes.

Future features to implement include adding the ability for non-autonomous TEs to transpose while in close proximity to autonomous TEs.

## How to run
Due to the amount of memory required to run this simulation, this simulation is run on Farm, a high performance computing cluster located at the University of California, Davis. To run this simulation, a job is sent to a slurm job manager via a bash script. This project also requires the installation of SliM version 4 or higher.

## Credits
This project was made possible by the Ross-Ibarra Lab at UC Davis. Special thanks to Natasha Dhamrait, Regina Fairbanks, and Dr. Ross-Ibarra for their guidance and resources.
