# Reducing the cost of support

- Role: Data Engineer / Analyst
- Situation: Ad-Hoc request to assist a Support organisation data project.
- Goal: Identify the opportuniy for feature development & direct escalation to reduce the total cost of support.
- Action: Build a dashboard where support cost (time, volume, CSAT) is broken down by team and type of requirement (tools or skills)
- Result: Provide the list of opportunities to reduce the total cost of support with priority

### TL;DR

Support management is looking to reduce cost of tickets by identifying repetitive process for escalated support, and investing to remove them. 

An example of this would be to identify and build an UI for merchant if there is a process with substancial volume that requires internal tool to complete.

### 1. Preliminary research 

1) Available resouces - found following resources that could be used to build the dashboard:

- Arbitrary list of ideas for feature development
- Current reporting tool (two dashboards requiring copy paste, not ideal)

2) The metrics we need for the analysis is mostly missing from the current reporting tool, so the following needs to be built from scratch:

- Time spent on ticket
  - Net (Interaction)
  - Gross (Time to close)
- CSAT

3) Furthermore, current classification system may lack in uniformity and granularity. Investigation and ad hoc classification may be necessary. This would require an interview with various specialists from respective teams.

4) The current classification was split into two tier (last 30 days )

### 2. Hypotheses building & Solution Proposal

1) To reduce the development cost, I will combine the two reports to create a master table, then use the built in report and analysis visiualisation to analyse the goal.

2) Investigate building the metrics
- Since most times do not track the actual time spent on each ticket, we can only use the escalation & close time stamp to calcurate a proxy.
- Similary CSAT will be available for tickets where the merchants have responded, we would need to use precaution when using this metric.

3) Project will start with a team most likely to have internal tools. We believe humans are more expensive than **the tools**. Despite the initial cost of adding UI for the tools the long term cost saving would outweigh the **direct escalation**, as it would still require the specialist to solve the ticket.

4) This was a measure no longer applicable and can be dropped.

### 4. Solution assessment



### 5. Result & Learnings

