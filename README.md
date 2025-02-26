# Student Performance Analysis Project

## 📌 Project Overview

This project analyses student performance based on various factors such as attendance, parental involvement, and engagement in school activities. The analysis includes **data cleaning, exploratory data analysis (EDA), predictive modelling, and visualization using Power BI**.

## 📂 Dataset

The dataset consists of the following columns:

- **Gender**: Male/Female
- **Nationality**: Country of the student
- **Place of Birth**: Birth location
- **Stage ID**: Education level (Primary, Middle, High School)
- **Grade ID**: Specific grade level
- **Section ID**: Class section
- **Topic**: Subject being studied
- **Semester**: First or second semester
- **Relation**: Relationship with guardian
- **Raised Hands**: Number of times a student raised their hand in class
- **Visited Resources**: Interaction with e-learning resources
- **Announcements View**: Number of times announcements were viewed
- **Discussion Participation**: Number of discussion contributions
- **Parent Answering Survey**: Whether the parent completed the survey
- **Parent School Satisfaction**: Satisfaction level with the school
- **Student Absence Days**: Number of absences (categorized)
- **Class Performance**: Final performance classification (Excellent, Good, Needs Improvement)

## 🔍 Key Analyses Performed

### 1️⃣ Descriptive & Calculative Analysis

- Summary statistics of numerical columns
- Identification of missing values and data inconsistencies
- Correction of column name errors

### 2️⃣ Data Visualization

- **Student Performance Overview** (Bar Chart)
- **Absenteeism Impact on Performance** (Scatter Plot)
- **Parental Involvement & Student Success** (Stacked Bar Chart)
- **Gender-Based Performance Analysis** (Grouped Bar Chart)
- **Feature Importance from Machine Learning Model** (Treemap/Pie Chart)

### 3️⃣ Predictive Modeling

- **Model Used**: Random Forest Classifier
- **Initial Accuracy**: 82%
- **Improved Accuracy**: 85% (After Hyperparameter Tuning)
- **Saved Model**: `model.pkl`

## 📁 Project Structure

```
📂 student-performance-analysis/
│-- 📂 data/               # Raw & cleaned datasets
│-- 📂 notebooks/          # Jupyter notebooks (if used)
│-- 📂 visuals/            # Saved charts & visualizations
│-- model.pkl              # Saved Machine Learning model
│-- analysis.ipynb         # Full analysis (Python or Power BI steps)
│-- README.md              # Main project documentation
│-- requirements.txt       # Libraries used (if Python)
```
## 📌 Future Improvements

- Explore deep learning models for better accuracy.
- Expand dataset with more student attributes.
- Create a web app for real-time predictions.

## 🏆 Conclusion

This project provides meaningful insights into student performance trends. It highlights the impact of absenteeism, parental involvement, and engagement on academic success. The predictive model offers a data-driven approach to identifying students who may need additional support.

