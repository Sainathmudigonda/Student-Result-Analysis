# 🎓 Student Result Analysis using Python

## 📘 Overview
This project analyzes student exam performance using Python.  
It explores how different factors — such as **study hours**, **sleep duration**, **attendance**, and **previous scores** — affect the **final exam result**.  
The goal is to draw insights and predict student performance using data analysis and visualization techniques.

---

## 🧠 Objectives
- Clean and explore the student dataset.
- Visualize key performance patterns.
- Identify correlations between study habits and exam results.
- Classify students as **Pass** or **Fail** based on their exam scores.
- Optionally, predict exam scores using a simple Machine Learning model.

---

## 📊 Dataset
- **File name:** `student_exam_scores.csv`
- **Columns may include:**
  - `student_id` – Unique student identifier  
  - `hours_studied` – Daily average study hours  
  - `sleep_hours` – Average sleep per day  
  - `attendance_percent` – Class attendance percentage  
  - `previous_scores` – Average previous semester score  
  - `exam_score` – Current final exam score  

---

## 🛠️ Technologies Used
- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn** (for predictive modeling)
- **Jupyter Notebook** / **VS Code**

---

## 📈 Project Workflow
1. **Import & Load Data**  
   Load the dataset using `pandas.read_csv()`.

2. **Data Cleaning**  
   - Handle missing values and duplicates  
   - Convert columns to proper data types  

3. **Exploratory Data Analysis (EDA)**  
   - Visualize score distribution  
   - Analyze relationships between study habits and scores  
   - Build correlation heatmaps  

4. **Feature Engineering**  
   - Create a new `pass` column (1 = Pass, 0 = Fail)

5. **Insights & Observations**  
   - Discover how attendance and study hours impact results.  
   - Identify key predictors of exam success.

6. **(Optional)** Predictive Modeling  
   - Use `RandomForestRegressor` to predict exam scores  
   - Evaluate performance using R² and MAE metrics  

7. **Export & Reporting**  
   - Save cleaned dataset and predictions to CSV  
   - Ready for Power BI or dashboard integration  

---

## 💡 Key Insights
- Students who study **more than 4 hours/day** have significantly higher average scores.  
- **Attendance** shows a strong positive correlation with performance.  
- Adequate **sleep (6–8 hours)** tends to improve concentration and results.  
- Prior academic performance is a major indicator of success.  

---

## 📂 Folder Structure
