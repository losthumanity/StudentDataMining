# 📊 Student Performance Analysis

This project analyzes student performance using the [Student Alcohol Consumption dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance). The analysis is done in **Python** (converted from an original R script) and explores how factors like study time, parental education, and absences influence final grades.

## 📁 Dataset

- **File**: `student-mat.csv`
- **Source**: UCI Machine Learning Repository
- **Description**: Data collected from Portuguese secondary school students.

## 🛠️ Technologies Used

- **Python 3.12.6**
- **pandas** – Data manipulation
- **matplotlib & seaborn** – Data visualization
- **scikit-learn** – ML models (SVM, Random Forest)
- **numpy** – Numeric operations

## 🔍 Exploratory Data Analysis

Key steps in the analysis:

- Converted categorical columns to `category` type.
- Removed students with excessive absences.
- Visualized distributions of:
  - Age
  - Absences (Pass vs Fail)
  - Study time vs Final grade
  - Parental education vs Final grade
- Summarized missing values and dataset structure.

## 📈 Visualizations

- **Boxplot**: Absences comparison between passed and failed students.
- **Histogram**: Age distribution.
- **Bar Charts**:
  - Study time vs average grade
  - Parental education vs average grade (Mother vs Father)

## 📊 Machine Learning (optional if included)

Models can be added to predict student performance using features like:

- Study time
- Absences
- Parental education

## 📂 Folder Structure

  📁 student-performance-analysis

  ├── student-mat.csv

  ├── analysis.py

  └── README.md

## ✅ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/student-performance-analysis.git
   cd student-performance-analysis

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn

3. Run the analysis:
   ```bash
   jupyter data_mining.ipynb
   jupyter test.ipynb
