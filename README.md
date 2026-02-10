# Editech-student-behavior-analysis
 Data cleaning and analysis of an EdTech learning dataset to understand course completion, drop-off rates, and learner feedback using Python and Pandas.
---
## Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Google Colab  

---

## Data Cleaning Steps
The following preprocessing steps were performed:
- Filled missing `course` values with **"Power BI"**
- Filled missing `enrollment_channel` with **"Unknown"**
- Filled missing `status` values with **"Unknown"**
- Imputed missing `completion_time_days` using **median per course**
- Imputed missing `feedback_score` using **mean per course**
- Removed duplicate records
- Verified data structure and null values using `info()` and `isnull()`

---

## Analysis Performed
### Key Metrics Calculated:
- **Drop-off Rate (%)**
  - Percentage of students who enrolled but did not complete the course
  - Calculated by course and enrollment channel

- **Average Completion Time**
  - Mean completion time (in days) per course

- **Average Feedback Score**
  - Mean feedback score by enrollment channel

---

## Key Insights Generated
- Identified courses with higher student drop-off rates
- Compared completion times across different courses
- Analyzed learner satisfaction based on enrollment channels
- Created a cleaned dataset ready for further visualization or reporting

---

## How to Run the Project
1. Upload the dataset to Google Colab  
2. Run the Python script / notebook step by step  
3. The cleaned CSV file will be generated automatically  

---

## Author
**Mrunal Khedekar**  
Aspiring Data Analyst / Data Science Professional  

---

## Skills Demonstrated
- Data Cleaning & Preprocessing  
- Handling Missing Values  
- GroupBy Aggregations  
- Business-focused Metrics (Drop-off Rate)  
- Python & Pandas Proficiency  
