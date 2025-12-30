📌 Project Overview

The goal of this project was to simulate a Trust & Safety Audit for Google Ads (AdWords). In this scenario, I acted as a T&S Analyst reviewing 100 ad submissions to detect policy violations, mitigate risks from "bad actors," and ensure platform integrity.

This project demonstrates how data-driven decisions can be used to scale policy enforcement and protect users from harmful or misleading content.

🛠️ Tech Stack & Skills

Tool: Google Sheets / Microsoft Excel

Analysis: Pivot Tables, Data Validation, Logical Functions (IF, AND, OR), SUBTOTAL for dynamic filtering.

Visualization: Interactive Slicers, Trend Charts, Conditional Formatting (Risk Heatmaps).

Domain Knowledge: Policy Enforcement (Misrepresentation, Healthcare, Dangerous Products, Counterfeit Goods).

🔍 The Workflow (Step-by-Step)
1. Data Sanitization & Risk Scoring :
   
I created a dataset of 100 ads across various industries. To prioritize the workload, I developed a Risk Scoring System (1-10) based on the severity of the violation.

Formula used: =IF(G2>=8, "🔴 Critical", IF(G2>=5, "🟡 Warning", "🟢 Safe"))

2. Interactive Dashboard Construction:
   
To provide a bird's-eye view of platform health, I built a dashboard that updates in real-time.

Pivot Tables: Aggregated data to show which industries have the highest violation rates.

Filters: Added interactive filters for Industry and Ad Status to allow for granular investigation.

3. Dynamic Metrics (The "Final Polish"):
   
Using the SUBTOTAL function, I ensured that the Compliance Rate and Total Ad Count update automatically when filters are applied.

Compliance Formula: =COUNTIF(Status_Range, "Approved") / COUNTA(Total_Ads_Range)

📈 Key Insights & Findings:

High-Risk Zones: The Finance and Health industries showed a 40% higher risk score compared to Retail, primarily due to "Get Rich Quick" schemes and unauthorized pharmaceutical sales.

Most Common Violation: Misrepresentation accounted for the largest volume of disapproved ads (approx. 35%).

Efficiency Gain: By using the Risk Heatmap, the time to identify "Critical" threats was reduced by visually highlighting scores above 8.

🚀 How to Use This Project:

Open the .xlsx or Google Sheets link.

Use the Slicers at the top to filter by "Finance" or "Retail."

Observe how the Charts and Total Metrics update to reflect the specific risks of that industry.
