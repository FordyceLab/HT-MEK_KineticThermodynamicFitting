# Michaelis-Menten fitting, inhibition fitting, data aggregation, and statistics

This repository contains a suite of Mathematica notebooks (for use with v.11 and above) for determining kinetic and thermodynamic constants from HT-MEK experimental data.

There are 3 types of notebook:

1. assayDataSet_pipeline notebooks contain the code to process the data from individual experiments and perform Michaelis-Menten fits and inhibition fits.
2. "process" notebooks allow processing (or reprocessing) of all experiments of the same type together in "batch mode", and export the per-experimental summary PDFs that are included in the OSF repository.
3. agg* notebooks (aggKinetic, aggInhibition, ...) contain the code necessary to aggregate data from multiple experiments to calculate statistics and final parameter estimates. These notebooks also output the aggregate PDF summaries included in the OSF repository.
