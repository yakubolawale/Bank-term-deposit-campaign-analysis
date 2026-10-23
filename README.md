# Bank-term-deposit-campaign-analysis
An excel-based banking analytics project using Power Query, PivotTables and interactive dashboards to analyze bank term-deposit campaign, customer behavior, subscription patterns, and factors influencing term-deposit uptake.
﻿
# Project Overview
The Bank Term-Deposit Campaign Analysis is a business intelligence project developed using Microsoft Excel to evaluate the performance of a bank's direct marketing campaign. The project transforms customer contact and campaign data into actionable insights to understand subscription behaviour, identify customer segments with higher conversion rates, and support more effective marketing decisions.
The analysis focuses on campaign conversion, customer demographics, occupational groups, contact channels, contact timing, and outcomes of previous marketing campaigns.

# 🎯 Business Problem Statement
Banks use direct marketing campaigns to encourage customers to subscribe to term-deposit products. However, contacting customers without understanding their characteristics, preferences, and previous campaign responses can lead to inefficient marketing expenditure and low conversion rates.
The business needs to understand which customer groups are more likely to subscribe, which contact strategies perform better, and how previous campaign outcomes relate to current subscription behaviour.
This project uses Excel-based analysis and dashboard visualisation to support evidence-based campaign planning, improve customer targeting, and help marketing teams allocate resources more effectively.

# 📊 Project Objectives
The project aims to:
- Measure the overall performance of the term-deposit marketing campaign.
- Evaluate the number of customers contacted and the number who subscribed.
- Calculate the overall campaign conversion rate.
- Compare conversion rates across age groups and occupational categories.
- Examine subscription outcomes by contact month and contact method.
- Analyse the outcomes of previous marketing campaigns.
- Identify customer segments that may warrant further marketing investigation.
- Develop practical recommendations for improving campaign effectiveness.

# 📂 Dataset Description
The analysis uses the Bank Marketing dataset from the UCI Machine Learning Repository.
The dataset contains information about customers contacted during a bank's direct marketing campaign and whether they subscribed to a term deposit.
The dataset includes variables relating to:
- Customer demographics, including age and occupation.
- Marital status and education.
- Contact method and contact month.
- Previous campaign outcomes.
- Campaign contact history.
- Subscription outcome.
The dataset version associated with this analysis contains 4,521 customer records.
Dataset source: UCI Machine Learning Repository – Bank Marketing

Data note: The source dataset describes a bank marketing campaign conducted in Portugal. It is used here for educational and portfolio purposes and should not be interpreted as actual customer data from a Nigerian bank.

# 🛠 Tools and Technologies
- Microsoft Excel: Data analysis, KPI calculations, dashboard development, and reporting.
- Power Query: Data cleaning, transformation, and preparation for analysis.
- Excel PivotTables: Summarising campaign data and comparing subscription outcomes across customer segments.
- Excel Charts and Visualisations: Presenting campaign performance, conversion rates, and customer segment comparisons through an interactive dashboard.
- Data Storytelling: Translating analytical findings into practical business insights and marketing recommendations.

# 🔍 Methodology
The project follows a structured data analysis workflow.
1. Business Understanding
Defined the business problem around term-deposit subscription conversion and the efficient allocation of marketing resources.
2. Data Understanding
Reviewed the dataset structure, variables, customer characteristics, campaign contact information, and subscription outcomes.
3. Data Cleaning and Transformation
Prepared the data for analysis by reviewing data quality, checking variable formats, and organising the fields required for reporting. Specific cleaning procedures should be documented according to the transformations actually performed.
4. Exploratory Data Analysis
Examined campaign responses across demographic groups, occupations, contact months, contact methods, and previous campaign outcomes.
5. KPI Development
Developed summary metrics to monitor campaign reach, subscriptions, and conversion performance.
6. Dashboard Development
Created an interactive Excel dashboard to consolidate key metrics and visual comparisons into a single reporting interface.
7. Business Interpretation
Interpreted the displayed results to identify patterns that could inform future campaign targeting and marketing strategy.

# 📈 Dashboard Overview
The dashboard provides a consolidated view of the bank's term-deposit campaign performance.
![Bank Campaign.](Dashboard.png)

Campaign Performance KPIs
The dashboard displays the following headline metrics:
Customers Contacted: 4,521
Subscribers: 521
Overall Conversion Rate: 11.52%
Previous-Campaign Success: 64.34%, as displayed in the dashboard for the selected previous-campaign segment.
Conversion Rate by Job

Compares subscription conversion rates across occupational groups to identify differences in campaign response. These comparisons can help guide further investigation into which groups may respond more favourably to future campaigns.

