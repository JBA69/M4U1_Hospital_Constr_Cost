# M4U1 — Healthcare Construction Cost Intelligence

Source dataset for the MAICEN M4U1 assignment: 
*A Predictive Engine for Market Calibration in California*.

## Data source

California Department of Health Care Access and Information (HCAI)  
California Open Data Portal  
https://data.ca.gov/dataset/total-construction-cost-of-healthcare-projects

## Contents

| File | Description |
|------|-------------|
| `ca-hcai-total-construction-cost-07232026.csv` | Main dataset — total construction cost and number of active projects per California county, pipeline stage, and snapshot date (October 2013 – July 2026) |
| `datapackage.json` | Machine-readable manifest — authoritative column schema, data types, and source metadata |
| `data-dictionary-total-construction-cost-of-healthcare-projects.csv` | Data dictionary bundled by the portal — note: describes a related HCAI building inventory dataset, not the main CSV |
| `data-dictionary-total-construction-cost-of-healthcare-projects-data-dictionary.csv` | Meta-dictionary — describes the structure of the data dictionary itself |

## Notes

The two data dictionary CSV files belong to a related HCAI dataset and do not 
describe the columns in the main CSV. The correct column definitions are in 
`datapackage.json`.

Data downloaded: 23 July 2026.
