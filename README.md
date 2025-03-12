# AtliQ Mart Supply Chain Analysis
As part of the October month codebaiscs resume challenge, I have performed data analysis and designed a dashboard in Power BI



Live Dashboard [(https://app.powerbi.com/view?r=eyJrIjoiYWZiYzk5ZTktMmJkMi00YjQwLTkwZDYtNjJmZjdkMTg1NDI3IiwidCI6IjdhZmI5ZTIyLTkzMDgtNDE4Ni04ZTI5LWVhMjMxZmYzYmFmNyIsImMiOjN9)]


## Problem statement

AtliQ Mart, a burgeoning FMCG manufacturer based in Gujarat, India, is looking to expand its operations beyond its current footprint in Surat, Ahmedabad, and Vadodara to other metro and tier 1 cities within the next two years.

However, the company is currently grappling with a significant issue: several key customers have chosen not to renew their annual contracts due to service-related issues. There have been instances where essential products were either not delivered on time or were not delivered in full over an extended period, leading to dissatisfaction among customers.

To address this problem before embarking on further expansion, the management has tasked the supply chain analytics team with closely monitoring the 'On Time' and 'In Full' delivery service levels for all customers on a daily basis. This approach aims to enable swift identification and rectification of any service-related issues.

The supply chain team has opted for a standardized method to measure service levels. They will assess the 'On-Time Delivery (OT) %', 'In-Full Delivery (IF) %', and 'On-Time In-Full (OTIF) %' of customer orders daily against the respective target service levels set for each customer.


### Task List

Peter Pandey, the newly hired data analyst at Atliq Mart's supply chain team, has been briefed on the task during the stakeholder business review meeting. As Peter, I'm enthusiastic about building the dashboard and fulfilling the assigned tasks:

1. Create metrics: 
   - On-time Delivery (OT) %
   - In-full Delivery (IF) %
   - On-time In-full (OTIF) %

2. Develop a dashboard according to stakeholders' requirements from the meeting.

3. Generate additional insights:
   - Trend analysis over time
   - Geographical analysis
   - Customer segmentation analysis
   - Root cause analysis
   - Predictive modeling

These insights aim to provide a deeper understanding of delivery service performance and support data-driven decisions for enhancing customer satisfaction and business growth.


## Data Model 

<p align="center">
  <img width="842" alt="Screenshot 2024-03-15 at 2 00 23 PM" src="https://github.com/SpurthyRam/PowerBi-Project-1/assets/68895924/0d1ac0a9-58da-4abb-8703-cede99f75538">
</p>

## Dashboard 

<p align="center">
  <img width="341" alt="Screenshot 2024-03-15 at 1 58 49 PM" src="https://github.com/SpurthyRam/PowerBi-Project-1/assets/68895924/0d609579-dde4-4567-a297-7f4053d06b3e">
</p>

## Some Major Insights 

- All the Key Metrics (OT%, IF%, OTIF%) are far behind the target
- On an average, orders are delayed 0.42 days from the agreed date of delivery
- Lotus Mart, Coolblue, Acclaimed stores have the highest orders as well as delayed the most to deliver the products on time 
  - Is it because we are not estimating the right delivery date?
  - Is it because we are receiving more orders than expected?
- Ghee, curd and butter products are most delayed to deliver. 
- There is no noticeable improvements in any of the key metrics in the last few months
- There is a huge gap in IF% for most of the customers. Is it because of less production?
