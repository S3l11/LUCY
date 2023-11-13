# On-cloud decision-support system for non-small cell lung cancer histology characterization from thorax computed tomography scans
This repository contains the main code of **LUCY**, the clinical decision-support system for non-small cell **LU**ng **C**ancer
histolog**Y** characterization directly from thorax computed tomography scans, presented in the paper:

>Selene Tomassini, Nicola Falcionelli, Giulia Bruschi, Agnese Sbrollini, Niccolò Marini, Paolo Sernani, Micaela Morettini, Henning Müller, Aldo Franco Dragoni, Laura Burattini. On-cloud decision-support system for non-small cell lung cancer histology characterization from thorax computed tomography scans. Computerized Medical Imaging and Graphics, Elsevier, 2023, 102310, https://doi.org/10.1016/j.compmedimag.2023.102310.

# Abstract
Non-Small Cell Lung Cancer (NSCLC) accounts for about 85% of all lung cancers. Developing non-invasive techniques for NSCLC histology characterization may not only help clinicians to make targeted therapeutic treatments but also prevent subjects from undergoing lung biopsy, which is challenging and could lead to clinical implications. The motivation behind the study presented here is to develop an advanced on-cloud decision-support system, named LUCY, for non-small cell LUng Cancer histologY characterization directly from thorax Computed Tomography (CT) scans. This aim was pursued by selecting thorax CT scans of 182 LUng ADenocarcinoma (LUAD) and 186 LUng Squamous Cell carcinoma (LUSC) subjects from four openly accessible data collections (NSCLC-Radiomics, NSCLC-Radiogenomics, NSCLC-Radiomics-Genomics and TCGA-LUAD), in addition to the implementation and comparison of two end-to-end neural networks (the core layer of whom is a convolutional long short-term memory layer), the performance evaluation on test dataset (NSCLC-Radiomics-Genomics) from a subject-level perspective in relation to NSCLC histological subtype location and grade, and the dynamic visual interpretation of the achieved results by producing and analyzing one heatmap video for each scan. LUCY reached test Area Under the receiver operating characteristic Curve (AUC) values above 77% in all NSCLC histological subtype location and grade groups, and a best AUC value of 97% on the entire dataset reserved for testing, proving high generalizability to heterogeneous data and robustness. Thus, LUCY is a clinically-useful decision-support system able to timely, non-invasively and reliably provide visually-understandable predictions on LUAD and LUSC subjects in relation to clinically-relevant information.

# Data & Full code
Data used in this paper are openly accessible (for details, please, have a look to the corresponding Section in the paper). 
Full code is available upon request, specifying the purpose for which it would be used.

# Terms of use
In case all (or part of) the main code released in this repository would be used, please, cite the paper.