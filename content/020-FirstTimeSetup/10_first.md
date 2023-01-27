---
title: "Business Units and Management Units"
chapter: false
weight: 10
---

## Business Units vs Management Units

Business Units and Management Units allow you to organize your teams and agents that you'll ultimately be scheduling. A Business Unit can have more than one Management Unit that rolls up to it. For example, in our scenario today, our Business Unit will be North America and we will have two Management Units that roll up into it; Sales and Customer Service. When creating Business Units you should consider the following: 
- Business Units contain one or more management units, planning groups and service goal templates
- Schedules and forecasts are generated at the business unit level
- Business units use divisions to separate resources
    - This means you can configure business units for different parts of the organization that do not share interactions and should be kept separate from a permissions perspective
- Do not configure agents who handle the same queue into different business units

Key considerations for management units are the following: 
- Let's you partition agents into logical groups with similar adherence, time off and shift trading rules
- Set permissions independently by management unit
    - In our example above, you could make it so the leader of the Sales management unit cannot view or edit schedules for the Customer Service management unit
- Allows you to view and edit schedules for a subset of the overall business unit schedule

### Make a Business Unit
1. In Genesys Cloud CX, navigate to Admin > Business Units (under the Workforce Management container)
2. Click to add a new business unit and name it "North America"

These are the only two steps to complete for making a business unit as part of our workshop. If you want to explore the additional settings when making a business unit, view this resource article. https://help.mypurecloud.com/articles/add-a-business-unit/

### Create 2 Management Units
1. Click on the "Management Units" section under Configuration
2. Ensure that you are under the "North America" business unit you created in the previous step by choosing it in the drop-down on the top right
![Create MU](/images/createMU.jpg)
3. Click add and create a management unit named "Customer Service"
4. Repeat step 3 but name this management unit "Sales"

We will be returning to some of the settings for management units later in the workshop, but if you want to read about all the options, view this resource article. https://help.mypurecloud.com/articles/create-new-management-unit/ 

### Add Agents to Management Units
Agents are assigned to a management unit. This allows Genesys Cloud to form teams or departments to group agents into for forecasting and scheduling. In our scenario today, we are going to focus on the Sales management unit that we just created. Follow these steps to add agents to the Sales management unit: 
1. Click on the "Agents" section under Configuration
2. Ensure that you are within the Sales management unit in the North America business unit
![Add Agents to MU](/images/addAgentstoMU.jpg)
3. Click add and then choose to add agents assigned to a specific queue. Search for one of the queues that you created earlier in the workshop (either "Existing Accounts" or "New Orders"). This will then add the agents in the queue to the management unit.
