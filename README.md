# Student Performance Analysis Using Python

This project focuses on analyzing student performance data using Python, exploring various factors that potentially influence academic outcomes. The analysis includes data visualization, statistical summaries, and insights derived from the dataset.

## Table of Contents
- [Introduction](#introduction)
- [Objective] (#objective)
- [Dataset](#dataset)
- [Analysis Overview](#analysis-overview)
- [Key Findings](#key-findings)
- [Libraries Used](#libraries-used)
- [File Descriptions](#file-descriptions)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)

## Introduction

Understanding the factors that impact student performance is crucial for educational institutions and policymakers to enhance learning outcomes. This project utilizes Python for data analysis and visualization to uncover patterns and insights from a dataset containing student performance metrics.

## Objective 

Analytics questions:
What factors (features) affect test scores most?
Are there interacting features which affect test scores?

## Dataset

Dataset Link: [Kaggle Dataset](https://www.kaggle.com/datasets/desalegngeb/students-exam-scores)
This datasets are fictional and should be used for educational purposes only.
The original dataset generator creator is Mr. Royce Kimmons.
Data Dictionary (column description)
Gender: Gender of the student (male/female)
EthnicGroup: Ethnic group of the student (group A to E)
ParentEduc: Parent(s) education background (from some_highschool to master's degree)
LunchType: School lunch type (standard or free/reduced)
TestPrep: Test preparation course followed (completed or none)
ParentMaritalStatus: Parent(s) marital status (married/single/widowed/divorced)
PracticeSport: How often the student parctice sport (never/sometimes/regularly))
IsFirstChild: If the child is first child in the family or not (yes/no)
NrSiblings: Number of siblings the student has (0 to 7)
TransportMeans: Means of transport to school (schoolbus/private)
WklyStudyHours: Weekly self-study hours(less that 5hrs; between 5 and 10hrs; more than 10hrs)
MathScore: math test score(0-100)
ReadingScore: reading test score(0-100)
WritingScore: writing test score(0-100)

## Analysis Overview

1. **Data Exploration**: Initial exploration to understand the structure, features, and basic statistics of the dataset.
   
2. **Data Cleaning**: Handling missing values, correcting data types, and ensuring data consistency for analysis.

3. **Data Visualization**: Using libraries like Matplotlib and Seaborn to create visualizations such as bar plots, histograms, and heatmaps to visualize relationships and distributions.

4. **Statistical Analysis**: Calculating descriptive statistics, correlations, and group comparisons to identify significant factors influencing academic performance.

5. **Insights and Recommendations**: Deriving insights from the analysis to make recommendations for educational strategies and interventions.

## Key Findings

- **Gender**: Females tend to perform better across all subjects compared to males except Math.
- **Ethnicity**: Group E consistently achieves higher scores, while Group A shows lower scores on average.
- **Parental Education**: Higher parental education levels correlate with higher student performance.
- **Lunch Type and Test Preparation**: Standard lunch and completed test preparation are associated with higher academic scores.
- **Sports Involvement and Study Hours**: Regular sports involvement and increased weekly study hours (>10) positively impact academic performance.


## Libraries Used

- Pandas: Data manipulation and analysis.
- NumPy: Mathematical operations on arrays.
- Matplotlib: Data visualization.
- Seaborn: Statistical data visualization.


## File Descriptions

- **Student Performance Analysis.ipynb**: Python script containing data analysis and visualization code.
- **Expanded_data_with_more_features.csv**: Dataset file containing student performance data.
- **README.md**: Documentation file providing an overview of the project.

## Future Improvements

- Expand analysis to include more advanced machine learning models for predictive analysis.
- Incorporate additional datasets or external factors influencing student performance.
- Enhance visualizations with interactive features using Plotly or other libraries.

## Contributing

Contributions to improve the analysis scripts, add new features, or fix issues are welcome. Please fork the repository, make your changes, and submit a pull request.
