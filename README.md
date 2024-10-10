# ShotSpotter Hit Rate Analysis for Type Investigations and Southside Weekly
This repository is organized as follows:
- `notebooks`
  - `shootings-cleaning.ipynb`: Data cleaning for CPD shooting victims dataset
  - `rfds-cleaning.ipynb`: Data cleaning for CPD reckless firearms discharge data
  - `shotspotter-cleaning.ipynb`: Data cleaning for CPD ShotSpotter data
  - `matching-shootings-alerts.ipynb`: Matching process for determining whether a ShotSpotter alert exists for each shooting
  - `analysis.ipynb`: Notebook containing main analysis findings for the story
- `data`
  - `raw`
    - `Crimes_-_2001_to_Present_20240905.csv`: CPD crime data
    - `Violence_Reduction_-_Shotspotter_Alerts_20240905.csv`: CPD ShotSpotter alert data
    - `Violence_Reduction_-_Victims_of_Homicides_and_Non-Fatal_Shootings_20240905.csv`: CPD shooting victim data
  - `clean`
    - `shotspotter_alerts_2023_2024.csv`: Cleaned ShotSpotter data
    - `reckless_firearm_discharges_2023_2024.csv`: Cleaned reckless firearm discharge data
    - `shooting_victimizations_2023_2024.csv`: Cleaned shooting victimization data
  - `final`
    - `matched_shootings_alerts_2023_2024.csv`: Matched shootings & alerts data for analysis

## Credits
Story conception, reporting, and writing: Max Blaisdell and Jim Daley
Editing: Sasha Belenky and Nina Zweig
Data analysis: Ethan Corey
Fact-checking: Paco Alvarez
