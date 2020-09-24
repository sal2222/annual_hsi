# annual_hsi

### Heat Stress Illness Outcomes and Annual Indices of Outdoor Heat at U.S. Army Installations

This study characterizes associations between annually-scaled thermal indices and annual heat stress illness (HSI) morbidity outcomes among active duty soldiers at ten Continental U.S. (CONUS) Army installations in order to better characterize outcome sensitivities to changing environmental conditions.

Initial data preparation code is available under the [`heat_stress`](https://github.com/sal2222/heat_stress)  repo and is outlined at https://sal2222.github.io/heat_stress/.
Plots of HSI rates over time, by installation, against selectable annual exposure indices available at: https://sal2222.shinyapps.io/annual_heat/.

## `output` folder

- full table of IRR results from 2-year bootstrap models
- IRR whisker plots
- index-type mosaic plots of associations
- plot of indices over time by installation
- sensitivity analysis IRR whisker plots

## `annual_summary`

Code for:
- HSI outcome tables

- Exposure tables: annual indices of heat and humidity

- Exposure over time linear regression models



## `bootstrap2`

Code for: 
Bootstrap models run for select indices with 10,000 resamples.
Models run for full range of indices with 2,000 resamples.

- Bootstrap models:
  - 2 year block (basic and Bca CIs)
  - 3 year block
  - standard (1 year)
  
 - Non-bootstrap negative binomial models:
  - with `year` term
  - without `year` term

- Sensitivity analysis plots
