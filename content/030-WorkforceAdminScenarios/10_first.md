---
title: "Adding the Option for Agents to Shift Trade"
chapter: false
weight: 10
---
### Shift Trade Overview
We will begin our first admin scenario by allowing shift trading in our environemnt. Shift trades enable agents to trade complete shifts with other agents. You can choose whether to allow automatic approval for trade requests or queue them for administrator review. You can also set a minimum time between shift trade approval and shift start. For example, if the minimum is 24 hours, then agents cannot request a trade with a shift 10 hours from now. However, they can request a trade between shifts at least 24 hours from now. 

Let's begin by learning a few key concepts of shift trading before setting things up in our Genesys Cloud CX org.

### Matching criteria requirements
As Workforce Management Administrations we can configure agent matching criteria for trade requests. If the trade meets a constraint, then choose how to process the request. Matching requirements include: 

-- Queue membership
-- Assigned language 
-- Assigned skills
-- Ability to handle the same planning groups 

### Shift trade rules
Shift trade rules include the following constraints, which you can set to allow, deny, or send for administrator review:

-- Shift trades with unequal paid hours
-- Shift trades that are one-sided
-- Shift trades that result in minimum weekly paid time violations
-- Shift trades that result in maximum weekly paid time violations

For shift trade rules, if you enable automatic review and set a constraint to allow, then the system can approve the trade. If you disable automatic review, then the system sends the request to an administrator for review.

