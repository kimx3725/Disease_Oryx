# Disease_Oryx
The repository contains all the annotated code examples of the manuscript. Please drop a mail to kimx3725@umn.edu and report an issue here for any queries and issues.

## Code 
- a.3state_HHM.Rmd: runs 3-state HMMs (unconstrained model, constrained model, semi-supervised constrained model) to estimate 3-state infection states from animal movement data. 
- b.4state_HMM.Rmd: runs 4-state HMMs (unconstrained model, constrained model, semi-supervised constrained model) to estimate 4-state infection states from animal movement data.
- c.5state_HMM.Rmd: runs 5-state HMMs (unconstrained model, constrained model, semi-supervised constrained model) to estimate 5-state infection states from animal movement data.
- d.constrained_4state_HHMM.Rmd: runs constrained 4-state hierarchical HMMs to estimate 4-state infection states from animal movement data.
- e.unconstrained_4state__HHMM.Rmd: runs unconstrained 4-state hierarchical HMMs to estimate 4-state infection states from animal movement data.
- f.4st_SIR_HMM.Rmd: runs a constrained 4-state SIR HMM to estimate 4-state infection states from animal movement data. 
- g.simulation.Rmd: runs a simulation to generate 30 days of hourly movement trajectories for 20 individuals - illustrating the potential of SIR formulations for systems where recovery is common. 
- h.4st_SIR_HMM_simulation.Rmd: runs a constrained 4-state HMM to estimate 4-state infection states from the simulated data. 

## Data
The scimitar-horned oryx was classified as Extinct in the Wild by the IUCN Red List from 2000 to December 2023, when the species was downlisted to Endangered (IUCN SSC ASG, 2023). Due to the species’ extremely threatened status and history of hunting by humans, data supporting this research are sensitive and unavailable publicly. The oryx movement data are owned by the Environment Agency - Abu Dhabi (EAD). They are available to qualified researchers by contacting the Director of Environmental Information Management at EAD (https://www.ead.gov.ae/en) and requesting an EAD Data Usage Agreement to access GPS tracking data of re-introduced oryx in Chad. However, the simulated data and code are available in the GitHub repository. 
