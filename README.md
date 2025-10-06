
# REWEIGHTING AND ANALYSES REPO FOR PaaA2 CG MODEL SYSTEM

Code for all analyses and Maximum Entropy Reweighting of CG PaaA2 ensemble



## Authors


Kaushik Borthakur, Thomas Sisk
## Methods and programs



- Chemical shifts from the trajectories were calculated using SPARTA+ (https://spin.niddk.nih.gov/bax/software/SPARTA+/)
- Maximum Entropy Reweighting approach used in this project is from https://doi.org/10.1101/2024.10.04.616700
- SAXS profiles were calculated using Pepsi-SAXS (https://team.inria.fr/nano-d/software/pepsi-saxs/)
- RDCs were calculated using PALES (https://www3.mpibpc.mpg.de/groups/zweckstetter/_links/software_pales.htm) [will require a SINGULARITY BUILD/APPTAINER to run PALES on a newer Linux environment]
- writhe_tools package (pip install writhe-tools) was used to calculate writhe features for the analyses [More information on the method can be found in the preprint https://doi.org/10.1101/2025.04.26.650781]