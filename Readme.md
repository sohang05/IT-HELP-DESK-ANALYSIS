# INTRODUCTION

In the FP20 Analytics Challenge, we are going to analyse IT service ticket data to build our own operational dashboards to measure metrics over time. This dashboard will help the organization identify automation candidates, optimize usage, and reduce costs.


## BRIEF:-

Within this challenge, we are presented with a reliable dataset that shows the IT tickets data and Agents’ profiles for a fictitious company that we work for. We will provide our actionable insight into our organization trends, usage patterns, systems behaviours, service level agreement etc. It will help the IT department to stay up to date with industry developments.

Briefly, there are some modifications to be made for this analysis, and we will define the metrics based on above needs:

__In the Tickets Table__
* The client requires the canvas settings of the PBI report to be H:1080 - W: 1920
* The client would like columns Severity and Priority to be split into 2 columns, creating an ID and classification columns. Example Severity Key column = 0 and Severity Type = Unclassified.
* The Average Resolution time is 4.5 days. The Client would like to create a new column where if the Resolution time is above 3.5 days = "Outside SLA" and if it is below "Within SLA". This will allow the client to push for all calls to stay within the limit by targeting these calls and agents.

**In the IT Agents Table**
* Column Full Name to be split into 2 columns Name and Last Name, where last name is missing to be obtained from the email address column.
* Name and Last name columns must be Capitalize first words and trimmed.
* Year/Month/Date of birth must be in one Column - data type Date.
* The client would also like to know the Age of the Agents from the Agents' DOB to 31/12/2020.
