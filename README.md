Student Performance Factor Analysis using SQL Server & Power BI
📌 Project Overview

The Student Performance Factor Analysis System is a Business Intelligence and Data Analytics project developed to analyze the various factors influencing student academic performance. The project uses data transformation, SQL-based analysis, and interactive Power BI dashboards to generate meaningful insights from student data.

The system follows a complete analytics workflow, beginning with raw data collection and ending with insight-driven reporting. Academic, demographic, and environmental factors are analyzed to understand their impact on examination performance and support data-driven decision-making.

🎯 Objectives
Analyze student academic performance using data analytics techniques.
Identify factors affecting examination scores.
Perform data cleaning and transformation using Power Query.
Design a dimensional data model consisting of fact and dimension tables.
Store and manage structured data using Microsoft SQL Server.
Perform analytical operations using SQL queries.
Develop interactive dashboards using Microsoft Power BI.
Generate insights to support educational decision-making.
🛠️ Technology Stack
Technology	Purpose
Microsoft Excel	Initial Dataset Preparation
Power Query	Data Cleaning & Transformation
SQL Server	Database Storage & Management
SQL Server Management Studio (SSMS)	Query Execution
Power BI Desktop	Dashboard & Visualization
DAX	KPI and Measure Creation
📊 Project Workflow
Plain Text
Student Dataset (CSV)
│
▼
Power Query
(Data Transformation)
│
▼
SQL Server
(Database Storage)
│
▼
SQL Analytics
(Query Processing)
│
▼
Power BI
(Dashboards & KPIs)
│
▼
Reports, Insights &
Decision Support
🏗️ Data Model

The dataset was transformed into four logical tables:

DimStudent
Stud_ID
Gender
Department
Semester
DimAcademic
Stud_ID
Hours_Studied
Attendance
Motivation_Level
Teacher_Quality
Tutoring_Sessions
Access_to_Resources
Parental_Involvement
Learning_Disabilities
DimEnvironment
Stud_ID
Family_Income
Internet_Access
School_Type
Peer_Influence
Distance_from_Home
Extracurricular_Activities
Parental_Education_Level
FactStudentPerformance
Stud_ID
Previous_Scores
Sleep_Hours
Physical_Activity
Exam_Score
🔍 SQL Analysis

The project includes SQL-based analytical queries to answer business questions such as:

Which department has the highest average examination score?
How does attendance impact academic performance?
What is the relationship between motivation level and examination score?
Does family income influence academic outcomes?
How does internet access affect performance?
Which students are top performers?
How does performance vary across semesters?
📈 Power BI Dashboard
Dashboard Page 1 – Student Performance Overview

Features:

Total Students KPI
Average Exam Score KPI
Average Attendance KPI
Average Study Hours KPI
Department-wise Performance Analysis
Semester-wise Performance Analysis
Gender Distribution
Exam Score Distribution
Interactive Filters and Slicers
Dashboard Page 2 – Performance Driver Analysis

Features:

Attendance vs Exam Score Analysis
Study Hours vs Exam Score Analysis
Motivation Impact Analysis
Family Income Impact Analysis
Internet Access Analysis
Learning Disabilities Analysis
Correlation-Based Insights
📌 Key Insights
Students with higher attendance generally achieve higher examination scores.
Increased study hours positively influence academic performance.
Motivation plays a significant role in student success.
Internet accessibility contributes positively to learning outcomes.
Family income impacts educational performance.
Previous academic performance serves as a strong indicator of future results.
Interactive dashboards simplify educational data exploration and reporting.
✅ Features
End-to-End Analytics Pipeline
Power Query Data Transformation
SQL Server Integration
Star/Snowflake-like Data Modeling
SQL-Based Business Analysis
Interactive Power BI Dashboards
KPI Monitoring
Dynamic Filtering & Drill-Down Analysis
Educational Decision Support
🚀 Future Scope
Real-time data integration from Learning Management Systems (LMS)
Predictive analytics using Machine Learning
Student risk prediction models
Automated performance alerts
Cloud-based dashboard deployment
Mobile dashboard accessibility
Advanced educational analytics and forecasting
👨‍💻 Author

Shubham Kumar Jha
(32624000078)
 Master of Computer Application(MCA), 
 CDOE,
 GLA University, Mathura
