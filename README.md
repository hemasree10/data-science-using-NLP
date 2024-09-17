# data-science-using-NLP

City of Los Angeles Job Descriptions Analysis
#Project Overview
This project focuses on helping the City of Los Angeles analyze and structure its job descriptions. The goal is to streamline the city’s hiring process by organizing job postings, identifying potentially biased language, and enhancing the diversity and quality of the applicant pool.

#Problem Statement
By July 2020, approximately one-third of the City of Los Angeles' 50,000 employees were eligible to retire. This presented a significant challenge to the city's hiring system, and there was a need for efficient management of job postings and promotions.

#Project Goals
Data Structuring: Convert unstructured job postings from plain text files into a structured CSV format for better analysis.
Bias Identification: Detect language in the job descriptions that may negatively impact the diversity of the applicant pool.
Promotion Tracking: Facilitate tracking of available promotions within the city’s various job classes.

#Dataset
Source: The dataset includes 683 plain-text job postings provided by the City of Los Angeles.
Contents: Each job description file contains details such as:
Job Title
Job Class Number
Requirements
Job Duties
Selection Criteria
Salary Information
Open and Deadline Dates


#Process
->Loading and Preprocessing:
  Load and process the job bulletins and related documents.
  Convert job postings into a structured format (CSV).
->Data Analysis:
  Analyze common job sectors, salary distributions, and selection criteria.
  Identify language that could introduce bias in job postings.
->Visualization:
  Generate visual insights on salary distributions, job sectors, and opportunities across different job classes.
  
#Tools & Technologies
Natural Language Processing (NLP): For text analysis and bias detection.
Python: Used for data processing, analysis, and visualization.
Matplotlib: For generating graphical representations of salary distributions and other statistics.
Pandas: For data manipulation and structuring.
CSV: Output format for the structured job data.

#Key Insights
A clearer view of job sectors and salary distribution across the city.
Identified selection criteria commonly used across job postings.
Potentially biased language was flagged to improve job postings' inclusivity.

#Conclusion
This project provides the City of Los Angeles with tools to better manage its job postings and promotions, while ensuring job descriptions are free of biases that may hinder the diversity of its workforce. The results help streamline the recruitment process, making it easier to fill the vacancies left by retiring employees.
