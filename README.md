# Call-Center-Data-Analysis-Project-Report-in-Power-BI
In this project, I analyzed call center data to generate insights and display KPIs in Power BI desktop.
<img width="955" alt="image" src="https://github.com/Shafic2023/Call-Center-Data-Analysis-in-Power-BI/assets/134142256/b210883f-e4f3-4a8e-acd2-eb4fee60b940">



## Introduction
This project aims to analyze the performance of a call center using historical data to create insightful visuals in Power BI. By examining various metrics such as call handling times, resolution rates, and customer satisfaction, we seek to identify areas for improvement and enhance the overall efficiency of the call center operations.

## Problem Statement
The primary challenge faced by the call center is optimizing its operational efficiency and improving customer satisfaction. Key performance indicators (KPIs) such as speed of answer, resolution rates, and average talk duration need to be closely monitored and analyzed to identify bottlenecks and areas requiring improvement.

![image](https://github.com/Shafic2023/Call-Center-Data-Analysis-in-Power-BI/assets/134142256/d62d7894-12b8-4f03-9ccd-1eaac7f42f80)

## About the Dataset
 A copy of the datset is available in the repository files.The dataset includes the following fields:
- **Call ID**: A unique identifier for each call.
- **Call Center Agent**: The agent who handled the call.
- **Date**: The date the call was made.
- **Time**: The time the call was made.
- **Topic**: The topic of the call.
- **Answered (Y/N)**: Indicates whether the call was answered.
- **Resolved (Y/N)**: Indicates whether the issue was resolved.
- **Speed of Answer (seconds)**: The time taken to answer the call.
- **Average Talk Duration (seconds)**: The duration of the conversation.
- **Satisfaction**: The customer's satisfaction rating.

## Data Preparation

The data has been cleaned using Microsoft Power Query Editor which comes together with Power BI, Data Analysis Expressions (DAX) has also been utilised in generating measures, new columns and tables necessary for visualizations.

1. **Data Cleaning**: Remove any duplicate entries and handle missing values.
2. **Data Transformation**: Convert date and time fields to appropriate formats and calculate additionaly (e.g., response time).
3. **Data Integration**: Combine data from multiple sources if required.
4. **Data Loading**: Import the cleaned and transformed dataset into Power BI.

## Analysis
### Key Performance Indicators

The management seeks to understand the below KPIs
* Possible KPIs include (to get you started, but not limited to):
* Overall customer satisfaction
* Overall calls answered/abandoned
* Calls by time
* Average speed of answer
* Agent’s performance quadrant -> average handle time (talk duration) vs calls answered

1. **Call Answer Rate**: The percentage of calls answered.
2. **Resolution Rate**: The percentage of calls that were resolved.
3. **Average Speed of Answer**: The average time taken to answer calls.
4. **Average Talk Duration**: The average duration of calls.
5. **Customer Satisfaction**: Average satisfaction rating.

### Visualizations
1. **Call Volume Over Time**: A line chart showing the number of calls over different periods (daily, weekly, monthly).
2. **Agent Performance**: A bar chart comparing the performance of different agents based on KPIs.
3. **Resolution Rates by Topic**: A stacked bar chart showing resolution rates for different call topics.
4. **Average Speed of Answer and Talk Duration**: Scatter plots to identify any correlations between these metrics and customer satisfaction.
5. **Customer Satisfaction Trends**: A line chart showing changes in customer satisfaction over time.

### Insights
1. **High-Volume Periods**: Identification of peak times and days for call volume.
2. **Agent Efficiency**: Agents who are performing well and those who may need additional training.
3. **Topic-Specific Issues**: Topics that frequently have unresolved calls, indicating potential areas for process improvement.
4. **Satisfaction Correlations**: How speed of answer and talk duration impact customer satisfaction.

## Findings
1. **Call Volume Trends**: The highest call volumes occur on Mondays and during lunch hours.
2. **Agent Performance**: Certain agents consistently resolve more calls and have higher satisfaction ratings.
3. **Topic Analysis**: Calls regarding billing issues have the lowest resolution rates.
4. **Customer Satisfaction**: Faster response times correlate with higher customer satisfaction.

## Recommendations
1. **Staffing Adjustments**: Increase staffing during peak times to reduce wait times and improve customer satisfaction.
2. **Training Programs**: Implement targeted training for agents, especially those handling billing issues, to improve resolution rates.
3. **Process Improvements**: Review and streamline processes for handling common issues to reduce average talk duration and improve resolution rates.
4. **Ongoing Monitoring**: Continuously monitor KPIs using the Power BI dashboard to quickly identify and address any emerging issues.

By implementing these recommendations, the call center can improve its operational efficiency and enhance the overall customer experience. The Power BI dashboard will serve as a valuable tool for ongoing performance monitoring and decision-making.

---

This project report outlines the process of analyzing call center data and creating actionable insights using Power BI. Each section of the report is designed to provide a comprehensive overview of the analysis, findings, and recommendations for improving call center performance.
