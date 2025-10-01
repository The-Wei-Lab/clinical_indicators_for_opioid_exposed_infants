# clinical_indicators_for_opioid_exposed_infants
Code repository for covariates generated for evaluating risk for opioid exposed infants at Vanderbilt University Medical Center. The original code for creating the phenotype has been published at https://github.com/Precision-Phenotyping-Core/opioid-exposed-infants. See README for more information.


## Organization
Code is split into two subgroups:

Notebook Repository from Original Phenotype Publication contains the notebooks and references from the original phenotype that has been published in the github listed above. This set of files has been condenced for its usage in covariate generation, and are designed to be run sequencially in number order. Teams looking to replicate the phenotype and its covariates should first run the full phenotype before utilizing those saved outputs for covariate generation

Covariate Creation Notebooks contains the set of notebooks used to generate the covariates that are listed in the PheKB and will be referenced in future publications. These notebooks can mostly be run seperately with the exception of hcv and hiv covaraiate notebooks which are combined from lab and diagnosis codes. 

## Code Creation

The Code was developed and used in Databricks. The structure of the code relies on a relational OMOP database for storage and organization of patient data. Each notebook collects and computes data using Pyspark and is designed for cloud computing. To learn more, see https://www.databricks.com/product/data-intelligence-platform.
