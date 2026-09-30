# R-tiny-project-
README
Project Title
Analysis of Student Attendance and Placement
Author
Piyush supekar
2505101270174
Date: 2026-09-10
Project Overview
This project uses R Programming to analyze student attendance and placement data. It demonstrates CSV data importing, data preprocessing, statistical analysis, visualization, and interpretation.
Dataset
The project analyzes 20 student records containing:
Student ID
Name
Gender
Attendance
CGPA
Aptitude Score
Placement Status
Package (LPA)
Data Import
The CSV dataset is imported using:
placement_data <- read.csv("placement_attendance.csv")
Data Preprocessing
Dataset contains 20 observations.
All columns contain 0 missing values.
Duplicate records: 0.
Statistical Analysis
Key results:
Mean Attendance: 82.30%
Median Attendance: 87.00%
Minimum Attendance: 60%
Maximum Attendance: 97%
Standard Deviation of Attendance: 12.23
Mean CGPA: 7.95
Mean Aptitude Score: 75.50
Placement Rate: 70%
Average package of placed students: 7.05 LPA
Highest package: 9.0 LPA (Student 110)
Visualizations
The project includes:
Placement Status Bar Chart
Student Placement Distribution Pie Chart
Student Attendance Bar Chart
Package of Placed Students Bar Chart
Attendance vs CGPA Scatter Plot
Correlation
The correlation between attendance and CGPA is 0.986, showing a positive association in this dataset.
Interpretation
In this sample, placed students have higher average attendance and CGPA than not-placed students. This indicates an association, but it does not prove that attendance alone causes placement.
Conclusion
The project demonstrates the use of R Programming for CSV data importing, preprocessing, statistical analysis, and visualization. The results suggest that higher attendance and CGPA are associated with better placement outcomes in this sample. Placement decisions, however, depend on several factors.
R Functions Used
Function
Purpose
read.csv()
Import CSV data
head()
Display first records
summary()
Statistical summary
str()
Show data structure
is.na()
Check missing values
duplicated()
Check duplicates
mean()
Calculate average
median()
Calculate median
min()/max()
Find minimum/maximum
sd()
Standard deviation
table()
Count categories
barplot()
Create bar charts
pie()
Create pie charts
plot()
Create scatter plots
aggregate()
Grouped statistical analysis
