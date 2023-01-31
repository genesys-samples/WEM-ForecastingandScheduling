---
title: "Work Plans"
chapter: false
weight: 30
---

## What are Work Plans? 
Work plans are where administrators get to define weekly, weekend, and day-level scheduling constraints. These constraints are then incorporated into the scheduling process. Agents are assigned to a work plan, which can have multiple shifts. For example, a work plan may include a short, medium and long shift. Short shifts, 2 to 3 hours, might include just "On Queue" time, which means the agents in this shift are available for customer interactions the entire shift. The medium shift, 4 to 6 hours, might incorporate 2 breaks into their day. For the regular shift, 7 or more hours, it would include 2 breaks and a meal to their schedule. For diving more into this example as well as other information about work plans, view this resource center article.https://help.mypurecloud.com/articles/work-plans-overview/

### Creating our Work Plan
Before creating our work plan, there are a few pieces of information we need to know about our business. First off, we only operate Monday through Thursday. Secondly, we only have part-time workers and our maximum weekly paid time is 32 hours. Lastly, there must be at least 10 hours between the end of one shift and the start of another. We want to offer 3 shifts in our work plan that is similar to the example above, offering a short, medium and regular shift. Let's get started. 
1. Under Configuration, click on "Work Plans" and then click add a work plan
2. First, at the top of the plan click to add a name and name this work plan "Sales Team"
3. We want three shifts, so click to add 2 more shifts and then name them Short, Medium, and Regular
![Add Shifts](/images/addShifts.JPG)
4. Next, we want to edit the weekly constraints. Near the top, click on the section that contains Weekly Paid Time
    - Under the Weekly Constraints tab, check the box for Weekly Paid Time and set it to 32 hours. Also, set the Maximum Scheduled Days Per Week to 4 as we are only open Monday through Thursday.
    ![Weekly Constraints](/images/weeklyConstraints.JPG)
    - Now navigate to the General Constraints tab, check the box for Minimum Time Between Shifts and then set this value to 10 hours
    ![Minimum Time Between Shifts](/images/minTimeBetweenShifts.JPG)
5. Now let's set the days that we'll work. For all three shifts, click on Monday through Thursday. 
6. Let's now configure the Short shift
    - The short shift is only 3 hours and begins between 8 am and 10 am
    - First, click on the daily paid time option for the short shift and make the following changes: 
        - Check the box for flexible start times and set the start times between 8 am and 10 am 
        - Change the daily paid time to 3 hours
        ![Short Shift](/images/shortShift.jpg)
7. Now let's configure the Medium Shift
    - The medium shift is between 4 and 6 hours and starts between 9 am and 11 am. This shift also gets 2 breaks during their shift
    - Now click to edit the daily paid time option for the medium shift and make the following changes: 
        - Check the box for flexible start times and set the start times between 9 am and 11 am 
        - Check the box for flexible daily paid time and set the minimum to 4 and the maximum to 6
        ![Medium Shift](/images/mediumShiftv2.jpg)
        - You now want to drag two break activities onto the schedule. Put them at 11 am and 1 pm (ensuring you are previewing the 9 am shift start)
        ![Medium Breaks](/images/mediumBreaksv2.jpg)
8. Finally, let's configure the Regular Shift
    - The regular shift is always 8 hours long starting between 8 am and 9 am and includes 2 breaks and a meal
    - Like with the other shifts, edit the daily paid time option and check the box for flexible start times. Choose 8 am as the earliest and 9 am as the latest
    - Drag break activities onto the shift at 10 am and 2 pm (whilst previewing the 8 am shift start)
    - Lastly, drag a meal activity onto the shift at noon. The shift should look like the following: 
    ![Regular Shift](/images/regularShift.jpg)
9. Lastly, click on the agent's tab and then add your agents to this work plan. Once you've done that, validate and save your work plan
![Add Agents to Work Plan](/images/addAgentsToWorkPlan.jpg)

        
        
