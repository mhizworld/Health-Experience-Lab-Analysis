# Health-Experience-Lab-Analysis
Title: Improving Patient Appointment Attendance and Health Care Support Using Data
Introduction
This analysis aims to examine the health connect experience lab dataset and observe the patterns of appointment outcomes. The dataset contains relevant information such as: appointment ID, Patients Demographics, Booking Information, Appointment Outcome etc. which will aid in generating actionable insights on patients missing scheduled appointments, factors associated with appointment no-shows and cancellations and help hospital administrators to make good business decisions to curb them.
 
Dataset Overview
The health connect lab dataset is a synthetic dataset containing fictional and anonymized information. Along with it was a health connect dictionary which provides an explanation and interpretation of the variables contained in the main health connect dataset. It is a CSV file which contains 5000 rows and 18 columns.
 
Data Summary
Attribute                                          Description
Total rows                                        5000
Total columns                                  18
Numeric data                                    7
Categorical data                               11
File format                                       CSV
 
Variables
·      Appointment ID
·      Patient ID
·      Gender
·      Age
·      Age group
·      Appointment type
·      Booking date
·      Appointment date
·      Appointment day
·      Appointment time
·      Booking lead days
·      Previous appointments
·      Previous no shows
·      Reminder sent
·      Reminder channel
·      Distance to clinic
·      Waiting time minutes
·      Appointment outcome
 
Data Quality Assessment
Blanks: Distance to clinic has 90 blank spaces; waiting time has 60. Both variables will be filled using its median for the sake of data accuracy.
Duplicate: There is no duplicate values in the dataset.
Data Type: Each variables has the appropriate data type: text, integer, decimal, date etc.
Consistency: The dataset is not consistent as each variables –both numerical and categorical- has quite different values.
         
                                       Methodology
1. Data Collection
The dataset used for this analysis is the Health Connect Experience Lab dataset, containing appointment-level records including appointment type, patient gender, patient age, booking date, appointment date, distance to clinic, and appointment outcome (attended, canceled, no-show).
2. Data Cleaning and Preparation
The dataset would be imported into Power Query, where it would be reviewed for missing values, duplicate records, and inconsistent formatting. Data types will be reviewed and aligned with its appropriate variable.
3. Data Modeling
A structured data model would be built in Power BI, with appointment records as the central fact table linked to supporting dimension tables (appointment type, patient demographics, date). Relationships would be established to enable filtering and cross-analysis across appointment outcomes and other variables.
4. KPI and Measure Development
Key performance indicators would be defined using DAX, including Total Appointments, Attendance Rate, Cancellation Rate, No-Show Rate, Completion Rate, Average Booking Lead Time, and Average Distance to Clinic. These measures would be designed to allow comparison across categorical breakdowns (appointment type, gender, age group) and over time.
5. Exploratory and Comparative Analysis
Attendance-related rates would be compared across appointment type, gender, and age group to identify which categories would show the highest and lowest attendance. Appointment volume would be analyzed over time to identify trends and patterns. Booking lead time and distance to clinic would each be analyzed against appointment outcome to assess their relationship with no-shows and cancellations.
 6. Reporting and Recommendations
Findings would be visualized in an interactive Power BI dashboard, and a written report would be compiled summarizing the key insights. Based on the factors most strongly associated with no-shows and cancellations, practical recommendations would be proposed to reduce missed and canceled appointments.
 
Objectives
At the end of this analysis, the following will be achieved:
·      Identify performance gaps across appointment types.
·      Access demographic patterns in attendance.
·      Monitor appointment volume trends over time.
·      Evaluate the effect of distance to clinic on attendance.
·      Reduce no-show and cancellation rate.
·      Evaluate booking lead time as a predicator of no-shows/cancelations.
 
 
                          Key Performance Indicators
·      Total appointments
·      Attendance rate
·      Cancellation rate
·      No-show rate
·      Average booking lead time
·      Average distance to clinic
 
 
                              Business Questions
·      Which appointment type has the highest and lowest attendance rate?
·      Does attendance vary by gender?
·      Does attendance vary by age group?
·      What is the trend in appointment volume over time?
·      How does booking lead time correlate with no-shows and cancellation?
·      How does distance to the clinic correlate with attendance?
·      What recommendation should be asserted to the hospital management?
 

                          Project Summary

This project proposes an analysis of appointment data from the Health Connect Experience Lab dataset, aimed at understanding patterns in patient attendance, cancellations, and no-shows. The analysis will examine how factors such as appointment type, patient demographics (gender and age group), booking lead time, and distance to clinic relate to appointment outcomes.

The primary objective is to identify which factors are most strongly associated with missed or canceled appointments, in order to provide data-driven recommendations for reducing no-show and cancellation rates. Key metrics to be tracked include Total Appointments, Attendance Rate, Cancellation Rate, No-Show Rate, and Completion Rate.
The analysis will involve data cleaning and preparation in Power Query, development of a structured data model in Power BI, and creation of KPIs and visualizations to support comparative and trend analysis. Findings will be presented through an interactive dashboard alongside a written report summarizing key insights and recommended interventions.
This project is expected to demonstrate practical skills in data cleaning, data modeling, DAX measure development, and dashboard design, while producing actionable insights relevant to appointment scheduling and patient attendance management.
