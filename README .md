# European Airport Performance

## About the project
This Power BI project explores airport delays and operational performance in Europe, using data for 2019 and 2022–2025. It brings together traffic volumes, delay reasons, and additional approach and taxi-out time to compare airports and countries, identify monthly patterns, and examine changes in delay per flight compared with 2019.

The focus is on looking beyond total delay figures. Comparing several indicators gives a broader picture of airport performance than ranking airports by delay alone.

## Data

The data comes from the [EUROCONTROL Aviation Intelligence Portal](https://ansperformance.eu/data/). It covers airport arrival ATFM delays and their causes, additional approach time (ASMA) and additional taxi-out time.

The datasets are connected through shared airport and date tables, with a separate table for delay causes. DAX measures calculate indicators such as delay per flight and changes compared with 2019. Calculated columns provide airport labels and country groups.

## Report pages

- **Overview** brings together traffic volumes, delays, monthly trends and delay reasons, alongside airport and country rankings.
- **Approach** compares additional approach and taxi-out time across months and airports.
- **Airport scorecard** combines an airport scatter chart with a country-to-airport matrix, including changes in delay per flight compared with 2019.

## Key findings
- In 2025, additional taxi-out time peaked in July at 4.34 minutes per flight, with elevated values in the surrounding summer months.
- Weather was the largest recorded contributor to airport arrival ATFM delay in 2025, accounting for approximately 3.3 million minutes. Aerodrome capacity and ATC capacity followed, at approximately 1.7 million and 1.6 million minutes respectively.
- Poland and Italy were selected as examples from different parts of Europe to illustrate contrasts between performance indicators. In 2025, Poland recorded higher arrival ATFM delay per flight than Italy (0.48 versus 0.29 minutes), while Italy had higher additional taxi-out time (4.6 versus 3.1 minutes).
- In 2025, airport arrival ATFM delay averaged 0.81 minutes per flight, compared with 0.86 minutes in 2019—a reduction of approximately 0.05 minutes per flight.

## Notes on the results

The delay figures cover airport arrival ATFM delays, not all delays experienced by passengers. Approach and taxi-out values represent additional time, rather than the full duration of each phase.

Comparisons with 2019 reflect the selected period. If several years are selected, the comparison is for that selection, not just the latest year. The scorecard uses a minimum of 25,000 arrivals within the selected period.

Percentage changes can look very large when the 2019 value was close to zero. For this reason, the matrix leaves the percentage blank when the baseline is below 0.1 minute per flight, while still showing the change in minutes where data is available. Other blank results indicate missing data, not zero.

Time values are expressed in decimal minutes; for example, 0.48 minutes is approximately 29 seconds, while 4.6 minutes is 4 minutes 36 seconds.
