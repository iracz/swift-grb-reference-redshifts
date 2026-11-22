# Swift GRB reference redshifts

This repository contains the verified spectroscopic reference
redshift compilation accompanying:

“A harmonized Swift GRB catalogue for reproducible
machine-learning redshift estimation”

Authors: Istvan I. Racz, Natalia Markus, Istvan Horvath,
and Zsolt Bagoly.

## Contents

- `reference_redshifts.csv`: GRB coordinatea, spectroscopic
  reference redshifts.
  
## Sample

This dataset contains the 329 GRBs used for regression training
and cross-validation in the accompanying article. Each event has
a verified spectroscopic reference redshift, an available BAT T90
measurement, and a first XRT observation starting less than
200 seconds after the trigger.

## Columns

- `ra_deg`: BAT right ascension (J2000), in degrees.
- `dec_deg`: BAT declination (J2000), in degrees.
- `z`: spectroscopic reference redshift.

## Scope

This repository provides reference redshifts, not machine-learning
redshift predictions.

The merged and cleaned observational catalogue, model input
matrices, and trained models are not included.

The underlying observational data are available from the NASA
Swift GRB Archive and the UK Swift Science Data Centre.
Data sources, preprocessing, and sample selection are described
in the accompanying article.

## Citation

Publication details will be added when available.
