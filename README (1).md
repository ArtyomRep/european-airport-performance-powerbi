# European Airport Performance

## About the project

This Power BI project looks at airport delays and operational performance in Europe, using data for 2019 and 2022–2025. The aim is to compare airports and countries, explore monthly patterns and see how delay per flight differs from the 2019 baseline.

Airport performance offers more to explore than a ranking of total delays. Looking at traffic volumes, delay per flight and additional approach and taxi-out time together gives a broader picture of the differences between airports. This is the focus of the report.

## Data

The data comes from the [EUROCONTROL Aviation Intelligence Portal](https://ansperformance.eu/data/). It covers airport arrival ATFM delays and their causes, additional approach time (ASMA) and additional taxi-out time.

The datasets are connected through shared airport and date tables, with a separate table for delay causes. DAX measures calculate indicators such as delay per flight and changes compared with 2019. Calculated columns provide airport labels and country groups.

## Report pages

- **Overview** brings together traffic volumes, delays, monthly trends and delay reasons, alongside airport and country rankings.
- **Approach** compares additional approach and taxi-out time across months and airports.
- **Airport scorecard** combines an airport scatter chart with a country-to-airport matrix, including changes in delay per flight compared with 2019.

## Notes on the results

The delay figures cover airport arrival ATFM delays, not all delays experienced by passengers. Approach and taxi-out values represent additional time, rather than the full duration of each phase.

Comparisons with 2019 reflect the selected period. If several years are selected, the comparison is for that selection, not just the latest year. The scorecard uses a minimum of 25,000 arrivals within the selected period.

Percentage changes can look very large when the 2019 value was close to zero. For this reason, the matrix leaves the percentage blank when the baseline is below 0.1 minute per flight, while still showing the change in minutes where data is available. Other blank results indicate missing data, not zero.
