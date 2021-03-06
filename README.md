# Chemotherapy-Associated-Liver-Injury
The rationale is to verify whether digital tissue samples' intrinsic heterogeneity can differentiate between healthy and diseased livers.

Hypothesis: heterogeneity in the volumes highlights the presence of CALI, Chemotherapy associated liver injury.

Goals:
- Investigate the relationship between heterogeneity of virtual biopsy and cali
- Given a patient try to understand if she/he is likely to develop cali as a consequence of chemotherapy

# Data

`Data` is protected by Copyright, They are provided by Humanitas hospital of Milan.
125 volumes (3d matrices) representing a virtual biopsy of patients’ liver.

In addition, clinical variables of patients are available for further analysis:
- Age (avg = 62.4, var = 126.3)
- Sex (87 M, 56 F)
- Obesity (13%)
- BMI - Body Mass Index (avg = 25.4, var = 15.5)
- IPA - Arterial Hypertension (43%)
- Post-operative complications (33%)

# Code
The main script is `Cali_beta.ipynb`; after a graphical and mathematical analysis which allows to make hypothesis to solve the problem this script mainly uses the other auxiliary scripts to do Functional Clustering using the entropy of the volumes and Clustering using filtering functions on the virtual biopsy in order to remove noise and reduce the dimension of the information. 

For the Unsupervised learning part the script `Distances.py` is the one which defines the different metrics perfomed on the volumes to define a distance between two volumes. 

The script `Kernel.py` performs different type of volumes transformation (using filtering functions).

## Authors
* [Matteo Tomasetto](https://github.com/MatteoTomasetto)
* [Paolo Gerosa](https://github.com/PaoloGerosa)
* [Lupo Marsigli](https://github.com/LupoMarsigli)
* [Francesco Romeo](https://github.com/fraromeo)
* [Sebastiano Rossi](https://github.com/Seb1198)
