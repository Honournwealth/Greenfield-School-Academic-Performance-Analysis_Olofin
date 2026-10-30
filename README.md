# Greenfield School Results Analysis & Academic Performance Dashboard

## Project Overview

The **Greenfield School Results Analysis Project** is an end-to-end data analysis project completed using Microsoft Excel 2021. The project focuses on cleaning, analysing, and visualising students' academic results across three academic terms to help school management understand performance trends and make data-driven decisions.

The dataset contains examination records for **240 students across six class streams: JSS 1A, JSS 1B, JSS 2A, JSS 2B, JSS 3A, and JSS 3B**.

The project transforms raw academic records into meaningful insights through data cleaning, Excel formulas, class and subject analysis, student performance tracking, and an academic performance dashboard.

## Project Objectives

The main objectives of this project were to:

- Clean and prepare raw student examination data for analysis.
- Calculate students' total scores, averages, and grades.
- Rank students within their respective classes and terms.
- Compare academic performance across classes and terms.
- Identify the hardest and easiest subjects based on average scores.
- Analyse student improvement between First Term and Third Term.
- Identify students who may require additional academic support.
- Build a dashboard to communicate key findings and recommendations to school management.

## Tools and Technologies

- **Microsoft Excel 2021**
- Excel Tables and structured references
- Excel formulas and functions
- Data cleaning and validation
- Conditional formatting
- Data analysis and aggregation
- Charts and data visualisation
- Dashboard design and reporting

## Dataset Overview

The dataset contains student examination results for three academic terms.

| Dataset Attribute | Description |
|---|---|
| Total Students | 240 |
| Class Streams | 6 |
| Academic Terms | 3 |
| Subjects | 6 |
| Expected Records | 720 student-term records |

### Subjects Analysed

- Mathematics
- English
- Basic Science
- Social Studies
- Computer Studies
- Civic Education

Each student has a record for each academic term, allowing performance to be analysed at student, class, subject, and term levels.

## Repository Structure

```text
Greenfield-School-Results-Analysis/
│
├── README.md
│
├── Greenfield_School_Results_Analysis.xlsx
│
├── screenshots/
│   └── greenfield_dashboard.png
│
└── documentation/
    └── project_methodology.md
```

## Workbook Structure

The Excel workbook contains seven worksheets.

| Worksheet | Purpose |
|---|---|
| Result | Preserves the original raw examination data. |
| Cleaned Data | Contains the cleaned and prepared dataset used for analysis. |
| Class Summary | Summarises student counts, class averages, and pass rates by class and term. |
| Subjects | Analyses average scores across the six subjects. |
| Improvements | Compares student performance between First Term and Third Term. |
| At Risk | Identifies students whose Third Term averages are below the pass mark. |
| Summary | Presents the dashboard, key performance indicators, summary tables, and charts. |

## Data Cleaning and Preparation

The raw dataset required cleaning before meaningful analysis could be performed.

The data preparation process involved:

- Standardising class names and removing unwanted spaces.
- Ensuring gender values were consistently recorded as Male or Female.
- Converting numeric scores stored as text into proper numbers.
- Correcting scores above 100 where the extra-zero typing error was confirmed.
- Identifying and removing duplicate records based on Student ID and Term after cleaning.
- Preserving blank subject scores rather than replacing them with zero.
- Preparing a consistent dataset for calculations and analysis.

The original `Result` worksheet was retained, while the cleaning and analysis were performed in separate worksheets.

## Analysis and Methodology

### 1. Student Results Analysis

Calculated the total score, average score, and grade for each student-term record using Excel formulas.

The grading criteria were:

| Grade | Average Score |
|---|---:|
| A | 70 and above |
| B | 60–69 |
| C | 50–59 |
| D | 45–49 |
| E | 40–44 |
| F | Below 40 |

A student passes a term with an average score of **50 or above**.

### 2. Class Performance Analysis

The `Class Summary` worksheet compares the six class streams across First Term, Second Term, and Third Term.

The analysis includes:

- Number of students per class and term.
- Average class score.
- Number of students who passed.
- Pass rate by class and term.
- Identification of the best- and lowest-performing classes in Third Term.

### 3. Subject Analysis

The `Subjects` worksheet evaluates average performance across all six subjects.

