# COVID-19 Dashboard 
This dashboard consists of four main parts. The controls specify the subset of the data that is used by the Line Chart, Donut Chart and Bar Chart.

## Data
Upon page load, data is loaded from a CSV file `covid19.csv` using the `d3.csv()` method. The columns are `Day`, `SG`, `MW`, `Imports`, `Deaths`. All this data is massaged into an array with keys based on month and year, e.g "Apr 2020", "May 2021", etc.

## Controls
- The drop-down list contains a list of all the keys available. The subset of the data that is used, is based on this value.
- Further, the checkboxes determine if SG, MW, Imports and Deaths data are shown.

## Line Chart
This is day-to-day statistics.

## Donut Chart
This is total proportion of statistics for that month.

## Bar Chart
This is total statistics for that mnth compared to total of entire dataset.

## Styling
`colSG`, `colMW`, `colImports` and `colDeaths` are CSS styles that determine the colors used by the various data points - `outline`, `fill` and `color` properties.

