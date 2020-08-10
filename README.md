# annual_hsi

Repository contains used for HSI annual outcome anaysis.

Initial data preparation code is available under the `heat_stress` repo.


## annual_summary

- HSI outcome tables

- Exposure tables: annual indices of heat and humidity

- Exposure over time linear regression models



## bootstrap

Bootstrap models run for select indices with 10,000 resamples.
Models run for full range of indices with 100 resamples.

- Bootstrap models:
  - 2 year block (basic and Bca CIs)
  - 3 year block
  - standard (1 year)
  
 - Non-bootstrap negative binomial models
  - with `year` term
  - without `year` term


- Sensitivity analysis plots
