<!--- Please see below for ASCII codes -->
<!--- USE &#x274C; for "red X" -->
<!--- USE &#x2705; for "green check mark" -->

# Data Insights & Analytics Data Source Refresh

## As of: 8/11/2020 6:25 AM 

### Notes:
<!---    -->
### Few data sources refresh are still in progress as of now.
<!--- END NOTES SECTION -->
***

| Data Source             | Tableau  |  GAH/IBI      | Hyperion/PBCS|
| ------------            | :------: |  :----------: | :----------: |
| AA Sub                  | &#x274C; | &#x2705;      | &#x2705;  |
| AP Invoice              | &#x2705; | &#x2705;      | &#x2705;  |
| AR Header               | &#x2705; | &#x2705;      | &#x2705;  |
| AR Line                 | &#x2705; | &#x2705;      | __N/A__  |
| Backlog                 | &#x2705; | &#x2705;      | &#x2705;  |
| International Tax       | &#x2705; | &#x2705;      | &#x2705;  |
| Inventory               | &#x274C; | &#x274C;      | &#x274C;  |
| OPR                     | &#x274C; | &#x2705;      | &#x2705;  |
| PA Labor Hours          | &#x274C; | &#x2705;      | __N/A__  |
| PPR                     | &#x2705; | &#x2705;      | &#x2705;  |
| Preliminary Orders      | &#x2705; | __N/A__       | __N/A__  |
| Services Effective Cost | &#x2705; | __N/A__       | __N/A__  |
| Services Projections    | &#x2705; | __N/A__       | &#x2705;  |

***


### SLAs

1. If only Hyperion/PBCS are impacted, only include Finance Systems and Analytics.
2. Alert goes out by **6:30 AM Central**.  During Finance month-end close (business days 1-5) please alert by **5:00 AM Central**.
3. If the issue is for a Tableau refresh only, please do not include distribution lists in Business List 3 and Business List 4.


### Distribution Lists for Alerts

 | Data Source           | Business List 1               |  Business List 2    | Business List 3  | Business List 4|
| ------------           | ----------------------------- |---------------   | ----------       | ----------    | 
| AA Sub                 | Finance Systems and Analytics   | ServicesFinance   | FinanceClosing        |
| AP Invoice             | Finance Systems and Analytics   | ServicesFinance   | Finance Data Alert AR | Finance Data Alert BBC |
| AR Header              | Finance Systems and Analytics   | ServicesFinance   | Finance Data Alert AR | Finance Data Alert BBC |
| AR Line                | Finance Systems and Analytics   | ServicesFinance   | Finance Data Alert AP |
| Backlog                | Finance Systems and Analytics   | ServicesFinance   | FinanceClosing        |
| International Tax      | Finance Systems and Analytics   | ServicesFinance   | Balazs.Tomanoczy@wwt.com|
| Inventory              | Finance Systems and Analytics   | ServicesFinance   |  |
| OPR                    | Finance Systems and Analytics   | ServicesFinance   | FinanceClosing  |
| PA Labor Hours         | Finance Systems and Analytics   | ServicesFinance   |   |
| PPR                    | Finance Systems and Analytics   | ServicesFinance   |   |
| Preliminary Orders     | Finance Systems and Analytics   | ServicesFinance   |   |
| Services Effective Cost| Finance Systems and Analytics   | ServicesFinance   |   |
| Services Projections   | Finance Systems and Analytics   | ServicesFinance   |   |
