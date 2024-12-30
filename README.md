Loan Approval and Job Support Analysis
Table of Contents
Project Overview
Features
Technologies Used
Dataset Description
Installation and Setup
Dashboards and Visualizations
Results and Insights
Recommendations

----------------------------------------------------------------------------------------
1. Project Overview
This project analyzes loan approvals and their impact on job support 
across the United States. Using a dataset from 2010 to 2022, we explore:

Trends in loan approval amounts by business type and geography.
Job creation supported by loans across industries and states.
Correlations between loan approvals and economic growth indicators.
Interactive dashboards in Tableau provide insights for data-driven decision-making.

--------------------------------------------------------------------------------------------
2. Features
Loan Trends: Analyze loan approval amounts over time, across states, and by business type.
Job Support: Explore industries and locations supporting the most jobs.
Business Types: Compare loan approvals and job support for corporations, partnerships, 
and individual proprietorships.
Visual Insights: Dashboards visualize key trends with bar charts, bubble charts, 
and time-series graphs.

---------------------------------------------------------------------------------------------
3. Technologies Used
Tableau: For creating interactive dashboards and visualizations.
CSV Dataset: From SBA’s FOIA database.
PowerPoint: For summarizing insights into a presentation.

----------------------------------------------------------------------------------------------
4. Dataset Description
The dataset used is foia-504-fy2010-present-asof-220930.csv, containing:

Time Period: 2010–2022.
Fields:
Loan approval amount.
Business types (corporations, partnerships, individuals).
NAICS industry codes and descriptions.
State-level loan data and job support numbers.

------------------------------------------------------------------------------------------------
5. Installation and Setup
Pre-Requisites
-Install Tableau Desktop or Tableau Public (free version).
-Ensure you have the dataset (foia-504-fy2010-present-asof-220930.csv).
Steps to Run the Dashboards
-Clone this repository or download the project folder.
-Open the Tableau file (Final_Project.twb) in Tableau.
-Load the dataset when prompted.
-Interact with the dashboards to explore insights.

--------------------------------------------------------------------------------------------------
6. Dashboards and Visualizations

### 1. Loan Approval Analysis Dashboard**
- **Focus**: Trends in loan approvals by business type and geography.
- **Features**:
  - Treemap of loan approvals by business type.
  - Loan approval trends over time.
  - Geographic distribution of loan approvals.
  
![Loan Approval Analysis Dashboard](Images/Loan_Approval_Analysis_Dashboard.png)

---

### 2. Job Support and Impact Dashboard**
- **Focus**: Trends in job support by industries, states, and business types.
- **Features**:
  - Bubble chart showing top states by jobs supported.
  - Trends in job creation over time.
  - Top industries supporting jobs.

![Job Support and Impact Dashboard](Images/Job_Support_and_Impact_Dashboard.png)

---

### 3. Geographic Insights Dashboard**
- **Focus**: Insights on top states by loan approvals and jobs supported.
- **Features**:
  - Bar charts for loan approvals and job support by top states.
  - Map visualization of loan distribution by state.
  - Time-series analysis of job support trends.

![Geographic Insights Dashboard](Images/Geographic_Insights_Dashboard.png)


--------------------------------------------------------------------------------------------------
7. Results and Insights
Key Findings
Loan Approvals:
-Corporations dominate loan approvals, receiving $67 billion (93% of total approvals).
-Partnerships and individuals received significantly lower loan amounts ($2B and $3B, respectively).
-California leads in loan approvals with $15 billion, followed by Florida ($5B) and Texas ($4B).

Job Support:
-California supported 204,000 jobs, leading all states.
-Full-service restaurants and child day care services supported the most jobs 
(87,000 and 54,000 jobs, respectively).
-Corporations accounted for 93.35% of jobs supported.

Trends Over Time:
-Loan approvals peaked in 2012 at $7 billion and again in 2022 at $9 billion.
-Job support trends followed a similar trajectory, with peaks in 2012 and 2022.

-----------------------------------------------------------------------------------------------------
8. Recommendations
Based on the findings, here are actionable insights:

Focus on Corporations:
--Continue prioritizing corporations for loans as they support the majority of jobs and have 
high loan repayment reliability.

Industry-Specific Interventions:
--Target industries like child day care services and restaurants to enhance job creation in 
economically struggling states.

State-Level Focus:
--Strengthen loan programs in top-performing states (e.g., California, Florida) while incentivizing 
economic activity in underperforming states.

Monitor Loan Efficiency:
--Investigate states like Michigan that have high job support relative to lower loan approvals, 
identifying best practices for efficient loan utilization.

Policy Adjustments:
--Ensure startup and small business loan accessibility to balance support across all business types.
