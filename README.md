# Project Performance Analysis for Scotland Homes UK 

## Table of contents

- [Project overview](#project-overview)
- [Data sources](#data-sources)
- [Tools](tools)
- [Data cleaning / Preparation](data-cleaning-Preparation)
- [Exploratory Data Analysis (EDA)](exploratory-Data-analysis-(EDA))
- [Data Analysis](data-analysis)
- [Results/Findings](Results-/Findings)
- [Recommendations](recommendations)
- [Limitations](limitations)
- [References](References)

  
## Project Overview

This Data Analysis project for Scotland Homes aims to provide insights into how project resources have been managed over the past four years across scotland. By analyzing various aspects of resource data, we seek to identify trends in budget allocations, enhance risk identification, and make data-driven recommendations for mitigation strategies. Ultimately, the goal is to improve overall productivity and project outcomes.
<img width="598" alt="Dashboard overview" src="https://github.com/user-attachments/assets/49ad35a7-c453-49ed-942d-09c8273233d0">
<img width="551" alt="Project Performance" src="https://github.com/user-attachments/assets/7c87a014-046d-4a8d-89fa-c57f32b70495">
<img width="558" alt="Issue cost summary" src="https://github.com/user-attachments/assets/7f9f5834-f713-4d93-9e07-f1d4bb6416f2">
<img width="551" alt="Risk Analysis" src="https://github.com/user-attachments/assets/723f30e5-f300-40fd-a14d-64515fbffb86">



## Data sources 

Project logs data: The primary dataset used for this analysis  is the 'Project_cost_summary.csv' containing detailed information about each project for 'Dalkeith','Lasswade'and 'Roslin'

## Tools

- Excel -Data cleaning
   - [Download Here](https://Microsoft.com)
- SQL Server -Data Analysis
- PowerBI - Data Visuslisation


### Data cleaning / Preparation

  In the innitial data preparation phase , I performed the following tasks
  1. Data loading and inspections,
  2. Handing missing values,
  3. Data cleaning and formatting.
 
### Exploratory Data Analysis (EDA)

EDA Invlolved exploring the project Logs data to answer key questions , such as 

- What is the overall project cost and progress ?
- The Risk analysis and mitigation progress ?
- Performance of each PN on project on costs savings?

## Data Analysis

Include some intresting code /features worked with

```SQL
SELECT* FROM PROJECT
WHERE PROJECT_ TITLE  = 'Dalkeith','Lasswade','Roslin'
```

### Results/Findings 

The analysis result are summerinsed as follows
1.The value of the Scotland Homes project has seen significant growth over the past four years, following government approval to build more affordable housing for mid-market rent.
2.The Gantt chart summarizes the progress of various projects, with team leaders and PMOs. It highlights that the Lasswade project, managed by Alexis, has been efficiently completed, consistently meeting deadlines thus giveng a tremedous cost save for the business.
3.The risk analysis reveals that the majority of issues encountered across all projects are technical in nature (41.71%), compared to the commercial and legal challenges faced during the previous financial year.

### Recommendations
Based on the analysis , I would recommend the following 
- Invest in the technical capability of the prokect ,by upgrading the technical tools as well as expertise of the project, and trainings to help reduce this issue
- A Proactive approach on risk management should be implemented which focuses on early detection, mitigation of technical risks, and regular technical audit that would identify potential issues before they arise.
- Increase the budget allocation and resources for technical support and improve the continuous efforts to streamline project completion.

### Limitations
Due to privacy concerns, the Health and Safety and RIBA Quality columns were excluded from the analysis, which has impacted the overall accuracy of the total budget and revenue conclusions. Despite a few outliers remaining after this omission, the analysis still reveals a positive correlation between the budget allocation and cost savings.

### References 
[Enterprise-wide information system for construction](https://www.bing.com/search?q=enterprise-wide+information+system+for+construction+%3A+a+document+based+approach+mohammed+arif*%2C+dennis+kulonda**%2C+charles+egbu***%2C+jack+s.+goulding****%2C+and+tahsin+toma*****+received+march+25%2C+2009%2Frevised+november+12%2C+2009%2Faccepted+may+7%2C+2010&gs_lcrp=EgZjaHJvbWUqBwgAEEUYwgMyBwgAEEUYwgMyBwgBEEUYwgMyBwgCEEUYwgMyBwgDEEUYwgMyBwgEEEUYwgMyBwgFEEUYwgMyBwgGEEUYwgMyBwgHEEUYwgPSAQoxMjA3MjZqMGo0qAIIsAIB&FORM=ANAB01&PC=HCTS)




  
