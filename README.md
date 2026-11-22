# Swift GRB reference redshifts

This repository contains the verified spectroscopic reference
redshift compilation accompanying:

“A harmonized Swift GRB catalogue for reproducible
machine-learning redshift estimation”

Authors: Istvan I. Racz, Natalia Markus, Istvan Horvath,
and Zsolt Bagoly.

## Contents

- `reference_redshifts.csv`: GRB identifiers, spectroscopic
  reference redshifts.

## Columns

- `grb_id`: GRB identifier.
- `z`: spectroscopic reference redshift.
- `reference`: source of the redshift determination.

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
