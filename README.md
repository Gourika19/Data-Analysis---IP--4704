# Student Internship Success Analysis
### Author: Gourika  
## Project Overview

This project aims to analyze the relationship between various student attributes (academic performance, event participation, career aspirations, and more) and their success in securing internships. Given the competitive nature of the job market and the importance of creating strong resumes, the analysis focuses on the data of students who have participated in events like resume building, data visualization, and others.

## Problem Statement

Millions of students apply for internships and jobs each year, and resumes play a vital role in making the first impression. However, recruiters spend only 2-3 minutes on average reviewing each resume, and over 70% of resumes are rejected during initial screening. Therefore, it's crucial for students to prepare quality resumes to pass through this phase.

## Objective

To conduct a comprehensive analysis of our student interns, focusing on the relationships between:
- Academic performance (CGPA)
- Event participation
- Career aspirations
- Factors influencing success (e.g., Python experience, family income, leadership skills, etc.)

This analysis will help uncover insights into what factors most influence a student’s success in securing internships and their future career prospects.

## Dataset

The dataset contains the following attributes:
- **First Name**: Student's first name.
- **Email ID**: Student’s email address.
- **Quantity**: Number of events attended.
- **Events**: The event(s) the student participated in.
- **Attendee Status**: Attendance status at the event.
- **College Name**: College from which the student is graduating.
- **Year of Graduation**: Student’s expected graduation year.
- **City**: City of residence.
- **CGPA**: Cumulative Grade Point Average of the student.
- **Experience with Python (Months)**: Number of months of experience in Python.
- **Family Income**: Family income bracket.
- **Expected Salary**: The salary the student expects after graduation.
- **Leadership Skills**: Whether the student possesses leadership skills.

## Analysis Performed

### Key Insights:
1. **Average GPA of Students**: The average GPA (CGPA) of the students is approximately 8.04.
2. **Graduation Year Distribution**:
    - 2023: 1530 students
    - 2024: 1506 students
    - 2025: 1289 students
    - 2026: 554 students
3. **Python Experience Distribution**: Most students have 5 months of Python experience, followed by 3 months and 8 months.
4. **Family Income**: The average family income of the students is approximately 129,288 INR.
5. **Expected Salary**: A weak correlation was found between family income, GPA, Python experience, and expected salary, indicating that other factors may influence salary expectations.
6. **Event Participation**: The most popular events were "Art of Resume Building" and "Data Visualization using Power BI," with 470 and 450 students attending, respectively.
7. **Promotion Channel Effectiveness**: Whatsapp was the most effective channel for event promotion, bringing in over 3400 students.

## Tools & Libraries Used
- **Python**: Data manipulation and analysis
- **Pandas**: Data handling and cleaning
- **Matplotlib & Seaborn**: Data visualization
- **Jupyter Notebook**: Development environment

## Instructions for Running the Project

1. **Data Preparation**:
   - Ensure the dataset is properly formatted and cleaned using the provided cleaning functions.
   - Handle missing values and inconsistencies in the data, such as replacing missing event attendance and college names.

2. **Analysis**:
   - Use the analysis functions provided to generate insights into the dataset, such as calculating averages, identifying relationships between factors, and visualizing data distribution.

3. **Visualizations**:
   - Run the visualization functions to generate bar charts, scatter plots, and other graphs to gain insights into the data.

4. **Reporting**:
   - The final insights and graphs can be compiled into a report to present the analysis findings.

## Results and Conclusion

This analysis revealed that students with higher CGPAs and more experience in Python tend to have higher salary expectations. However, factors such as leadership skills and event participation also play significant roles in career success. Promotion channels like Whatsapp were the most effective in drawing participants to events, which highlights the importance of selecting the right communication strategies for student engagement.
