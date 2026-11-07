# LCA and LCC of a Combined Pyrolysis and Anaerobic Digestion Plant

Extension of a cooperative design project at TUM Campus Straubing. I added a life cycle assessment (LCA) and a life cycle cost calculation (LCC) to a biogas plant with a pyrolysis unit.

## What is in this repo
- `LCA_LCC_Report_Pyrolysis_AD_final.pdf`: the full report (24 pages)
- `LCA_LCC_Pyrolysis_AD_final.xlsx`: Excel model with the inventory, GWP check and cost calculation

## Method
- Functional unit: 1 t of feedstock
- LCA in openLCA 2.5.0 (Agribalyse 3.2, IPCC 2021 GWP100), checked against the Excel model
- LCC in Excel: net cost per tonne and NPV over 20 years, with spot-price and EEG cases

## Main results
- Base case: about 36 kg CO2e per t of feedstock
- With heat sold: about -5 kg CO2e per t
- Cost at 2025 spot price: about EUR 17 per t, NPV about -EUR 44 million
- With an EEG tariff the NPV is positive, but this is an upper bound (EEG cap not modelled)

## Limits
This is a screening-level study. Some inputs are my own assumptions (pyrolysis share, syngas heating value, own electricity use). They are listed in section 9 of the report.

## Author
Jeffrey Saju, M.Sc. Biomass Technology, TUM Campus Straubing
