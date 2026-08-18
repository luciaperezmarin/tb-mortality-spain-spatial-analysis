# tb-mortality-bym2-inla
R/INLA code for Bayesian spatial modelling (BYM2) of tuberculosis mortality


# BYM2 spatial model for tuberculosis mortality: analysis code

## Description

The repository contains the code used to estimate municipality-level tuberculosis mortality risk using Bayesian spatial models (BYM2) implemented with R-INLA.

Pérez-Marín L, Alcalde-Cabero E, García-García D, Rojas-Benedicto A, Roy Á, Herrador Z, Gómez-Barroso D.

"Mapping tuberculosis mortality risk in Spain from 2000 to 2023".

## Repository contents

- `R_BYM2_INLA_code.R`: R/INLA code used to estimate municipality-level smoothed standardized mortality ratios (sSMRs) and exceedance probabilities using the BYM2 model.

- `adjacency_graph.txt`: adjacency graph used in the spatial analyses and required for the implementation of the BYM2 model in INLA.

## Data availability

The mortality microdata used in this study are owned by the Spanish National Statistics Institute (Instituto Nacional de Estadística, INE) and are subject to legal and confidentiality restrictions. Therefore, the original data cannot be publicly shared.

Researchers who meet the criteria for access to confidential data may request access directly from the INE:

https://www.ine.es/infoine/?L=1

## Software

The spatial analyses were performed using:

- R (version 4.3.2)
- R-INLA (Integrated Nested Laplace Approximations)
- BYM2 Bayesian spatial model

The code included in this repository reproduces the municipality-level spatial modelling strategy used to estimate smoothed standardized mortality ratios (sSMRs) and exceedance probabilities.

## Contact

Lucía Pérez-Marín. lucia.perez@externos.isciii.es
