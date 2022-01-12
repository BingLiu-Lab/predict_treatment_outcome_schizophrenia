# predict_treatment_outcome_schizophrenia

This repository contains data and codes used in the paper **Predicting treatment response in schizophrenia with magnetic
resonance imaging and polygenic risk score**.

All neuroimaging features and polygenic risk scores are saved in a pandas dataframe. The treatment response labels are also included in the column of "responder" (1 indicates responder and 0 means non-responder).

The column names inform feature category (i.e., GMV, ALFF, et al) and brain region number or feature number. For example, "gmv_1" indicates gray matter volume from region 1, which corresponds to the Brainnetome atlas.

The raw genotype data are not publicly available but can be obtained by interested researchers upon official request and ethical approval by contacting the corresponding author.