The analysis helps identify subjects with relatively high or low average scores and highlights areas where additional teaching support may be beneficial.

### 4. Student Improvement Analysis

The `Improvements` worksheet compares each student's First Term average with their Third Term average.

The analysis calculates the change in average score and classifies performance trends to identify students who improved, declined, or remained unchanged.

It also supports the identification of the most improved students.

### 5. At-Risk Student Analysis

The `At Risk` worksheet identifies students whose Third Term average is below 50.

This analysis supports early identification of students who may need additional academic assistance, targeted revision, or closer performance monitoring.

### 6. Student Ranking

Student performance is compared using overall averages across the three terms.

The analysis supports identification of:

- The overall best-performing student.
- The student with the lowest overall average.
- The top three and bottom three students within the JSS 1, JSS 2, and JSS 3 groups.

## Dashboard Overview

The `Summary` worksheet contains a visual dashboard designed to present the school's academic performance at a glance.

### Key Performance Indicators

The dashboard currently highlights the following results:

| KPI | Result |
|---|---|
| Total Students | 240 |
| Third Term Pass Rate | 86% |
| Hardest Subject | Mathematics |
| Best Class — Third Term | JSS 3B |
| Lowest-Performing Class — Third Term | JSS 3A |
| Students at Risk | 34 |

### Dashboard Visualisations

**1. Class Average by Term**

Compares average scores across the six class streams to show differences in academic performance.

**2. Overall Average by Subject**

Displays average scores across the six subjects to identify relative academic strengths and areas requiring attention.

**3. Pass Rate by Class and Term**

Compares First Term, Second Term, and Third Term pass rates for each class.

### Dashboard Screenshot

![Greenfield School Academic Performance Dashboard](screenshots/greenfield_dashboard.png)

## Key Findings

Based on the current dashboard results:

- **Third Term pass rate was 86%.** This indicates that most students achieved the school's minimum pass mark.
- **JSS 3B was the best-performing class in Third Term**, based on the class performance analysis.
- **JSS 3A was the lowest-performing class in Third Term**, indicating a potential need for targeted academic support.
- **Mathematics recorded the lowest overall subject average of 55.41**, making it the subject requiring the greatest attention based on average scores.
- **34 students were identified as at risk** based on the dashboard's current risk calculation.

These findings provide a basis for further investigation into learning gaps, class performance differences, and opportunities to improve student outcomes.

## Recommendations

Based on the findings, the following actions are recommended:

1. **Improve Mathematics performance:** Review student performance in specific topics and provide targeted revision, practice exercises, and additional instructional support.
2. **Support underperforming classes:** Investigate the factors contributing to JSS 3A's lower performance and develop an appropriate improvement plan.
3. **Provide support for at-risk students:** Identify individual learning gaps and monitor students' progress through subsequent assessments.
4. **Monitor academic progress:** Compare results across terms to evaluate whether teaching interventions are producing improvements.
5. **Use evidence in academic planning:** Review class averages, subject performance, and pass rates regularly when planning teaching strategies and allocating support resources.

Before making major decisions, school management should also consider attendance, teaching methods, learning materials, and other factors that may influence academic performance.

## Skills Demonstrated

This project demonstrates practical skills in:

- Data cleaning and preparation
- Data quality checks and duplicate identification
- Excel formulas and structured references
- Data aggregation and conditional calculations
- Student ranking and comparative analysis
- Academic performance measurement
- KPI development
- Data visualisation and dashboard development
- Insight generation and recommendations
- Communicating findings to decision-makers

## Conclusion

The Greenfield School Results Analysis Project demonstrates how Microsoft Excel can be used to transform raw academic records into meaningful insights for educational decision-making.

Through data cleaning, student-level analysis, class and subject comparisons, term-to-term performance tracking, and dashboard visualisation, the project provides a structured view of academic performance across the school.

The findings help highlight academic strengths, identify areas requiring attention, and support decisions aimed at improving student performance.

This project forms part of my data analytics portfolio and demonstrates my ability to use Excel to solve practical problems, communicate analytical findings, and support data-driven decisions.

---

**Project Name:** Greenfield School Results Analysis & Academic Performance Dashboard  
**Industry:** Education  
**Tool:** Microsoft Excel 2021  
**Project Type:** Data Cleaning, Data Analysis, Performance Reporting, and Dashboard Development
