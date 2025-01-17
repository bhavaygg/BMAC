The repository contains scripts used for predictive modelling for the paper titled "On-chip 3D potency assay for improved prediction of clinical outcomes for cell therapy candidates for osteoarthritis". The analysis compares the predictive modelling of pain scores (KOOS and VAS) using analytes measured using 3 different methods ('On-chip ctrl NORM', 'On-chip simSF NORM', '2D simSF NORM'). 
THe modelling is performed using lASSO regression and using `RepeatedStratifiedKFold` for consistency. The script contains 3 sections - 

- KOOS Modelling
- VAS Modelling
- Modelling using topk most predictive and most correlated features: In this section we want to find which analytes are the most predictive of the KOOS and VAS scores. 
