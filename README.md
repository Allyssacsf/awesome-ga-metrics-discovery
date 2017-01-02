# awesome-ga-metrics-discovery
Uncover the definition of metrics and logic to analyze data accurately

## Acquisition
1. Organic Searches
 - **Definition:** The number of organic searches that occured within a session
 - **Query:** This query returns site usage data for all traffic by search engine, sorted by pageviews in descending order.
 - **General Query:** 
> dimensions=ga:source
> metrics=ga:pageviews,ga:sessionDuration,ga:exits
> filters=ga:medium==cpa,ga:medium==cpc,ga:medium==cpm,ga:medium==cpp,ga:medium==cpv,ga:medium==organic,ga:medium==ppc
> sort=-ga:pageviews

