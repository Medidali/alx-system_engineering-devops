0x19. Postmortem
DevOps
SysAdmin
 By: Sylvain Kalache
 Weight: 1
 Project will start Feb 12, 2024 4:00 AM, must end by Feb 19, 2024 4:00 AM
 Manual QA review must be done (request it when you are done with the project)
Concepts
For this project, we expect you to look at this concept:

On-call
Background Context


Any software system will eventually fail, and that failure can come stem from a wide range of possible factors: bugs, traffic spikes, security issues, hardware failures, natural disasters, human 
A postmortem is a tool widely used in the tech industry. After any outage, the team(s) in charge of the system will write a summary that has 2 main goals:

To provide the rest of the s employees easy access to information detailing the cause of the outage. Often outages can have a huge impact on a company, so managers and executives have to understand what happened and how it will impact their work.
And to ensure that the root cause(s) of the outage has been discovered and that measures are taken to make sure it will be fixed.
Resources
Read or watch:

Incident Report, also referred to as a Postmortem
The importance of an incident postmortem process
What is an Incident Postmortem?
More Info
Manual QA Review
It is your responsibility to request a review for your postmortem from a peer before the s deadline. If no peers have been reviewed, you should request a review from a TA or staff member.

Tasks
0. My first postmortem
mandatory


Using one of the web stack debugging project issue or an outage you have personally face, write a postmortem. Most of you will never have faced an outage, so just get creative and invent your own :)

Requirements:

Issue Summary (that is often what executives will read) must contain:
duration of the outage with start and end times (including timezone)
what was the impact (what service was down/slow? What were user experiencing? How many % of the users were affected?)
what was the root cause
Timeline (format bullet point, format: time - keep it short, 1 or 2 sentences) must contain:

when was the issue detected
how was the issue detected (monitoring alert, an engineer noticed something, a customer complainedprojectcompanyerror