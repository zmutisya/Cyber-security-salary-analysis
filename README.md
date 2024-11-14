# CYBER SECURITY SALARY ANALYSIS
This project is focused on cybersecurity salary analysis. The dataset provides valuable insights in compensation within the cybersecurity industry. It captures various factors such as work experience, employment type, job titles, salary in USD, employee residence, remote work ratio, company location and company size. Analyzing this data will help to understand salary distribution across different experience levels, identify the most lucrative role, compare compensation between different employment types etc.
## Tools
MySQL: For database management and storage
DBeaver: For interacting with MySQL database
Python : For Data processing
Jupyter Notebook: For interactive coding and data analysis and visualization.
Pandas: For data cleaning and manipulation
Numpy: For data manipulation and statistical analysis
Matplotlib & Seaborn for data visualization
Plotly: For creating interactive and informative plots
Datetime: For managing time based data 
Tableau: For creating visualization and interactive dashboard
## Dataset
The dataset has 11 columns and 1247 rows.
* Work Year: The number of experience years in the cybersecurity industry
* Experience level: The experience level of the cybersecurity professional
* Employment type: Type of employment i.e Full time, Part time, contract or freelance
* Job title: The job position of the cybersecurity professional
* Salary in USD: Salary amount converted in USD for standardization
* Employee residence: The country or region where the employee resides
* Remote ratio: The proportion of remote work allowed in the cybersecurity position
* Company location: The location where the company is located
* Company size: The size of the employing company i.e small, medium or large
To access the dataset click [here](https://github.com/zmutisya/Cyber-security-salary-analysis/blob/master/cybersecurity_salaries.csv)
## Project Objectives
1. Find average salary for different cybersecurity roles: What is the average salary for different cybersecurity roles? Which job titles have the highest and lowest average salaries?
2. Find salary distribution by experience level: How does salary vary across different experience levels? Are there any significant differences in salaries based on experience?
3. Salary comparison by employment type: What is the average salary for different employment types (full-time, part-time, contract)? Are there significant salary differences between employment types?
4. Salary trends over time: How have cybersecurity salaries changed over the years? Are there any noticeable trends or patterns in compensation within the cybersecurity field?
5. Salary analysis by company size: Is there a correlation between company size and cybersecurity salaries? Do larger companies tend to offer higher salaries in the cybersecurity field?
## EDA
Exploratory Data Analysis was conducted to uncover the dataset patterns, relationship, trends and anomalies. 
## Data Analysis and Visualization
#### **1.What is the average salary for different cybersecurity roles?**
Analyzing salary data to determine the average salaries for different cybersecurity roles. This information provides businesses with a valuable benchmark for their compensation packages. It also helps businesses stay competitive in attracting and retaining top talents in the industry.
#### Highest paid Cybersecurity role
![average](https://github.com/user-attachments/assets/2d807677-0d2c-485e-8d44-5ff4331f1432)
#### These were the findings from the analysis
![highest paid](https://github.com/user-attachments/assets/2e188163-273f-4292-ac2c-edd78a76c8d7)
* The Application Security Architect and Staff Security Engineer positions lead in compensation, indicating high demand for expertise in application security and staff-level engineering.
* The roles focusing on application security, software security, and compliance management tend to offer competitive salaries, reflecting the high value placed on these specializations within cybersecurity.
* The roles like IAM Engineer and Head of Information Security, while still well-paid, are on the lower end of this top-tier range, suggesting that these positions may be more common and therefore offer less premium pay than highly specialized roles.
#### Least paid Cybersecurity role
![least paid](https://github.com/user-attachments/assets/8fa6d7f9-f391-4e08-9437-ae51c79d7fd0)
#### These were the findings from the analysis
![bottom](https://github.com/user-attachments/assets/be57ad9f-4c45-4cc6-be45-bb86dfbc87c5)
* Lower salaries are generally associated with roles that focus on vulnerability research, threat hunting, and intelligence analysis, suggesting these positions may be more accessible as entry-level roles in cybersecurity.
* Some roles, such as Threat Intelligence Response Analyst and Staff Security Engineer, appear in both high and low salary lists, which could indicate large salary ranges within these roles depending on experience, seniority, and industry demand.
* Roles with Engineer titles, such as Software Security Engineer and Staff Security Engineer, tend to command higher salaries even within the bottom 10 list. This indicates that general trend of higher compensation for engineering roles in cybersecurity.
#### **2.What is the salary distribution by experience level?**
Analyzing salary salary distribution by experience level within the cybersecurity field can provide businesses with valuable insights into the correlation between years of experience and compensation. This analysis guides decisions regarding career advancement, promotion pathways, and the development of competitive salary structures within the organization.
![distribution](https://github.com/user-attachments/assets/fcc2a1c9-45ba-4843-9beb-ab49e7dfa507)
These were the findings
![dist](https://github.com/user-attachments/assets/b19234ef-9c5f-4232-a6d7-4ff444af071b)
* The salaries for entry level positions are concentrated in a relatively narrow range, with a median around $100,000. There are some outliers with higher salaries, but the majority fall within this range.
* The mid level salaries show a wider distribution compared to entry-level. The median is around $200,000, and there are both lower and higher outliers.
* The executive level salaries have a significant spread. The median is around $400,000, but there are outliers both below and above this range.
* The senior level salaries also have a wide distribution, with a median around $350,000. There are outliers at both ends.
#### **3.Salary comparison by employment type**
Conducting salary comparison analysis by employment type can help companies ensure fair and competitive compensation practices. This in return can help in attracting and retaining top talent, allocating budgets effectively, complying with legal requirements, benchmark against industry standards and enhance employee satisfaction.
![Comparison](https://github.com/user-attachments/assets/c9d75078-415e-4d7c-a8b3-d59548c73473)
These were the findings
![comparison plot](https://github.com/user-attachments/assets/0d2a603b-4e95-461a-8dee-0bcf9fbe1cf8)
* Full-time employment positions in cybersecurity have the highest average salary, reaching approximately $120,000 USD. This is likely due to the stability, benefits, and potential for career growth associated with full-time roles.
* Both contract and freelance positions have lower average salaries compared to full-time employment. This could be due to factors like project-based nature, lack of benefits, and the need for self-management in these roles.
* Part-time positions in cybersecurity have the lowest average salary, around $50,000 USD. This is likely due to the reduced workload and potential for fewer benefits compared to full time roles.
#### **4.Salary analysis by company type**
This analysis will help understand how compensation structures vary across organizations of different scales. The analysis can help the businesses assess if their pay offerings are competitive relative to their size, resources, and market position. It can also inform decisions about attracting and retaining talent, optimizing salary budgets, ensuring equitable compensation practices and aligning with industry standards.
![company size](https://github.com/user-attachments/assets/42a9733a-edfc-4008-927b-c5119443c755)
These were the findings
![c size](https://github.com/user-attachments/assets/7cbc81bd-271f-4e0e-b149-a3f365f3169d)
* The medium-sized companies in the cybersecurity industry offer the highest average salaries, reaching approximately $120,000 USD. This could be attributed to factors like a balance between resources and flexibility, potentially higher growth opportunities and a focus on emerging technologies in these companies.
* The large companies in the cybersecurity industry offer slightly lower average salaries compared to medium-sized companies which is around $115,000 USD. While they might have more resources and established structures, the potential for individual growth and contribution might be comparatively lower in larger organizations.
* The small companies in the cybersecurity industry offer the lowest average salaries at around $80,000 USD. This could be due to limited resources, smaller budgets, and potentially fewer opportunities for career advancement in smaller organizations.
#### **5.Salary trends over time**
By analyzing salary data over time will help identify trends and patterns in compensation within the cybersecurity industry. This analysis can help businesses anticipate changes in salary expectations and adjust their recruitment and retention strategies accordingly.
![trends](https://github.com/user-attachments/assets/fb3762e0-e7ca-4f79-97c6-7124b81e030d)
These are the findings
![trends overtime](https://github.com/user-attachments/assets/5662d7bc-40e5-4525-a98e-1b37e30add34)
* There is a clear upward trend in average salaries in the cybersecurity industry from 2020 to 2022. This indicates that salaries have been steadily increasing over this period.
* The most notable increase in salary occurred between 2021 and 2022. This suggests that there might have been significant factors contributing to this jump, such as increased demand for cybersecurity professionals, advancements in technology, or heightened awareness of cybersecurity threats.
  
