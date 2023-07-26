# Project Title : Ayushman_Bharat_Healthcare_Claim_Analysis

# Problem Description:

Ayushman Bharat is National Health Protection Scheme, which will cover over 10 crore poor and vulnerable families (approximately 50 crore beneficiaries) providing coverage upto 5 lakh rupees per family per year for secondary and tertiary care hospitalization. Ayushman Bharat - National Health Protection Mission will subsume the on-going centrally sponsored schemes - Rashtriya Swasthya Bima Yojana (RSBY) and the Senior Citizen Health Insurance Scheme (SCHIS).
Below problem statement we have analyst in this project:
1. Checking case workflows on different claim status.
2. Bringing an analysis report card  on family id, gender and patient's home district.
3. Finding the doctor name who all are handled more cases with respect to speciality.
4. Building a report of patient rush based on each hospital and district.
5. What is the maximum and minimum discharge time?
6. Patient admission count based on different time period.
7. What is the minimum and maximum time taken for claim settle?
8. Expressing an observation on paid amount for different hospital based on each district.
9. Checking patient's pay any additional amount or not for their treatement apart from insurance claim.
10. Minimum, maximum and average treatement charge analysis.
11. Monthly investment amount per month and district.
12. Treatement charge based on different procedure.


# OBJECTIVE:

This dataset contain 5 months 15 days information from 1st january to 15th june 2023 about medical insurance claim from variours insurance organization through ayushman bharat scheme in Jharkhand. In this project, we can gain several insights related to healthcare claims. Here are some potential insights we can extract:

Case Number: In the provided dataset, the "Case Number" refers to a unique identifier assigned to each individual healthcare claim case. It is a reference number or code that helps in identifying and tracking specific claims throughout the claims processing workflow. The Case Number serves as a unique identifier for a particular claim and is used to reference and retrieve information related to that claim.

Family id : It is a reference number that helps link multiple individuals who are part of the same family or have a common insurance policy. The Family ID enables the tracking and management of claims and other relevant information related to the insurance coverage of the associated family members.

Gender: It refers to the categorization of individuals based on their biological sex. It indicates the gender identity of the patients involved in the healthcare claims.

Patient's Home District : It indicates the geographic location or district of the patient's primary residence. This information helps in identifying the patient's locality or region for healthcare administrative and logistical purposes.

Claim Status: We can analyze the status of claims and understand the distribution of different claim statuses, such as approved, rejected, or pending. This insight can help identify bottlenecks and areas for improvement in the claims processing workflow.

Speciality : In the provided dataset, "Speciality" refers to the medical specialization or field of expertise related to the healthcare treatment or procedure associated with each claim. It indicates the specific area of medicine that the healthcare provider or medical practitioner specializes in, based on the type of treatment provided to the patient.

treating_doc_name: The "treating_doc_name" field contains the name of the doctor or healthcare provider who is primarily responsible for managing the patient's treatment during their hospitalization or medical care. This information helps in identifying and tracking the healthcare provider involved in the patient's treatment for each specific claim case.

Admission Data : In the given dataset, "Admission Date" refers to the date when the patient was admitted to the hospital or healthcare facility for medical treatment or care related to the specific healthcare claim. It indicates the exact date on which the patient's hospitalization or medical treatment began for the claim in question.

Discharge Date: In the provided dataset, "Discharge Date" refers to the date when the patient was discharged from the hospital or healthcare facility after receiving medical treatment or care related to the specific healthcare claim. It indicates the exact date on which the patient's hospitalization or medical treatment ended for the claim in question.

Approval and Rejection Patterns: We can identify patterns in pre-authorization approval and rejection rates. This information can help in understanding the criteria used for approval or rejection and identify any inconsistencies or areas for improvement in the decision-making process.

Claim Amount Analysis: Analyzing the claim amounts paid by insurance companies can provide insights into the average cost of different medical procedures or treatments. This information can be useful for cost analysis, budgeting, and negotiating contracts with healthcare providers.

Hospital and District Analysis: By examining the data related to hospitals and districts, We can gain insights into the distribution of claims across different healthcare facilities and geographic areas. This analysis can help identify patterns, resource utilization, and healthcare access disparities.

Processing Time: Analyzing the time taken for claim processing, from submission to payment, can provide insights into the efficiency of the claims processing system. This analysis can help identify any delays or areas where process improvements can be made to expedite claims processing.


These insights can support decision-making processes for healthcare administrators, insurance companies, policymakers, and other stakeholders involved in healthcare claims management. It can help optimize workflows, identify areas for improvement, and enhance the overall efficiency and effectiveness of the claims processing system.

# APPROACH:

The approach of this project for data analysis involves the following steps:

Data Understanding: Start by understanding the structure and content of the healthcare claims dataset. Identify the columns, data types, and potential data issues. Gain insights into the meaning of each column and the relationships between them.

Data Cleaning: Preprocess the dataset to handle missing values, data inconsistencies, and any formatting issues. Clean and transform the data to make it suitable for analysis.

