# Number of child deaths by region - Data package

This data package contains the data that powers the chart ["Number of child deaths by region"](https://ourworldindata.org/grapher/child-deaths-igme-data?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on December 20, 2024.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Number of under-five deaths
Last updated: May 20, 2024  
Next update: May 2025  
Date range: 1960–2021  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Multiple sources compiled by World Bank (2024) – processed by Our World in Data

#### Full citation
Multiple sources compiled by World Bank (2024) – processed by Our World in Data. “Number of under-five deaths” [dataset]. UN Inter-agency Group for Child Mortality Estimation (via World Bank), “World Development Indicators” [original data].
Source: Multiple sources compiled by World Bank (2024) – processed by Our World In Data

### What you should know about this data

### How is this data described by its producer - Multiple sources compiled by World Bank (2024)?
Number of children dying before reaching age five.

Limitations and exceptions: Complete vital registration systems are fairly uncommon in developing countries. Thus estimates must be obtained from sample surveys or derived by applying indirect estimation techniques to registration, census, or survey data. Survey data are subject to recall error, and surveys estimating infant/child deaths require large samples because households in which a birth has occurred during a given year cannot ordinarily be preselected for sampling. Indirect estimates rely on model life tables that may be inappropriate for the population concerned. Extrapolations based on outdated surveys may not be reliable for monitoring changes in health status or for comparative analytical work.

### Source

#### UN Inter-agency Group for Child Mortality Estimation (via World Bank) – World Development Indicators
Retrieved on: 2024-05-20  
Retrieved from: https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators  


    