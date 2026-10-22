# Customer-Support-Complaint-Analysis-Project
- [Title](#Customer-Support-Complaint-Analysis-Project)
- [Description](#Project-Description)
- [Overview](#Business-Overview)
- [Aim](#Aim-of-Project)
- [Dataset](#Dataset-Description)
- [Data-Cleaning](#Data-Processing)
- [Data-Processing](#Data-Processing)
- [Analysis and Visualization](#Analysis-and-Visualization)
- [Insight and Reccomendation](#Insight-and-Reccomendation)
- -[Conclusion](#Conclusion)


  ## Project Description
This project evaluates the effectiveness of customer service in resolving customer complaints and maintaining customer satisfaction through data analysis and visualization. It uses the Customer Support Ticket Dataset by Suraj to examine complaint categories, contact channels, resolution status, and customer satisfaction ratings. By examining these indicators, the project seeks to identify weaknesses in complaint management, understand patterns in customer complaints, and provide recommendations for improving service quality and customer experience.
The project uses Microsoft Excel for data inspection and preparation and Microsoft Power BI to analyze the data and develop an interactive Customer Support Performance Dashboard.
### Business Overview
Customer support compliant provide a formal record of customer interactions and contain useful information for evaluating service performance. Analyzing these records allows an organization to identify common complaints, monitor resolution outcomes, compare communication channels, and assess customer satisfaction.This project applies data analytics to customer support complaints records to evaluate how effectively complaints are handled. The resulting dashboard can help managers monitor support performance, identify areas requiring improvement, and make informed decisions about resource allocation, staff training, and complaint management.
The project is relevant to customer service managers, support agents, operations teams, and business decision-makers seeking to improve customer experience and service efficiency.
### Aim of Project
- To evaluate the effectiveness of the customer service department in resolving customer complaints.
- To assess the relationship between complaint resolution and customer satisfaction.
- To identify the most common customer complaints and examine their distribution.
- To investigate the quality and timeliness of customer service responses.
- To examine customer complaint patterns across different communication channels.
- To analyze customer satisfaction across complaint categories and contact channels.
- To evaluate complaint resolution outcomes and identify potential inefficiencies.
- To provide recommendations for improving customer service performance and customer satisfaction.
### Data Description
The project uses the Customer Support Ticket Dataset by Suraj, Renamed as Customer Support Compliant Dataset.The dataset contains customer ID, complaint category, contact channel, resolution status, customer satisfaction rating, response time, resolution time, priority level, date or month and 8,000 total complaints. It provides a practical opportunity to apply analytical techniques to real world sales data and derive actionable business insights.
### Data Cleaning and Processess
Data cleaning was an important stage of the project because the original dataset contained incomplete entries and inconsistencies that could affect the reliability of the analysis. According to the project document, missing values were present particularly in response time, resolution time, and resolution status. Variations in formatting and duplicate records also required attention. Microsoft Excel and Power Query in Power BI were used as the relevant tools for preparing the data.
#### Data Cleaning
- The dataset was checked for missing or blank entries, particularly in response time, resolution time, and resolution status. These fields are important for evaluating complaint-handling efficiency.
- Duplicate records were identified as a data quality concern. Duplicate checks help prevent the same complaint from being counted more than once and producing misleading complaint totals.
- Inconsistent text entries and formatting were reviewed to ensure that equivalent categories were represented consistently.
- Date fields, numerical ratings, response times, and resolution times were stored in appropriate data types.
- Resolution status entries were reviewed to ensure that complaints were classified consistently.
- The cleaned dataset was checked for invalid dates, implausible response times, invalid satisfaction ratings, and inconsistencies between complaint counts and calculated indicators.
#### Data Processing
- The customer support ticket dataset was imported into the analytical environment. The data fields were reviewed to understand their structure and determine their relevance to the project objectives.
- The dataset was prepared by standardizing categories, checking data types, and handling missing or inconsistent entries. Power Query provided functionality for these transformation tasks.
- Complaint records were grouped by complaint category, contact channel, and resolution status to calculate complaint distributions and compare support outcomes. Customer satisfaction ratings were aggregated to obtain average satisfaction scores across complaint categories and contact channels.
- The dashboard uses four key performance indicators: Total complaints, average customer satisfaction, resolved complaints, resolution rate.
- Complaint dates were used to organize customer satisfaction results by month. This supports the monthly customer satisfaction trend chart and helps identify changes in performance over the reporting period.
- Slicers were included for resolution status, complaint category, and priority level. These allow users to filter the displayed results and examine specific groups of complaints.
### Analysis and Visualization
Data analysis was performed to examine complaint patterns, customer satisfaction, and resolution outcomes. Power BI was used to present the results through KPI cards, bar charts, column charts, doughnut charts, and a line chart.
To present these insights, the dashboard utilizez:
- KPI cards to display Total Complaints, Average Customer Satisfaction, Resolved Complaints and Resolution Rate.
- Horizontal bar chart to visualize complaint by category.
- Column chart to analys average customer satisfaction by complaint category.
- to analyse customer staisfaction by contact channel.
- Doughnut chart to visualize complaint by contact chanel.
- Doughnut chart to visualize complaint resolution status.
- Line chart to analyse monthly customer satisfaction trend.
- Slicers for resolution status, complaint category and priority level.
  
<img width="1740" height="697" alt="Screenshot 2026-10-22 155924" src="https://github.com/user-attachments/assets/e2d93717-f6cc-4b33-8781-009aae20dcaa" />

### Insight and Recommendation
The analysis of the Customer Support Performance Dashboard produced the following key findings and based on the findings and the objectives of the project, the following recommendations are proposed.
#### Insight
- We discovered High volume of customer complaints
- We discovered Moderate customer satisfaction
- We discovered Reported resolution rate requires attention
- We discovered Complaint volumes vary by category
- We discovered Satisfaction varies across communication channels
- We discovered Resolution status provides insight into workflow
- We discovered Customer satisfaction changes over time
The most important findings are the high volume of complaints, an average satisfaction score of 2.99, and a reported resolution rate of 32.70%. Together, these indicators establish a basis for reviewing complaint-handling efficiency and identifying opportunities to improve customer service.
#### Recommendations
- The organization should establish clear targets for complaint resolution and monitor outstanding cases regularly. Complaints that exceed the expected resolution period should be escalated to the appropriate personnel.
- Refund requests and technical issues should be investigated to determine their underlying causes. Where recurring problems are identified, the organization should consider improving product information, troubleshooting support, refund procedures, and customer communication.
- Refund requests and technical issues should be investigated to determine their underlying causes. Where recurring problems are identified, the organization should consider improving product information, troubleshooting support, refund procedures, and customer communication.
- Customer satisfaction should be monitored consistently. Support teams should review negative feedback, identify recurring service problems, and provide appropriate training in communication, problem-solving, and complaint handling.
- The organization should compare complaint volume, satisfaction ratings, and resolution performance across chat, email, phone, and social media. Resource allocation decisions should be based on these combined measures rather than complaint volume alone.
- A structured follow-up process should be established for pending and open complaints. Customers should receive appropriate updates, while overdue cases should be reviewed to reduce unnecessary delays.
- Management should review the monthly satisfaction trend and investigate noticeable declines. This can help identify periods requiring additional support or a review of service procedures.
- The organization should maintain accurate and complete complaint records. Missing response times, resolution times, and status values should be minimized through improved data entry and validation procedures.
- Management should establish realistic targets for complaint resolution and customer satisfaction after validating the baseline figures. Progress should be reviewed periodically to determine whether implemented improvements are producing the desired results.
### Conclusion
This project evaluated the effectiveness of customer service in resolving customer complaints and maintaining customer satisfaction through data analysis and visualization.Using the Customer Support Ticket Dataset by Suraj, Microsoft Excel, and Power BI, the project examined complaint categories, contact channels, resolution status, and customer satisfaction trends. The resulting dashboard provides an overview of customer support performance through key performance indicators and interactive visualizations.
The dashboard displays approximately 8,000 complaints, an average customer satisfaction score of 2.99, approximately 3,000 resolved complaints, and a resolution rate of 32.70%. These results highlight the importance of monitoring complaint resolution, maintaining accurate support records, and investigating factors that may affect customer satisfaction.The project also demonstrates how visualizations can help management identify common complaint categories, compare customer experiences across communication channels, and monitor changes in satisfaction over time.
In conclusion, data analytics and visualization provide useful tools for evaluating customer service performance and supporting informed business decisions. By improving complaint-handling procedures, monitoring outstanding cases, maintaining data quality, and responding to customer feedback, organizations can work toward more efficient support operations and better customer experiences.However, further analysis of the underlying dataset would be necessary to establish the causes of the observed performance levels and determine the effectiveness of specific improvement measures.

