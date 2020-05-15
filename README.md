# pa-covid
Bill's COVID-19 calculations for PA's metrics to reopen

[The Pennsylvania Governor's Process to Reopen PA](https://www.governor.pa.gov/process-to-reopen-pennsylvania/) references
one metric as being 50 cases per 100,000 in the last 14 days.  I was curious to know how we were doing on that front, so I
decided to create a graph.  I used the county population data from https://worldpopulationreview.com/us-counties/pa/ and
[the New York Times COVID-19 data](https://github.com/nytimes/covid-19-data).

Current image from Google spreadsheets:
![img](https://docs.google.com/spreadsheets/d/e/2PACX-1vS5-jDsS33FbjHfpxjA84q5K_fvuEFbU3xe0HWibmSIf2dhEExttUMY0W4s-8bioUoVrHDNZ7vVSZyr/pubchart?oid=2110172775&format=image)

[There's also an interactive version](https://bit.ly/bill-se-pa-covid19)


How to set up to run this:
```
git clone https://github.com/nytimes/covid-19-data
git clone https://github.com/fenner/pa-covid
cd pa-covid
<download csv from https://worldpopulationreview.com/us-counties/pa/>
<maybe edit pa-covid to change the list of counties>
./pa-covid
```
you will get an `output.csv` file.  If you are as shameful as me you can upload it to Google Sheets and create
a graph that way, or perhaps you have a preferred graphing tool.
