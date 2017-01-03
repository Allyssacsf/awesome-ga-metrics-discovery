# awesome-ga-metrics-discovery
Uncover the definition of metrics and logic to analyze data accurately

------------------------------------------------------------------------------------------------------------------
Format and Style Standards:
##Category
1. Metric
 - **Definition:** xxx
 - **Link:**
 - **Relevent Case/Report:**
 - **Query:** xxx
 - **General Query:**
```javascript
dimensions=xxx
metrics=xxx
filters=xxx
sort=xxx
```
------------------------------------------------------------------------------------------------------------------

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

## Ad Exchange *Notes: Action Required-fill up the blank.*
1. AdX Clicks
 - **Definition:** The number of times AdX were clicked on your site
 - **General Query:** 
```javascript
metrics=ga:adxClicks
```

##Advertising *Notes: Action Required-fill up the blank.*
1. Clicks 
 - **Definition:** The number of times users click on your ad. The *Clicks* metric differs from the *Sessions* metric, which is the number of unique sessions initiated by your users. Because *Clicks* and *Sessions* are distinct metrics, you may see different number reported in Analytics.

##Behaviour
1. % Sessions with Search
 - **Definition:** The percentage of sessions with search
 - **Query:** Sessions with Search / Total Sessions.

2. Average Search Depth
 - **Definition:** The number of pages visitors viewed adter getting results for the search term

3. Avg. Document Content Loaded Time(sec)
 - **Definition:** Average time(in seconds) that the browser takes to parse the document and execute deferred and parse-inserted scripts (DOMContentLoaded), including the network time from the user's location to your server

