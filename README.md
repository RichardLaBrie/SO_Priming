# Read me
This repository contains all necessary data to reproduce the results and figures in the paper titled "Testing the priming effect in the deep ocean: are microorganisms too starved to consume recalcitrant organic carbon?" submitted to _Applied and Environmental Microbiology_.

# File description
Data.xlsx contains chemical (DOC, DON and DOP) and cell abundance data.

# Data description
ID: Unique ID written as "Experiment""Replicate"_"sampling time". e.g., "Ctrl1_0" is control bottle, replicate 1, sampled at time 0.

Exp: Experimental conditions. Values can be "Control", "Glucose", "Amino acids", "AA-Glu-6-P" or "Glu-6-P", where AA stands for amino acids and Glu-6-P for Glucose-6-phosphate

Time: Sampling time

DOC_uM: Dissolved organic carbon concentration expressed in µmol L-1

DON_uM: Dissolved organic nitrogen concentration expressed in µmol L-1

DOP_uM: Dissolved organic phosphorus concentration expressed in µmol L-1

Abundance_per_ml: Cell abundance expressed in cells mL-1

# Figures
Figure 1 can be produced using ggmap, cowplot, sf, lwgeom and rworldmap libraries in R.

Figures 2 and S2 can be produced with Data.xlsx.

Figures 3, 4 and S3 can be produced with the 16S rRNA amplicon sequencing data available on NCBI Sequence Read Archive using accession number PRJNA1274019.
