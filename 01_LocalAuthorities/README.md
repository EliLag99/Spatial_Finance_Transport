## Local Authority Analysis
The notebooks in this folder analyse UK Local Authorities and especially the datasets about Greenhouse Gas emissions, Traffic Counts and Geography.

## Goal
The aim is to compile information about Local Authorities and Traffic Count Sites to determine which sites are most useful to train the later model on

## Walkthrough

1. AllocateCountSitesToLA.ipynb:
   - Gathers data from Greenhouse Gas Emissions Dataset, Road Lengths dataset and UK Traffic Countsites
   - Filters out active countsites and allocates them to a local authority in the  UK using a shapefile of the UK Geography
   - 