## Dashboard

The live dashboard can be viewed here:
https://tejshah01.github.io/Paulding-FQHC-Rationale/

# Rationale for an FQHC Look-Alike in Paulding County

This repository contains the source code for a DATA 555 final dashboard examining selected health indicators in Paulding County, Georgia. 
The dashboard uses county-level CDC PLACES data to compare Paulding County with national estimates and project benchmarks for health 
conditions relevant to primary care and community health planning.

## Research Topic

The project evaluates whether Paulding County has health needs that support the rationale for a potential Federally Qualified Health Center Look-Alike site. 
The dashboard focuses on indicators such as obesity, high blood pressure, diagnosed diabetes, depression, and current asthma.

## Project Importance

This dashboard highlights key health and access-related needs in Paulding County as a rationale for a grant for a potential FQHC Look-Alike site. 
By comparing local indicators with national estimates and project benchmarks, the dashboard helps identify priority areas where expanded primary care, 
behavioral health, and enabling services could improve community health.

## Data Source

The dashboard uses publicly available county-level health indicator data from the CDC PLACES dataset. 
The dataset includes model-based estimates for adult health outcomes and risk factors.

## Source Code

The source code for this dashboard is included in `index.Rmd`. 

The first interactive Plotly widget is generated in the code chunk beginning with `plot_df <- analysis_df %>%`.
The source code for this can be found here:-
https://github.com/TejShah01/Paulding-FQHC-Rationale/blob/dd4997691299804b4e42d8941610111494808059/index.Rmd#L104-L199

The second interactive Plotly widget is generated in the code chunk beginning with `viz2_df <- analysis_df %>%`.
The source code for this can be found here:-
https://github.com/TejShah01/Paulding-FQHC-Rationale/blob/dd4997691299804b4e42d8941610111494808059/index.Rmd#L210-L315
