# 🎓 Student Performance Dashboard

![Python](https://img.shields.io/badge/Language-Python-blue)
![Tools](https://img.shields.io/badge/Libraries-pandas%2C%20NumPy%2C%20Matplotlib-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📊 Overview

This project analyzes student performance data using Python, pandas, and NumPy.  
The dataset includes student scores in Math, Reading, and Writing, along with demographic information.

---

## ✅ Objectives

- Clean and prepare student performance data
- Calculate average score using NumPy
- Categorize students into performance levels: Excellent, Good, Needs Improvement
- Analyze scores by gender, parental education, and test prep status
- Export cleaned data to CSV/Excel
- Visualize score distributions and performance breakdowns

---

## 📁 Dataset

- Source: [Kaggle - Student Performance Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- Format: CSV

### Columns Used:
- `math score`
- `reading score`
- `writing score`
- `gender`, `parental level of education`, `test preparation course`

---

## 🛠️ Tools Used

- Python 3.x  
- pandas  
- NumPy  
- matplotlib  
- Jupyter Notebook

---

## 🧠 Key Functions Used

- `pandas.read_csv()`, `.groupby()`, `.value_counts()`, `.to_csv()`
- `NumPy.mean()`, `NumPy.where()` for performance classification
- `matplotlib.pyplot` for plotting histograms and bar charts

---

## 📈 Sample Insights

- Students who completed test prep scored higher on average
- Gender-wise score differences were minimal in reading/writing
- Majority of students fell under the "Good" category

---

## 📤 Output

- Cleaned dataset saved in: `/output/cleaned_student_data.csv`
- Visualizations displayed in the notebook

---

## 📎 License

This project is free to use under the [MIT License](https://choosealicense.com/licenses/mit/).

---

## 👩‍💻 Author

**Anisha Kumari**  
📍 India  
🔗 [GitHub: anisha-repo](https://github.com/anisha-repo)