Exploratory Data Analysis (EDA): Perform exploratory data analysis to gain initial insights into the data using numpy and panda libraries. Visualize the distribution of claim amounts, the frequency of medical procedures, and other relevant information help of matplotlib and seaborn libraries. Identify patterns and correlations between variables.

Claim Patterns Analysis: Analyze claim patterns to identify trends in claim approvals, rejections, and the most common medical procedures claimed. Look for any recurring patterns or outliers.

Assess Claim Amounts: Analyze claim amounts to determine the average cost of different medical treatments and procedures. Perform statistical analysis to understand the variability in claim amounts.

Evaluate Claim Status: Analyze the claim status over time to identify any delays or inefficiencies in the claims processing workflow. Look for trends in claim processing times and identify potential bottlenecks.

Medical Specialties Analysis: Analyze the distribution of medical specialties in the dataset to understand which types of treatments and procedures are most commonly claimed.

Hospital and District Insights: Analyze data related to hospitals and districts to identify regional variations in claim patterns and healthcare utilization. Look for potential disparities in healthcare access.

Data-Driven Insights: Use the findings from the data analysis to provide data-driven insights and recommendations to stakeholders, such as healthcare administrators, insurance companies, and policymakers.

Optimization and Decision-Making: Use the insights to optimize the claims processing workflow, improve decision-making, and enhance the overall efficiency of healthcare claims management.

Communication and Reporting: Present the results of the data analysis in a clear and concise manner using visualizations and reports to facilitate communication with stakeholders.

By following this approach, the project aims to extract valuable information from the healthcare claims dataset and provide actionable insights to enhance the claims management process and support better healthcare service delivery.

# Result: 
![Capture1](https://github.com/SrvPioneer/Ayushman_Bharat_Healthcare_Claim_Analysis/assets/93809665/f6c792dc-a286-488e-8125-323441690b66)

* Above pie chart clearly expressed that 72.52% claim has been paid, 0.03% claim has been cancelled, 9.74% has been approved, 2.16% claim has been under process, 11.42% claim has been yet to be initiated, 2.39% claim has been under query, 1.74% claim has been rejected.

![Capture2](https://github.com/SrvPioneer/Ayushman_Bharat_Healthcare_Claim_Analysis/assets/93809665/ce0c33e5-91b1-4c7f-b5bf-101ab97dafc8)

* More than one time insurance claim raised family number 22754, claim settle number 18594 and percentage 81.72 through ayushman
  bharat scheme from various insurance organization.
  
 ![Capture3](https://github.com/SrvPioneer/Ayushman_Bharat_Healthcare_Claim_Analysis/assets/93809665/8c6427c6-dfdf-428b-b868-6ad13b2154df)

 * Above donut chart clrealy highlighted that most of female gender got benefit through this scheme around 56.4% and than male with 43.6% and transgender 0.002%.

![Capture4](https://github.com/SrvPioneer/Ayushman_Bharat_Healthcare_Claim_Analysis/assets/93809665/2e59622e-5df7-41a5-a0e8-121dc0998d58)

* After observed district I found that high number of cases are coming from Ranchi and low number of cases coming from Jamtara.

![Capture5](https://github.com/SrvPioneer/Ayushman_Bharat_Healthcare_Claim_Analysis/assets/93809665/b9d84aef-6165-49e9-8b71-462095e5f11d)

* Above table display top 10 doctor name who have handled more cases along with their spacility.

![Capture6](https://github.com/SrvPioneer/Ayushman_Bharat_Healthcare_Claim_Analysis/assets/93809665/704d2bf4-343f-4cbf-9f11-1623d91502a5)

* Above table express top 10 hospital name base on district attend maximum number of patient.

* After observation I found that maximum treatement time 130 days 15 hour and minimum 0 days.

![Capture7](https://github.com/SrvPioneer/Ayushman_Bharat_Healthcare_Claim_Analysis/assets/93809665/4d648679-0c62-4064-8c72-264c968db53c)

* Above observation express that maximum number of patient coming from March month and minimum from january month.

![Capture8](https://github.com/SrvPioneer/Ayushman_Bharat_Healthcare_Claim_Analysis/assets/93809665/a4b83149-f68d-450d-9721-dc32cbbda5ef)

* After analysis of patient admission based on different month and day, I can say that date of 13th is the highest patient count and day of 31st is low.

* After analysing claim history I found that maximum 101 days can be taken for claim settle and minimum same day.

* After analysing of difference between "Claim Paid Amount" and "Amount paid to Hospital", I found that minimum and maximum differnce is zero. It means that patient's not paid any aditional amount for their treatement without insurance claim.

* Minimum, maximum and average treatement charges are 2, 100000, 9334.

![Capture9](https://github.com/SrvPioneer/Ayushman_Bharat_Healthcare_Claim_Analysis/assets/93809665/913fa071-1853-4bd8-bd8c-8ccbac9c678a)

* Above analysis express about minimum, maximum and avegare treatement amount also, monthly tratement budget as per different district

![Capture10](https://github.com/SrvPioneer/Ayushman_Bharat_Healthcare_Claim_Analysis/assets/93809665/dd9e3615-f567-49bd-a7f4-c4d5b345e594)
  
* Above table clearly talk about top 10 procedure based on claim paid amount.

