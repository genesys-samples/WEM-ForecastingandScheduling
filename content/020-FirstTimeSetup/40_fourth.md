---
title: "Forecast and Schedule Generation"
chapter: false
weight: 40
---

## About Forecasting & Scheduling in Genesys Cloud CX
Genesys Cloud CX forecasts for both voice and digital channels that route through queues. While there are multiple types of forecasting available, we will be focusing our efforts today on the AI-powered Automatic Best Method Selection. To read more about what makes this type of forecast special, navigate to this resource article. https://help.mypurecloud.com/articles/automatic-best-method-forecast-method-overview/ 

Once a forecast is created for a certain period, schedules can then be generated based on that forecast. Schedule generation uses data from a short-term forecast along with week- and day-level scheduling constraints to produce a week’s schedule. Administrators will schedule generation from forecasting to return predicted service performance that closely matches requirements with as few paid hours as possible. Let's get started

### Create a Forecast using AI
1. Navigate to the Forecasts page from the Genesys Cloud Admin console
2. Ensuring you are in the "North America" business unit you created earlier, click to add a new forecast
3. For the start date, choose the upcoming Monday and we will forecast out 6 weeks (you can forecast up to 104 weeks for long-term planning)
4. Choose Automatic Best Method Selection as the creation method and then press Add Forecast
![Add Forecast](/images/addForecast.jpg)
5. Explore the forecast while reading this article https://help.mypurecloud.com/articles/navigate-the-forecast/ (no actual changes to the forecast need to be made)

### Generate a Schedule based on our Forecast
1. Navigate to the Schedules section under the WorkForce Management container
2. Click the Generate button 
    - Match the start date to the forecasts start date (the upcoming Monday)
    - Change the number of weeks to 6 (this means we will schedule our agents out 6 weeks)
    - Select the forecast that you just created and press Generate
    ![Generate Schedule](/images/generateSchedule.jpg)
3. Explore the different options in the schedule editor while reading this article https://help.mypurecloud.com/articles/navigate-schedule-editor/ (no actual changes to the schedule need to be made)
4. Press publish to push this schedule out to agents

Congrats! You've successfully set up forecasting and scheduling in Genesys Cloud CX using some of the built-in artificial intelligence tools! In the next section, we'll walk you through some common scenarios that WFM administrators might run into and how to address them in Genesys Cloud CX. 