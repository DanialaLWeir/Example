# TITLE
Add title

## Research objective
Add overall research objective

## Project structure

protocol/Study protocol and analysis plan

codelists/Concept sets for exposures, outcomes, and covariates

sql/Database extraction scripts

analysis/Quarto documents for statistical analyses

scripts/Reusable helper functions

docs/Study documentation and phenotype definitions

notebook/Meeting notes and decision logs

output/Generated tables and figures


## Data sources

The study uses electronic health record data mapped to the OMOP
Common Data Model.

Data access is restricted and not stored in this repository.

## Analysis workflow

1. Extract cohort and variables using SQL scripts in `sql/`
2. Generate derived datasets
3. Run statistical analyses using Quarto documents in `analysis/`
4. Output tables and figures are saved in `output/`

## Reproducibility guidelines

- Raw data must not be modified.
- All results must be generated using code.
- Analytic decisions should be documented in the notebook folder.
- Changes to code should be committed using Git.



