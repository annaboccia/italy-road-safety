# Italian Road Safety: Where to Invest First

Data Analytics Capstone Project — Anna Boccia

## Objective

I analysed road accidents in Italy from 2021 to 2024 to identify
municipalities to investigate for road safety investments.

## Data and tools

I used:
- ISTAT accident data, downloaded through its API.
- SITUAS population and area data, referring to 2020.
- Python for cleaning, charts, clustering and statistical analysis.
- Power BI for the dashboard.

## Main results

The analysis compares 6,331 municipalities with four years of data.
Rankings include 1,206 municipalities with at least 10,000 residents.

Bergamo, Florence, Genoa, Milan and Riccione remain in the top five
when I change the weights of the priority score.

These are priorities for further investigation, not guaranteed
investment opportunities.

## Files

- Python notebook: code, analysis and results.
- Power BI dashboard.
- Five-slide PDF presentation.
- CSV files in the data folder.

The large ISTAT CSV is not included. The notebook downloads it
automatically if it is missing.

## How to use

Run the notebook cells in order, keeping situas_comuni.csv
inside a folder named data.

Open the dashboard with Power BI Desktop.
To refresh its data, update the CSV source paths.

## Limitations

Population and area refer to 2020.
Traffic volumes and intervention costs are not available.
The results show associations, not causes.
