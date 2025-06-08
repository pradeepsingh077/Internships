# 🎓 UptoSkills: College Data Analysis and Visualization using Power BI
A full-fledged data gathering, preprocessing, and visualization project to analyze Indian colleges and course availability across districts using tools like Python, Excel, and Power BI. The data is sourced from leading college search engines like Shiksha, CollegeDunia, and others.

# 📚 Table of Contents
Project Objective

Data Sources

Tools & Tech Stack

Data Collection Process

Data Consolidation

Power BI Visualization

Insights & Analysis

How to Use the Project

Future Scope

References & Links

About the Author

# 🎯 Project Objective
The objective of this project is to:

Aggregate and analyze publicly available data on colleges, courses, fees, and reviews

Assist students, institutions, and job seekers in comparing educational opportunities across India

Provide a centralized Power BI dashboard to compare districts and institutions on a variety of parameters

# 🔎 Data Sources
The following education portals were scraped or referenced for structured and semi-structured data:

Website Purpose
Shiksha.com College details, courses, entrance exams, fees, city/district-wise filters

CollegeDunia Reviews, top courses, category tags (Engineering, MBA, etc.)

Careers360 Rankings, NIRF tags, placements, rating

GetMyUni Admission cutoff, scholarship, student feedback

IndiaEducation.net General educational data

# 🛠️ Tools & Tech Stack
Tool Purpose

Excel/CSV/Google Sheets Initial formatting and combination

Power BI Final interactive dashboard and insights

DAX Custom measures and KPIs

# 🔄 Data Collection Process
✅ Fields Collected
Field Name Description

College Name: Standardized across portals

Course Offered: E.g., B.Tech, MBA, BCA, M.Com

Location: City, Distinct, State

Ownership: Government or Private College

Type: Girls,Boys, Co-Educational

Qualification: define which type of degree such as ITI, Diploma, UG(UnderGraduate) & PG(Post-Graduate)

# 🗃️ Data Consolidation
District-wise scraped files (sikkim.csv, puducherry.csv, tripura.csv, etc.) were merged into one master file:

Unified into master_college_dataset.csv

Duplicates removed across portals

Districts validated against India Districts List

Saved as .xlsx, .csv for Power BI integration

# 📊 Power BI Visualization
📁 PBIX File:
🔗 UptoSkills Power BI Dashboard

# 📌 Key Dashboard Sections
Page Visuals Included
State & District Summary Maps, slicers, tree map
Course Availability Course vs District Matrix
Ownership Piechart, bar chart
Type slicers, bar chart, columns chart
Filter Page Interactive filtering (district, course, range)

📂 How to Use the Project
🔧 Installation Steps:

 https://github.com/pradeepsingh077/uptoskills.git
 
Open UptoSkills Final.pbix in Power BI Desktop

Load data from the /data folder or update source path

Use filters and slicers to explore

# 🌱 Future Scope
Automate scraping with schedule and update sync

Connect with live APIs or government portals

Integrate user reviews sentiment using NLP

Extend dashboard to support career guidance path recommendation

Export reports for offline use (PDF, PPT)

# 📎 References & Links
✅ Project Resources
🔗 Power BI Dashboard (PBIX)

📄 Sample Data Sheet (Excel & Google Sheets)


#👤 About the Author
Pradeep Singh

🎓 Final Year B.Tech | 📍 Noida

📊 SQL • Power BI • Python • Data Scraping

📧 pradeepsingh.psk610@gmail.com

🔗 LinkedIn Profile: https://www.linkedin.com/in/pradeep-singh-585931230/

🔗 GitHub Profile: https://github.com/pradeepsingh077
