# Students Exam Scores
This project contains data cleaning and preprocessing, visualization, and analysis of the Students Exam Scores dataset from [Kaggle](https://www.kaggle.com/datasets/desalegngeb/students-exam-scores).
The analysis focuses on the influence of a variety of personal, socio-economic, and cultural factors on students’ academic performance.

## Overview
- Cleaned and preprocessed data
- Gained insights from descriptive statistics and variables distributions
- Visualized the overall exam scores by various study habits and social factors using barplots, kde plots and boxplots
- Evaluated if other personal factors have any effect on exam grades

## Resources Used
- Python 3.7
- Numpy and Pandas libraries for data manipulation
- Matplotlib and Seaborn libraries for data visualization

## Dataset
The Students Exam Scores dataset includes scores from three exams of students at a (fictional) public school and a variety of personal and socio-economic factors that may have interaction effects upon them. The dataset contains 30641 observations and 14 attributes.

- **Gender**: Gender of the student (male/female)
- **EthnicGroup**: Ethnic group of the student (group A to E)
- **ParentEduc**: Parent(s) education background (from some_highschool to master's degree)
- **LunchType**: School lunch type (standard or free/reduced)
- **TestPrep**: Test preparation course followed (completed or none)
- **ParentMaritalStatus**: Parent(s) marital status (married/single/widowed/divorced)
- **PracticeSport**: How often the student parctice sport (never/sometimes/regularly))
- **IsFirstChild**: If the child is first child in the family or not (yes/no)
- **NrSiblings**: Number of siblings the student has (0 to 7)
- **TransportMeans**: Means of transport to school (schoolbus/private)
- **WklyStudyHours**: Weekly self-study hours(less that 5hrs; between 5 and 10hrs; more than 10hrs)
- **MathScore**: math test score(0-100)
- **ReadingScore**: reading test score(0-100)
- **WritingScore**: writing test score(0-100)

## Data Cleaning and Preprocessing
- Get insights from descriptive statistics and columns info 
- Check for duplicates
- Handle missing values
     - Numerical columns: impute missing values with the median of the variable
     - Categorical columns: impute missing values with varaible's mode
- Drop unnecessary columns
- Map categories in columns
- Add two new columns:
     - Scores contains the average Math, Reading and Writing scores
     - Grades represents students' grades from A to F according to Overall Score









## EDA




## What factors influence students’ test scores?



