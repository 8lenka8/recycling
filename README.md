# recycling

UK Recycling Databricks Hackathon for Good SparkAISummit

https://data-teams-unite.devpost.com/

ETL
1.  Get UK waste and recycling dataset http://www.wastedataflow.org/reports/default.aspx
2a. Pre-process it to convert into graph, generating unique facility IDs via geocoding
2b. Tag on CO2e and monetaty value of materials extracted from waste (TODO)
3.  Load the graph into spark for ML

Insights of interest
1. Measure market shocks and policy impacts, such as:
   * China refuses accepting forein waste in 2019
   * London Boroghs move to mixed recycling collections in different years
2. Compare Local Authority performance
3. Compare impacts and performance in terms of CO2e and revenue 
4. Simulate effects of lockdown (validate vs 2020 data to be released later in the year)
