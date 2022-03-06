# Chemotherapy-Associated-Liver-Injury
The rationale is to verify whether digital tissue samples' intrinsic heterogeneity can differentiate between healthy and diseased livers.
HYPOTHESIS: heterogeneity in the volumes highlights the presence of CALI, Chemotherapy associated liver injury.
Goals:
- INVESTIGATE THE RELATIONSHIP BETWEEN HETEROGENEITY OF VIRTUAL BIOPSY AND CALI
- GIVEN A PATIENT TRY TO UNDERSTAND IF SHE/HE IS LIKELY TO DEVELOP CALI AS A CONSEQUENCE OF CHEMOTHERAPY

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
The main script is `Cali_beta.ipynb`; this script uses the other files to do Functional Clustering using the entropy of the volumes and Clustering using filtering functions on the virtual biopsy in order to remove noise and reduce the dimension of the information.

## Authors
* [Matteo Tomasetto](https://github.com/MatteoTomasetto)
* [Paolo Gerosa](https://github.com/PaoloGerosa)
* [Lupo Marsigli](https://github.com/LupoMarsigli)
* [Francesco Romeo](https://github.com/fraromeo)
* [Sebastiano Rossi](https://github.com/)
