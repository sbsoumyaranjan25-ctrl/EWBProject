# EWBProject
Student-Performance-Analytics-System

## 1. Project Title & Student Details
* **Project Title:** Student Performance Analytics System[cite: 1]
* **Student Name:** [Soumya Ranjan Behera]

* **Course:** Python with AI (EWB Courses)


---

## 2. Objective
The main objective of this project is to build an automated Python-based analytics system that reads student records, processes and analyzes data using Pandas and NumPy, and generates clear academic insights—such as total marks, averages, letter grades, pass/fail statuses, subject-wise performance, and top performers[cite: 1].

---

## 3. Technologies Used
* **Python:** Core programming language used for logic and script execution.
* **Pandas:** Used for loading, cleaning, filtering, and organizing the dataset into DataFrames.
* **NumPy:** Used for numerical operations and efficient array-based calculations.

---

## 4. Dataset Description
* **File Name:** `students.csv`
* **Dataset Size:** 50 student records
* **Key Fields Included:**
  * `Student_ID`: Unique identification number for each student.
  * `Name`: Full name of the student[cite: 1, 2].
  * `Department`: Academic branch/department (e.g., Computer Science, Mechanical, Electronics)[cite: 1, 2].
  * `Math`, `Science`, `English`: Numerical subject marks scored out of 100[cite: 1, 2].
  * `Attendance`: Percentage of student attendance[cite: 1, 2].

---

## 5. Implementation
The project was executed in the following steps:
1. **Data Preparation:** Created a clean CSV file (`students.csv`) containing 50 structured rows of student details[cite: 2].
2. **Data Loading:** Used Pandas (`pd.read_csv`) to load the dataset into a DataFrame and inspected columns and basic summaries[cite: 2].
3. **Data Processing:** 
   * Applied Python loops and custom functions to calculate total marks and average marks for each student[cite: 1, 2].
   * Implemented conditional statements to assign letter grades ('A', 'B', 'C', 'F') based on average scores[cite: 1, 2].
   * Utilized NumPy operations to evaluate pass/fail criteria[cite: 1, 2].
4. **Data Analysis:** Computed overall class averages, subject-wise averages, and filtered out top-performing students[cite: 1, 2].

---

## 6. Key Features
* **Automated Calculations:** Computes individual student totals and average scores dynamically[cite: 1].
* **Grading System:** Automatically assigns letter grades based on performance thresholds[cite: 1].
* **Pass/Fail Diagnostics:** Identifies student status based on academic criteria[cite: 1].
* **Subject-Wise Insights:** Calculates highest, lowest, and average marks per subject[cite: 1].
* **Top Performer Identification:** Pinpoints the highest-scoring student in the class[cite: 1].

---

## 7. Output / Screenshots
*(Note: Replace this section or add screenshots showing your actual terminal/console output when running `main.py`)*
```text
--- STUDENT PERFORMANCE ANALYTICS ---
Total Students: 50
Overall Class Average: 76.42

Top Performer: Sneha Iyer with Average 95.00

Subject-wise Averages:
- Math: 75.80
- Science: 76.20
- English: 77.26

Pass/Fail Statistics:
Pass    44
Fail     6