4. Avg. Document Interactive Time (sec)
 - **Definition:** The average time(in seconds) that the browser takes to parse the document(DOMInteractive, including the network time from user's location to your server

5. Avg. Domain Lookup Time (sec)
 - **Definition:** The average amount of time (in seconds) spent in DNS lookup for this page
 
6. Avg. Page Download Time (sec)
 - **Definition:** The average amount of time (in seconds) to download this page
 
7. Avg. Page Load Time (sec)
 - **Definition:** Avg. Page Load Time is the average amount of time (in seconds) it takes for pages from the sample set to load, from initiation of the pageview(e.g. click on a page link) to load completion in the browser. If you see zero(0) as a value or a small increase in November 2011
 - **Link:** [About Site Speed] https://support.google.com/analytics/answer/1205784?topic=1120718&hl=en-GB article
 
8. Avg. Redirection Time (sec)

 *Action Required - fill-up the blank*

9. Search Depth
 - **Definition:** The number of pages visited after the search and before the next one or end of session
 
10. Search Exits
 - **Definition:** The number of exits from your site that occurred following a result from an internal search
 
11. Search Refinement
 - **Definition:** The total number o times a refinement(transition) occurs between internal search keywords within a session. For example if the sequence of keywords is: "shoes","shoes", "pants", "pants", this metric is 1 because the refinement of "shoes" to "pants" occrs once

12. Server Connection Time (ms)
 - **Definition:** The server connection time in milliseconds
 
13. Server Response Time (ms)
 - **Definition:** The server response time in milliseconds
 
14. Sessions with Event
 - **Definition:** Total number of sessions in which at least one Event is triggered

15. Sessions with Search
 - **Definition:** The number of sessions during which at least one site search occurred
 
16. Site Search Goal Conversion Rate
 - **Definition:** The ratio of goal conversions to unique searches. The rate can exceed 100% when a session includes multiple goal conversions per unique search
 
17. Speed Metrics Sample
 - **Definition:** The sample set(or count) of pageviews used to calculate the averages for technical metrics
 
18. Time After Search
 - **Definition:** The amount of time visitors spent on your site after getting results for the search term
 
19. Time After Search
 - **Definition:** The time spent on your site from the start of the current search until session ended or another search started
 
20. Time on Page
 - **Definition:** The amount of time spent on a specified page or screen, or set of pages or screens
 
21. Time on Screen
 - **Definition:** The average amount of time users spend viewing a specific screen or set of screens
 
22. Total Events
 - **Definition:** Total Events is the number of times events occurred
 
23. Unique Dimension Combinations
 - **Definition:** A count of the number of times a unique set of dimension values was seen at least once within a session
 - **Link:** [Unique Events and Unique Combinations] https://support.google.com/analytics/answer/7084499?hl=en-GB
 
24. Unique Events
 - **Definition:** A count of the number of times an event with category/action/label value was seen at least once within a session

25. User Timing (ns)
 - **Definition:** Total user timing in milliseconds
 
26. User Timing Sample
 - **Definition:** User timings measurement volume

##Users
1. % Exit
 - **Definition:** %Exit is (number of exits)/(number of pageviews) for the page or set of pages. It indicates how often users exit from that page or set of pages when they view the page(s)

2. % New Sessions
 - **Definition:** An estimate of the percentage of first time visits
 
3. % Search Exits
 - **Definition:** The number of exits from your site that occurred following a result from an internal search
 
4. % Search Refinement
 - **Definition:** The total number of times a refinement(transition) occurs between internal search keywords within a session.
 
5. Avg. Session Duration
 - **Definition:** The average length of a Session
 
6. Avg. Time on Page
 - **Definition:** The average of time users spent viewing a specified page or screen, or set of pages or screens

7. Avg. Time on Screen
 - **Definition:** The average amount of time users spent on a screen
 
8. Bounce Rate
 - **Definition:** The percentage of single-page visits (i.e. visits in which the person left your site from the entrance page without interacting with the page)
 
9. Bounces
 - **Definition:** The number of single-page visits
 
10. Exits
 - **Definition:** The number of times visitors exited your site from a specified page or set of pages
 
11. Hits
 - **Definition:** Total number of hits sent to Google Analyticsm, for this reporting view(profile). This metric sums all hit types, including pageview, custom event, ecommerce and other types. Note that this number is based on the reporting view(profile), not the propety, and therefore is not the same as the property's hit volume
 
12. New Users
 - **Definition:** The number of first-time users during the selected date range
 
13. Number of Sessions per User
 - **Definition:** The average number of Sessions per user
 
14. Page Views
 - **Definition:** The total number of pages viewed. Repeated views of a single page are counted
 
15. Pages/Session
 - **Definition:** The average number of pages viewed during a session. Repeated views of a single page are counted
 
16. Results Page Views/Search
 - **Definition:** The average number of times visitors viewed a search results page after performing a search
 
17. Screen Views
 - **Definition:** The total number of screens viewed, Repeated views of a single screen are counted
 
18. Screens/Session
 - **Definition:** The average number of screens viewed per session. Every view of a single screen is counted individually, including repeated viws of the same screen
 
19. Session Duration
 - **Definition:** The length of a Session in seconds. A session lasts as long as there is continued activity
 - **Link:** [How a session is defined in Analytics]https://support.google.com/analytics/answer/2731565?hl=en-GB
 
20. Sessions
 - **Definition:** The total number of Sessions within the date range. A session is the period time a user is actively engaged with your website, app, etc. All usage data (Screen Views, Events, Ecommerce, etc) is associated with a session
 
21. Total Unique Searches
 - **Definition:** The number of times people searched your site. Duplicate searches within a single visit are excluded
 
22. Unique Page Views
 - **Definition:** The number of sessions during which the specified page was viewed at least once. A unique pageview is counted for each *page URL + page Title* combination

23. Unique Screen Views
 - **Definition:** The number of sessions during which the specified screen(s) are viewed at least once. Multiple viewings of a screen are counted as a single Unique Screenview
 
24. Users
 - **Definition:** Users that have thad at least one session within the selected date range. Includes both new and returning users
 

##Site Usage
1. Sessions
 - **Definition:** The total number of Sessions within the date range. A session is the period time a user is actively engaged with your website, app, etc. All usage data (Screen Views, Events, Ecommerce, etc) is associated with a session
 
2. Page Views
 - **Definition:** The total number of pages viewed. Repeated views of a single page are counted
 
3. Bounce Rate
 - **Definition:** The percentage of single-page visits (i.e visits in which the person left your site from the entrance page without interacting with the page)
 
4. Avg. Session Duration
 - **Definition:** The average length of a Session
 
5. % New Sessions
 - **Definition:** An estimate of percentage of first time visits
 
##Goals
1. Goal Conversion Rate
 - **Definition:** The sum of all individual goal conversion rates

2. View more (Goal 1 Conversion Rate)
 - **Definition:** The percentage of visits that resulted in a conversion to the goal
 
3. Goal 2 (Goal 2 Conversion Rate)
 - **Definition:** The percentage of visits that resulted in a conversion to the goal
 
4. View more (Goal 1 Value)
 - **Definition:** The monetary value of conversions to the goal
 
5. Goal 2 (Goal 2 Value)
 - **Definition:** The monetary value of conversions to the goal
 
6. Per Session Goal Value
 - **Definition:** The average of a Session (as calculated from Goal Value)
 
##E-commerce
1. Unique Purchases
 - **Definition:** The total number of times a specified product (or set of products) was a part of a transaction
 
2. Product Revenue
 - **Definition:** Revenue from individual product sales
 
3. Quantity
 - **Definition:** The number of units sold in ecommerce transactions
 
4. Revenue
 - **Definition:** The total revenue from web ecommerce or in-app transaction, this can include tax and shipping
 
5. Delivery
 - **Definition:** The total of shipping charges for ecommerce transactions
 
6. Tax 
 - **Definition:** The total of tax charges for ecommerce transactions

7. Transactions
 - **Definition:** The total number of completed purchases on your site
 
8. Average QTY
 - **Definition:** Average number of products sold per transaction
 
9. Average Order Value
 - **Definition:** Average value of transactions
 
10. Per Session Value
 - **Definition:** Average revenue per Session. For mobile apps, this is the average for in-app revenue only. Acquisition revenue (like from app purchases within a marketplace like Google Play) is not included
 
 11. E-commerce Conversion Rate
  - **Definition:** The percentage of sessions that resulted in an e-commerce transaction

##Content
1. Total Unique Searches
 - **Definition:** The number of times people searched your site. Duplicate searches within a single visit are excluded
 
2. Sessions with Search
 - **Definition:** The number of sessions during which at least one site search occurred
 
3. Total Events
 - **Definition:** The number of times events occurred
 
4. Unique Dimention Combinations
 - **Definition:** The number of unique events per category, action or label
 
5. Event Value
 - **Definition:** The total value of an event or set of events. It is calculated by multiplying the per-event value by the number of times the event occurred
 
6. Search Refinements
 - **Definition:** The total number of times a refinement(transition) occurs between internal search keywords within a session. For example if the sequence of keywords is: "shoes", "shoes", "pants", "pants", this metric is 1 because the refinement of "shoes" to "pants" occurs once
 
 7. Time After Search
  - **Definition:** The time spent on your site from the start of the current search until session ended or another search started
  
 8. Search Depth
  - **Definition:** The number of pages visited after the seaerch and before the next one or end of session
  
 9. Search Exits
  - **Definition:** The number of exits from your site that occurred following a result from an internal search
  
 10. Avg. Domain Lookup Time (sec)
  - **Definition:** The average amount of time (in seconds) spent in DNS lookup for this page
  
 11. Avg. Page Download Time (sec)
  - **Definition:** The average amount of time (in seconds) to download this page
 
 12. Avg. Page Load Time (sec)
  - **Definition:** The average amount of time (in seconds) it takes for pages from the sample set to load, from initiation of the pageview (e.g click on a page link) to load completion in the browser. If you see zero(0) as a value or a small increase in November 2011.
  
 13. Avg. Redirection Time (sec)
  - **Definition:** The average amount of time (in seconds) spent in redirects before fetching this page. If there are no redirects, the value for this metric is expected to be 0
  
 14. Avg. Server Connection Time (sec)
  - **Definition:** The average amount of time (in seconds) spent in establishin TCP connection for this page
  
 15. Avg. Server Response Time (sec)
  - **Definition:** The average amount of time (in seconds) your server takes to respond to a user request, including the network time from user's location to your server
  
 16. Avg. User Timing (sec)
  - **Definition:** Average time of user timings in seconds

##Click
1. Impressions
 - **Definition:** How often your ad is shown. An impression is counted each time your ad is shown on a search result page or other site on the Google Network
 
2. Clicks
 - **Definition:** The number of times users click on your ad. The *Clicks* metric differes from the *Sessions* metric, which is the number of unique sessions initiated by your users. Because *Clicks* and *Sessions* are distinct metrics, you may see different numbers reported in Analytics

3. Cost
 - **Definition:** The total amount you paid for your ads
 
4. Click-through Rate (CTR)
 - **Definition:** Adwords CTR is the percentage of ad impressions that resulted in a click
 
5. Cost-per-click (CPC)
 - **Definition:**  The average cost you paid for each click on your search ad(s)
 
6. Cost-per-mille-impressions (CPM)
 - **Definition:** The average cost you paid for each 1000 impressions on content ads


-----------------------------------------------------------------------------------------------------------------
### References
- [Core Reporting Query] https://developers.google.com/analytics/devguides/reporting/core/v3/common-queries#users-and-pageviews-over-time
- [Core Reporting Query Change Log] https://developers.google.com/analytics/devguides/reporting/core/v3/changelog
- [How Site Search metrics are calculated] https://support.google.com/analytics/answer/1032321?hl=en
