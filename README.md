# awesome-ga-metrics-discovery
Uncover the definition of metrics and logic to analyze data accurately

## Acquisition
1. Organic Searches
 - **Definition:** The number of organic searches that occured within a session
 - **Query:** This query returns site usage data for all traffic by search engine, sorted by pageviews in descending order.
 - **General Query:** 
 
```javascript
dimensions=ga:source
metrics=ga:pageviews,ga:sessionDuration,ga:exits
filters=ga:medium==organic
sort=-ga:pageviews
```
