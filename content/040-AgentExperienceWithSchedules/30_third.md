---
title: "Requesting a Vacation"
chapter: false
weight: 30
---

## Requesting Time Off - Configuration

In this section we will discuss the supervisor experience of configuring the time off request process agents can go through. In our case, we want to automate this process as much as possible, I am a pretty busy supervisor after all.

First and foremost, we have to turn on Time off requests when creating our Maganement Unit. SInce we have already done this, lets get into the rest of the configuration.

Administrators with appropriate permission can add, approve, edit, and deny time-off requests by clicking Admin and under Workforce Management, selecting Time-Off Requests. If the time-off request passes all time-off plan and limit conditions, the auto-approval engine places the time-off request in an approved state. If the time-off request does not pass all time-off plan and limit conditions, the auto-approval engine places the time-off request in a pending state.

In the most manual perspective, we can create time off requests for agents upon their request and approve them when they are created. Below we show how this can be done by Navigating to Admin > Workforce Management > Time-Off Requests and clicking the add button found in the upper right hand corner.

We will then select the agents we would like to grant time off, the activity code configured for time off and the dates we would like to select. We can also choose the status we would like to use, either pending or approved. for this time off request to go into immediate effect, we will select "approved". Once we have made our selections for this manual time off request, we can save it and have our changes applied.

> **Note: Agents can only use activity codes mapped to a Time Off activity category when requesting time off. For more information about managing activity codes, see [Configure activity codes](https://help.mypurecloud.com/?p=46769)**

![image](/images/manualaddpto.png)
![image](/images/manualconfiguretimeoff.png)

## Automating the PTO Process

There are 2 preliminary components to automating the time off process. The first is creating Time-Off Limits and the second is Time-off Plans. Once these plans are configured, agents will be able to submit time off requests and have them automatically approved given the request made meets all constraints between Time-Off plans, Limits and other configurations made between the workplans and activity codes.

#### Time-off Limits

Administrators with appropriate permissions can view, add, edit, and remove time-off limits. Time-off limits allow you to specify the number of hours available on a particular date for agents to request time off. Even though agents can see time-off requests in their time zone, the limits still divide the days according to the management unit’s time zone. Each management unit can only have one time-off limit per day.

We will navigate to the Time-off Limits configuration pane within workforce management to show what our current configuration is. Since we do not have a time off limit configuration set, we will click the "select all" button next to date to highlight all dates within a 4 week range. On the bottom, we see a window where we can enter the configured limit. We will set this to 8 and apply to show all the selected days now show 8 hours as the time off limit.

![image](/images/timeofflimitselect.png)
![image](/images/timeofflimitapply.png)

#### Time-off Plans

Next we will work with configuring our time off Plan. Administrators with appropriate permissions can view, add, edit, and delete time-off plans. Time-off plans allow you to associate Time Off activity codes to time-off limits. This will then allow you to auto approve time off requests that meet the parameters of your configurations.

To start we will navigate to the Time-Off Plans configuration pane and click add on the top right side:

![image](/images/timeoffplanstart.png)

Once in the create new view, we will need to add our activity codes associated with time off that will be considered when the plan is in effect.

Next, we will select count against time-off limit to reference the limit we previously configured. Once this is selected, we gain the option to Auto approve the time off request when the request is within the bounds of the Time-Off limit we created.

![image](/images/autoapprovetimeoffplan.png)

Finally, we will save our plan to have it go into effect. 

Great Job! we've now created some automated processes to agents abilities to request time off.

## Requesting Time Off - Agent Experience

Now that we have configured our parameters around time off request, agents can now submit their requests. 

First an agent would navigate back to the schedule view and click on the Time off tab. From here we can begin selecting the date and time of our time off request:

![image](/images/agentsubmitpto.png)
![image](/images/agentpto4.png)

There we have it! We have now created an automated process to auto approve agent time off requests. Great Job!