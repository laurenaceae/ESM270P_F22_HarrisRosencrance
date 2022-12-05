# ESM270P_F22_HarrisRosencrance
## Analytic Hierarchy Process Methodology

This code calculates aggregated preferences for 4 conservation criteria (water resources, climate resilience, biodiversity, agriculture) using the analytic hierarchy process developed by Saaty in 1987 (https://doi.org/10.1016/0270-0255(87)90473-8). The second half of the code analyzes the impact of elevating indigenous voices on AHP aggregated weights. Data for this code is not included in order to protect respondent privacy. To run this code with data, create a folder called `input_data` in the main rproj folder and place the unprocessed csv of responses there. 

Variables to set:

- indigenous_vector (0s and 1s to determine which responses to duplicate)
- file name and path (if differing from original)

Outputs for each AHP:

- Preference score and consistency ratio per individual and per paired comparison
- Comparison matrix per respondent
- Table of scaled and aggregated AHP results 
- Table of individual AHP results and consistency ratios 
- Mean consistency ratio
- Standard deviation of consistency ratios