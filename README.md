# Student Alcohol Consumption Analysis

## 📊 Project Overview

This project analyzes student alcohol consumption and explores its relationship with different student-related factors.

The analysis combines data from **Mathematics** and **Portuguese** student datasets and uses Python-based data analysis and visualization techniques to identify patterns in:

- Student demographics
- Weekday and weekend alcohol consumption
- Social activities
- Family educational support
- Study time
- Class absences
- Academic performance
- Previous failures
- Student health

> **Note:** The analysis identifies associations and patterns in the data. It does not prove that alcohol consumption causes changes in academic performance, attendance, or health.

---

## 🎯 Objectives

The main objectives of this project are:

1. Analyze the distribution of students by gender, course, and address.
2. Compare alcohol consumption between different student groups.
3. Examine the relationship between alcohol consumption and social activities.
4. Study the relationship between alcohol consumption and study time.
5. Analyze alcohol consumption in relation to class absences.
6. Explore the relationship between alcohol consumption and final grades.
7. Examine alcohol consumption in relation to previous failures and health.

---

## 📁 Dataset

The project uses two datasets:

- `student-mat.csv` — Mathematics students
- `student-por.csv` — Portuguese students

The two datasets are combined for analysis.

The datasets contain information about students' demographic, social, academic, and alcohol-consumption characteristics.

### Important Variables

| Variable | Description |
|---|---|
| `sex` | Student gender |
| `age` | Student age |
| `course` | Course/subject |
| `address` | Urban or rural home address |
| `Dalc` | Weekday alcohol consumption |
| `Walc` | Weekend alcohol consumption |
| `goout` | Frequency of going out with friends |
| `studytime` | Weekly study-time category |
| `famsup` | Family educational support |
| `absences` | Number of school absences |
| `G1` | First-period grade |
| `G2` | Second-period grade |
| `G3` | Final grade |
| `failures` | Number of previous class failures |
| `health` | Student's reported health level |

---

## 📈 Analysis Performed

### 1. Student Demographics

The project analyzes:

- Distribution of students by gender
- Distribution of students by course
- Distribution by home address
- Age-wise weekend alcohol consumption by gender

### 2. Alcohol Consumption & Social Factors

The project examines:

- Average alcohol consumption by gender
- Average alcohol consumption by area
- Alcohol consumption and frequency of going out
- Family educational support and alcohol consumption

### 3. Alcohol Consumption & Academics

The analysis explores:

- Study time and final grades
- Alcohol consumption and study time
- Weekend alcohol consumption and class absences
- Class absences and final grades at different alcohol-consumption levels

### 4. Alcohol Consumption & Student Outcomes

The project also examines:

- Final grades by course and alcohol consumption
- Previous failures by alcohol-consumption level
- Student health and alcohol consumption

---

## 🔍 Key Findings

Some important patterns observed in the analysis include:

- Weekend alcohol consumption is generally higher than weekday alcohol consumption.
- Male students show higher average alcohol consumption than female students in this dataset.
- Students who go out more frequently generally show higher weekend alcohol consumption.
- Higher weekend alcohol consumption is generally associated with higher average class absences.
- Higher study time is generally associated with higher final grades, although the relationship is not perfectly linear.
- Weekend alcohol consumption generally shows a negative association with study time.
- Alcohol consumption shows a weak negative relationship with final grades in some of the analyses.
- Family educational support shows a small difference in average alcohol consumption.
- The relationship between alcohol consumption and health does not show a clear consistent pattern.

These findings describe patterns in the dataset and should not be interpreted as proof of cause and effect.

---

## 📊 Visualizations

Different types of visualizations were used depending on the question being investigated.

### Countplots

Used to show the number of students in different categories.

### Bar Graphs

Used to compare average values between groups.

### Line Graphs

Used to show trends across ordered categories.

### Scatter Plots

Used to examine relationships between numerical variables.

### Regression Lines

Used to show the overall trend between numerical variables.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📂 Project Structure

```text
student-alcohol-analysis/
│
├── README.md
├── student_alcohol_analysis.ipynb
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── student-mat.csv
│   ├── student-por.csv
│   └── README.md
│
└── graphs/
