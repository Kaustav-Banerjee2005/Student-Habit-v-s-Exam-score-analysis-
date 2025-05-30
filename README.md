# 📊 Student Habits vs Exam Score

This project analyzes how students' lifestyle and study habits affect their exam performance using Python and data visualization. The goal is to identify key behavioral patterns that contribute to academic success.

---

## 📁 Dataset

- **File:** `student_habits_performance.csv`
- **Features:** Study hours, sleep duration, social media usage, etc.
- **Target:** `exam_score`

---

## 🧹 Data Preprocessing

- Dropped less impactful columns:
  - `netflix_hours`, `part_time_job`, `diet_quality`, `exercise_frequency`, `parental_education_level`, `internet_quality`, `extracurricular_participation`
- Checked for and confirmed **no null values**
- Set `student_id` as the index
- Saved the cleaned data as `cleaned_data.csv`

---

## 📊 Exploratory Data Analysis (EDA)

### 📌 Performance Categorization

Created a new column `student_performance` based on `exam_score`:
- `Good`: ≥ 80  
- `Average`: 41–79  
- `Fail`: ≤ 40

### 📈 Exam Score Distribution

- The distribution is **left-skewed**, indicating most students scored high.
- Plotted histogram with **mean** and **quartile lines** to visualize score spread.

### 🔗 Correlation Matrix

Analyzed numerical features' correlation with `exam_score` to identify which habits matter most:
- Positive correlation: Likely with `study_hours`, `sleep_hours`
- Negative correlation: Likely with `social_media_usage`

---

## 🔍 Key Insights

- **More study hours** and **sufficient sleep** are positively associated with higher scores.
- **High social media usage** might negatively impact exam performance.
- Irrelevant lifestyle factors like part-time jobs or Netflix hours showed minimal influence.

---

## 📦 Tech Stack

- **Python**
- **Pandas, NumPy**
- **Seaborn, Matplotlib**
- **Jupyter Notebook**

---

## ✍️ Author

- **Kaustav Banerjee**
- Data Science Enthusiast

---

> "Smart habits make successful students."