# Conversion Rate by Age Band
Examines subscription conversion across age categories. The dashboard indicates that the 65-and-above group has the highest displayed conversion rate, at 37.3%. This result should be interpreted in the context of the number of customers contacted within that age group.

# Conversion Rate by Contact Month
Visualises changes in campaign conversion across contact months to investigate potential differences in response timing.

# Subscription Status by Contact Mode
Compares subscription outcomes across contact methods, including cellular, telephone, and unknown contact modes.

# Previous Campaign Outcome
Displays the distribution of previous campaign outcomes, including success, failure, other, and unknown categories, to support analysis of historical campaign engagement.

# 💡 Business Insights and Interpretation
The dashboard provides several findings for further business investigation:
- Campaign conversion: The dashboard reports 521 subscriptions from 4,521 customers contacted, with an overall conversion rate of 11.52%.
- Age-based differences: The displayed conversion rate for customers aged 65 and above is higher than that of the other age bands shown. The bank should investigate the size and characteristics of this group before changing its targeting strategy.
- Occupational differences: Conversion rates vary across occupational categories, suggesting that campaign response is not uniform across all customer groups.
- Contact timing: Monthly conversion patterns provide an opportunity to examine whether campaign timing is associated with differences in subscription response.
- Contact methods: Subscription outcomes differ across the displayed contact modes. However, a fair comparison should account for the number of customers contacted through each method.
- Previous campaign history: Historical campaign outcomes may provide useful context for customer segmentation and follow-up planning.
These observations describe patterns in the dashboard. They do not, by themselves, establish that age, occupation, contact timing, or contact method causes a customer to subscribe.

# 🎯 Strategic Recommendations
Based on the dashboard's analytical focus, the following actions are recommended for further evaluation:
- Improve customer targeting: Use observed differences in conversion rates to identify segments for controlled follow-up campaigns.
- Evaluate contact timing: Test campaign schedules across different periods and compare conversion rates using consistent definitions.
- Review contact-channel performance: Assess conversion alongside contact volume, campaign costs, and successful customer engagement.
- Use previous campaign history: Investigate whether customers with positive previous responses are more likely to subscribe again.
- Track campaign effectiveness: Monitor conversion rate, subscription volume, and marketing cost over time.
- Conduct controlled experiments: Compare alternative campaign approaches to determine whether proposed targeting or contact changes improve outcomes.
- Validate segment sizes: Review the number of customers within each age and occupational group before making significant resource-allocation decisions.

# 📌 Business Value
This project demonstrates how spreadsheet-based business intelligence can support marketing and customer acquisition decisions.
The analysis provides a framework for:
- Monitoring direct marketing campaign performance.
- Understanding differences in customer response.
- Comparing campaign outcomes across demographic and contact segments.
- Identifying areas for further marketing investigation.
- Supporting evidence-based campaign planning.
- Communicating results through a consolidated visual dashboard.

# 🧠 Skills Demonstrated
* Microsoft Excel
* Data Cleaning and Transformation
* Exploratory Data Analysis
* KPI Development
* Customer Segmentation
* Marketing Campaign Analysis
* Data Visualisation
* Dashboard Design
* Business Insight Development
* Data Storytelling
* Evidence-Based Decision-Making

⚠️ Limitations
The dashboard presents descriptive campaign analysis. Differences in conversion rates should not be interpreted as causal relationships.
Segment sizes, potential confounding factors, campaign costs, and statistical uncertainty should be assessed before making major operational decisions. The project does not claim to provide a validated predictive model unless one is developed and evaluated separately.

# 📚 Dataset Source and Acknowledgement
UCI Machine Learning Repository. Bank Marketing dataset.
https://archive.ics.uci.edu/dataset/222/bank+marketing
The dataset is used for educational, analytical, and portfolio demonstration purposes. The project does not represent an official analysis commissioned by the original bank.

# ✅ Conclusion
The Bank Term-Deposit Campaign Analysis demonstrates how Microsoft Excel can be used to transform marketing campaign data into meaningful business intelligence. By evaluating subscription conversion across customer demographics, occupational groups, contact methods, and campaign history, the project provides a foundation for more informed customer targeting and campaign evaluation.
The dashboard illustrates how data analysis and visual storytelling can help organisations understand campaign performance, identify opportunities for further investigation, and make better-informed marketing decisions.

# 👤 Author
Yakub Olawale Moshood
Statistician | Data Analyst | Business Intelligence Enthusiast
Email: yakubolawale576@gmail.com
LinkedIn: https://www.linkedin.com/in/olawale-yakub
GitHub: https://github.com/yakubolawale
