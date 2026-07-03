# 🎯 Expectation Decider

### Probability & Statistical Analysis of Student Exam Performance

[![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?logo=plotly&logoColor=white)](https://matplotlib.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](#license)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)](#)

---

## 📖 Overview

**Expectation Decider** is a statistics and probability project that analyzes the likelihood of students passing a competitive mathematics examination, using historical academic data. The project applies core probability concepts — empirical & theoretical probability, probability distributions, contingency tables, conditional probability, and **Bayes' Theorem** — to understand how factors like study hours, attendance, group discussion participation, and previous test scores influence exam outcomes.

---

## 🎯 Project Objective

To analyze and quantify the probability of students passing a final examination by studying the relationship between key academic behaviors (study hours, attendance, group discussion, previous scores) and the final pass/fail outcome, using rigorous probability theory and statistical reasoning.

---

## 🗂️ Dataset Description

The dataset (`Expectation_Decider_Dataset.csv`) contains records for **200 students** with the following attributes:

| Column | Description |
|---|---|
| `study_hours` | Number of hours studied per week |
| `attendance` | Attendance percentage |
| `group_discussion` | Participation in group discussions (Yes/No) |
| `previous_test_score` | Previous internal examination marks |
| `final_exam_pass` | Final exam outcome (Pass/Fail) |

---

## 🧠 Concepts Covered

1. **Understanding the Basics**
   - Probability fundamentals, terminology (experiment, outcome, sample space, event)
   - Independent vs. dependent events
   - Conditional probability
2. **Types of Probability**
   - Theoretical probability
   - Empirical probability
3. **Random Variable & Probability Distribution**
   - Probability distribution table
   - Mean (Expected Value)
   - Variance
4. **Venn Diagram in Probability**
   - Visualizing overlapping events
5. **Contingency Table & Probability Calculations**
   - Joint probability
   - Marginal probability
   - Conditional probability
6. **Understanding Relationships**
   - Dependence between group discussion participation and passing
7. **Bayes' Theorem Application**
   - Computing `P(Pass | High Attendance)` using prior and conditional probabilities

---

## 🔑 Key Insight

Using Bayes' Theorem, the analysis finds that:

> **P(Pass | High Attendance) ≈ 51.09%**

This shows that while attendance is an important factor, **high attendance alone does not guarantee passing** — study hours, previous test scores, and group discussion participation also play a significant role.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Python 3.12** | Core programming language |
| **Pandas** | Data loading & manipulation |
| **NumPy** | Numerical computations |
| **Matplotlib** | Data visualization |
| **matplotlib-venn** | Venn diagram plotting |
| **Jupyter Notebook** | Interactive analysis environment |

---

## 📁 Project Structure

```
Expectation-Decider/
│
├── Expectation_Decider.ipynb          # Main analysis notebook
├── Expectation_Decider_Dataset.csv    # Student dataset (200 records)
├── PR__1_Expectation_Decider.docx     # Project report
└── README.md                          # Project documentation
```

---

## ⚙️ Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/Expectation-Decider.git
   cd Expectation-Decider
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib matplotlib-venn jupyter
   ```

3. **Run the notebook**
   ```bash
   jupyter notebook Expectation_Decider.ipynb
   ```

---

## 📊 Sample Output

```
Total Students        : 200
Marginal Probability   = 0.45   (P of passing)
Joint Probability       = 0.22   (Group Discussion ∩ Pass)
Conditional Probability = 0.431  (Pass | Group Discussion)
P(Pass | High Attendance) = 0.5109
```

---

## 🏁 Conclusion

The project demonstrates that no single factor determines a student's success — passing the final exam is influenced by a **combination of study habits, attendance, peer engagement, and prior performance**. Applying Bayes' Theorem provides a statistically grounded way to update predictions about a student's chance of passing as new information (like attendance) becomes available.

---

## 👩‍💻 Author

**Rensee Gajipara**

[![GitHub](https://img.shields.io/badge/GitHub-Profile-181717?logo=github&logoColor=white)](https://github.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/)

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use, modify, and distribute with attribution.

---

<p align="center">⭐ If you found this project useful, consider giving it a star! ⭐</p>
