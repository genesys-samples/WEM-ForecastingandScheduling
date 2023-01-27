---
title: "Before Getting Started"
chapter: false
weight: 10
---

### Before Getting Started

One part of forecasting that is crucially important is solid data. Genesys Cloud CX offers the most sophisticated methodology in WFM using the interaction data that has taken place in your Genesys Cloud CX organization. Automatic Best Method Forecasting includes: 
- Built-in, automated capabilities for historical data cleanup
- Outlier and calendar effect identification
- Pattern detection including seasonality and trends
- Best-of-best modeling to select from 20+ methodologies including ARIMA, WM, Decomp

Of course, not all of us following along in this workshop are using a Genesys Cloud CX organization that has lots of data. If you fall in that boat where you don't have much data, Genesys Cloud CX offers a Historical Data Import that allows you to manually add interaction data from an outside source. If you have interaction data in your org, feel free to skip along to the first-time setup section. 

### Get Some Data in Your Org
**Heads up: In this part of the workshop, you'll be importing data using the Historical Data Import feature. This feature runs the import at 3 am nightly. If you do need to complete this section, you'll need to stop this workshop after going through the steps outlined below and continue the next day when the import is successful.**

#### Create the Queues 
The first step we need to do to import our historical data will be adding the queues to your organization that we have in our data. In our example, you'll need to create two queues. If you haven't created a queue before in Genesys Cloud CX, follow along with this resource center article https://help.mypurecloud.com/articles/create-queue/. We need to create two queues and be sure to match the naming of the queues exactly (if the names don't match exactly, the import of data will fail). 
1. New Orders
2. Existing Accounts

In both of these queues, you'll need to add the agents that you wish to schedule. For testing purposes, choose at least 2 other users in your org that you'll use as part of the workshop. Add your Genesys Cloud CX user and the other users you've chosen to both of the queues. 
![Add Queue Members](/images/addQueueMembers.jpg)

#### Import Your Data
We have provided you with a data set to import. You'll need to navigate to this GitHub repository, https://github.com/genesys-samples/WFMHistoricalDataImport, and download the CSV file to your local machine. You'll then need to follow the steps outlined in this article to import the CSV file's data into your Genesys Cloud CX org. https://help.mypurecloud.com/articles/import-historical-data/

As previously mentioned, the import process, when in Pending status, completes at approximately 3 am local time in each region. If you needed to do this step, you should be able to resume this workshop tomorrow once the import successfully completes. 