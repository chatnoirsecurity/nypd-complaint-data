# NYPD Complaint Data

On March 4, 2021, New York City’s civilian police oversight group released a [database of complaints](https://nymag.com/intelligencer/2021/03/the-city-just-published-a-massive-nypd-misconduct-database.html) made against current and former NYPD officers. 

The official data can be found on the NYC website: https://www1.nyc.gov/site/ccrb/policy/MOS-records.page

## Why this? 

The report is fantastic, but it's currently in a form that makes it very hard to aggregate or do statistical analysis on the data.

This is the same data scraped out of Microsoft Power BI, and outputs it into CSV for ease of use. It uses the same data endpoint the official UI does, and only has access to the same public information the official report does.

If you want the script that generates the data, please see https://github.com/chatnoirsecurity/nypd-complaint-scraper

## Useful links
* [Official city site](https://www1.nyc.gov/site/ccrb/policy/MOS-records.page)
* [Definitions of case outcomes](https://www1.nyc.gov/site/ccrb/investigations/case-outcomes.page)
