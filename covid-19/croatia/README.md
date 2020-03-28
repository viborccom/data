# COVID-19 / SARS-CoV-2 coronavirus data for Croatia

**Important note**: Starting March 28, 2020 - data for City of Zagreb and Zagreb County are shown together under City of Zagreb. Zagreb county data will now be empty fields (, ,).

This folder contains 2 CSV files.

1) **time-series.csv** contains cummulative data for Croatia as a country
2) **time-series-counties.csv** contains data for all Croatian counties


Here's the CSV description

## time-series.csv


Header | Definition
---|---------
`Date` | An actual calendar date of the data
`TotalCases` | The number of total cases recorded from the start of COVID-19 outbreak
`NewCases` | The number of new cases registered from the last update / day
`PercentageChange` | The percentage of growth of new cases compared with the previous record
`Days` | The number of days from the first registered case
`TotalRecovered` | The number of people who recovered (cummulative)
`TotalDied` | The number of people who died (cummulative)


## time-series-counties.csv


Header | Definition
---|---------
`County` | The name of the county, in Croatia, also includes cummulative data for Croatia under "Republika Hrvatska"
`21.3, 22.3., 23.3. ...` | Actual calendar dates and assigned values

