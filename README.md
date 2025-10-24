# ARGevol 2025 - Day 3 Workshop

This repository contains simulations, tree files, and notebooks used for the Day 3 Workshop at ARGevol 2025. This workshop 


## Create conda environment

`conda env create -f environment.yml`


## Outline of workshop

- Spatial simulations
    - Discrete space simulations with `msprime`
    - Continuous space simulations with `SLiM`
        - Recapitation (if not covered in other workshops)
    - Extracting spatial information from simulated tree sequences
    - Visualizing lineage movements
    - Calculating dispersal rates from location data
- Tree- versus graph-based approaches for applied ARGs
    - Simplest walkthrough example for a two tree ARG
    - Categorization of current spatial methods
- Comparing current spatial methods
    - ARGscape (Talbot and Bradburd 2025)
    - Individually (not planning to do all but these are options)
        - Wohns et al. 2021
        - Osmond and Coop 2024
        - Grundler et al. 2025
        - Deraje et al. 2025
        - `terracotta` from keynote presentation earlier in the day
    - How to handle uncertainty arising from the movement model
- ARG inference in a spatial context
    - How space affects common ARG structures
    - Importance sampling