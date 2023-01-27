---
title: "Service Goal Templates and Planning Groups"
chapter: false
weight: 20
---

## The Relationship between Service Goal Templates and Planning Groups
Service goal templates are templates that describe your organization's service goals. They get applied to one or more planning groups. Planning groups associate a queue, media type, language and skill set combination to a service goal template which you use for forecasting and scheduling. Let's look at an example. 

A business wants to answer 80% of its voice calls within 20 seconds. They create a service goal template specifying this service goal. They then create planning groups for all of the queue, language and skill set combinations those voice calls may have. Later on, they decide to start identifying certain callers are VIP members. They wish to answer 90% of the VIP members within 10 seconds. They create a new service goal template to reflect the service goal. They then have a new planning group tied to that service goal for the route paths that would signify the caller is a VIP member.

To read more about service goal template key principles, navigate here: https://help.mypurecloud.com/articles/service-goal-templates-key-principles/
To read more about planning group key principles, navigate here: https://help.mypurecloud.com/articles/planning-groups-key-principles/

### Create Service Goal Templates  
For today, our business handles two media types, voice and web messaging. It wishes to have the same service goals across all route paths for voice and the same for messaging. This means we only need two service goal templates; one for our voice calls and another for our web messenger interactions. Let's go ahead and create them. 
1. Under Configuration, click on "Service Goal Templates" 
2. Click to add a new service goal template
3. Name this first service goal template "Voice Basic"
4. You'll notice we can make the service goal templates based on service level, the average speed of answer, abandonment rate or a combination of those 3. For "Voice Basic", we just want our service level to be 80% of interactions answered within 20 seconds.
![Voice Basic](/images/voiceBasic.jpg)
5. Save "Voice Basic" and click to add another service goal template
6. Name this second service goal template "Messaging Basic"
7. For "Messaging Basic" we want the average speed of answer to be 10 seconds
![Messaging Basic](/images/messagingBasic.jpg)
8. Press save

### Create Planning Groups
Both the "Existing Accounts" and "New Orders" queues can handle voice calls but only the "Existing Accounts" queue handles web messenger interactions. The business currently isn't using any skilling or languages to route interactions either. Based on this information, we'll need to create 2 planning groups. Our first planning group, which will be for voice, will need to have 2 route paths, one for each queue. Our second planning group, which will be for messaging, will need to just have one route path since only one queue handles messaging. Let's get started. 
1. Under Configuration, click on "Planning Groups" 
2. Click to create a new planning group
3. Name this first planning group "Voice Path"
4. Click to associate your "Voice Basic" service goal template
5. Choose "Voice" as the media type
6. Click to add a new route path
7. Depending on your environment, you may need to choose the option to manually add route paths
8. First search for the "New Orders" queue and then select "none" for both skill and language options
![New Orders](/images/newOrdersRoutePath.jpg)
9. Press save and add new, then add another route path for the "Existing Accounts" queue (also with no skills or languages selected)
10. Your route path should look like this and it should say that all of the agents in your 2 queues match this planning group
![Voice Path](/images/voicePath.jpg)
11. Save that planning group and click to add a new one
12. Name this second planning group "Messaging Path"
13. Select the "Messaging Basic" service goal template and then change the media type to "Message" 
14. Click to add a new route path for the "Existing Accounts" queue with no skills or languages selected
15. This route path should look like this and all of the agents in your 2 queues should match this planning group
![Messaging Path](/images/messagingPath.jpg)
16. Press save

