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
| `ca_hcai_construction_cost.csv` | Main dataset — total construction cost and number of active projects per California county, pipeline stage, and snapshot date (October 2013 – present) |
| `datapackage.json` | Machine-readable manifest — authoritative column schema, data types, and source metadata |
| `data-dictionary-total-construction-cost-of-healthcare-projects.csv` | Data dictionary bundled by the portal — note: describes a related HCAI building inventory dataset, not the main CSV |
| `data-dictionary-total-construction-cost-of-healthcare-projects-data-dictionary.csv` | Meta-dictionary — describes the structure of the data dictionary itself |

## Updating the data

To refresh the dataset, download the latest CSV from the California Open Data 
Portal link above and upload it to this repository replacing 
`ca_hcai_construction_cost.csv`. The filename is date-neutral so the notebook 
URL does not need to change. Record the download date in the version history 
below.

## Version history

| Date | Notes |
|------|-------|
| 23 July 2026 | Initial download |

## Notes

The two data dictionary CSV files belong to a related HCAI dataset and do not
describe the columns in the main CSV. The correct column definitions are in
`datapackage.json`.

Data licence: see `datapackage.json`. This repository contains California 
government open data — the notebook code is separately licenced under MIT.
