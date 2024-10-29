# Pennsylvania Early Voting Analysis

This repository automatically tracks and analyzes Pennsylvania's early voting data for the 2024 General Election. The analysis is updated daily at 8:00 AM EDT using data from the Pennsylvania Department of State.

[Output is accessible here](https://wtwillterp.github.io/PA_Earlyvote)

## 🔄 Data Source

Data is pulled daily from the Pennsylvania Department of State's official daily mail ballot report:
[PA Voter Services Mail Ballot Report](https://www.pavoterservices.pa.gov/2024%20General%20Daily%20Mail%20Ballot%20Report.xlsx)

## 📈 Analysis Details

The analysis includes:
- Total ballot applications and returns by party
- Democratic vs Republican return rates
- Independent voter assumptions and impact
- Projected turnout analysis based on 2020 benchmarks

## 🛠️ Technical Details

- Data processing performed in R using tidyverse
- Visualization and report generation using Quarto
- Automated daily updates via GitHub Actions
- Hosted on GitHub Pages