# Student-Tracking-Dashboard
### Executive Summary
This report outlines the development and insights gained from the Student Tracking Dashboard project at ExploreAI Academy. The project aimed to enhance the efficiency of monitoring student performance and identifying at-risk students. Key data, including test grades, predict grades, missed tests, failed tests, login duration, and hours spent online, was utilized to build a predictive model using K-Means clustering.

### Insights Gained
#### Cohort Analysis
![cohort_2](https://github.com/AndisiweJ/Student-Tracking-Dashboard/assets/107894108/ce53281c-4d3e-4c37-86aa-9b803178204e)

- Cohort Growth: In the year 2022, 11 cohorts were conducted, with data science being the most popular program, constituting over 86% of admissions.
- Study Modes: Full-time mode had the lowest student admissions, emphasizing the diverse study modes offered by Explore AI.

#### Student Progress Tracking
![student_1](https://github.com/AndisiweJ/Student-Tracking-Dashboard/assets/107894108/f3b7d926-89f4-42f8-b9c5-eab54646419a)

- Challenges of Scale: With 11 cohorts in a year, manual tracking becomes challenging, emphasizing the need for an autonomous and flexible student tracking system.
- Addressing Dropouts: A small percentage of enrolled students dropped out. The goal is to reduce this number by identifying at-risk students early on and providing support.

#### Correlation Analysis

Positive Correlations:
- Logged in duration and total logins have a strong positive correlation (0.79), suggesting students who log in more tend to spend longer hours online.
- Average grade and total logins exhibit a strong positive correlation, indicating higher engagement may lead to better test performance.

#### High vs. Low Performing Students
![image](https://github.com/AndisiweJ/Student-Tracking-Dashboard/assets/107894108/4b68ff7c-113c-4152-8eca-4127fc6c828e)
![image (1)](https://github.com/AndisiweJ/Student-Tracking-Dashboard/assets/107894108/be410ab3-2e71-439d-9602-576e801063bf)
![image (2)](https://github.com/AndisiweJ/Student-Tracking-Dashboard/assets/107894108/5b7a0f52-7261-4858-9c6c-2a970821bc59)
Patterns Observed:
- High-performing students had higher predict grades, spent more time online, and had higher login frequency.
- Low-performing students exhibited lower duration and grades.

## Project Description
### Objective
The primary objective of the Student Tracking Dashboard project is to streamline the monitoring of student performance and enhance the identification of at-risk students within ExploreAI Academy.

### Goals
- Streamline Administrative Processes:
- Automate and centralize student tracking to simplify administrative tasks, reducing manual data entry and analysis.
#### Enhance Student Support:
- Provide timely notifications and targeted support to at-risk students, promoting academic success and overall well-being.
#### Improve Reporting:
- Generate comprehensive reports offering a detailed overview of student performance, aiding decision-making processes and ensuring transparency.
#### Deliverables
- The project includes the development of specific views in the dashboard, such as Cohort View, Student View, and At-Risk View. Additionally, there is a focus on data science and data engineering components for ongoing data collection and processing.

## Model Building Process
### Data Preprocessing
- Removed missing values, scaled features, and converted categorical variables to numerical.
- Merged relevant tables for a consolidated dataset.

### K-Means Clustering Model
- Utilized K-Means clustering for predicting at-risk students.
- Trained the model on key features: test grades, predict grades, missed tests, failed tests, login duration, and hours spent online.

### Continuous Monitoring and Refinement
- Periodically retrain the model as new data becomes available.
- Refine the model based on feedback and performance evaluation.

### Conclusion
The Student Tracking Dashboard is expected to have a profound impact on ExploreAI Academy's ability to manage its growing student body effectively. By empowering educators and administrators with enhanced tools for monitoring student progress, the project aims to foster a more productive and successful learning environment.

