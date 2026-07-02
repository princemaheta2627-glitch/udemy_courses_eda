# 🎓 Udemy Courses Exploratory Data Analysis (EDA)

# 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Udemy Courses Dataset** to uncover insights into course popularity, pricing strategies, subscriber behavior, course levels, and subject-wise performance.

The analysis demonstrates practical data cleaning, datetime parsing, aggregation, visualization, and business intelligence techniques using Python.

---

# 🎯 Objectives

- Explore and understand the Udemy course dataset
- Perform data cleaning and duplicate removal
- Analyze free vs paid course performance
- Study subscriber and review trends
- Compare course levels and subject popularity
- Search and analyze Python-related courses
- Extract business insights through data visualization

---

# 📊 Dataset Information

| Feature | Details |
|----------|----------|
| Dataset | Udemy Courses |
| Source | Kaggle |
| Rows (Raw) | 3,678 |
| Rows (After Cleaning) | 3,672 |
| Columns | 12 |
| Subjects | 4 |
| Course Levels | 4 |
| Duplicate Rows Removed | 6 |

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📂 Project Structure

```
Udemy-Courses-EDA/
│
├── udemy_courses.csv
├── Udemy_Courses_EDA.ipynb
├── README.md
├── requirements.txt
│
├── images/
│   ├── subject_distribution.png
│   ├── course_levels.png
│   ├── free_vs_paid.png
│   ├── top_courses.png
│   ├── subject_reviews.png
│   ├── price_vs_reviews.png
│   └── python_courses.png
```

---

# 📈 Exploratory Data Analysis

The project covers:

### 🔹 Data Inspection

- Dataset Shape
- Data Types
- Memory Usage
- Statistical Summary

### 🔹 Data Cleaning

- Duplicate Detection
- Duplicate Removal
- Datetime Parsing
- Data Quality Check

### 🔹 Univariate Analysis

- Subject Distribution
- Course Level Distribution
- Free vs Paid Courses

### 🔹 Bivariate Analysis

- Subscribers by Course Level
- Free vs Paid Course Performance
- Subject vs Reviews
- Price vs Reviews

### 🔹 Ranking Analysis

- Top 10 Most Popular Courses
- Most Popular Python Courses
- Highest Reviewed Subjects

---

# 📊 Key Visualizations

- 📚 Subject Distribution
- 🎯 Course Level Distribution
- 💰 Free vs Paid Comparison
- 👨‍🎓 Top 10 Courses by Subscribers
- ⭐ Subject-wise Reviews
- 📈 Price vs Reviews Scatter Plot
- 🐍 Python Courses Analysis

---

# 🔍 Key Insights

- 📚 Web Development is the largest subject category.
- 💼 Business Finance closely follows in course count.
- 💳 91.6% of courses are paid.
- 🆓 Free courses attract nearly **5× more subscribers** than paid courses.
- 📖 Paid courses provide almost **2× more lectures** and longer content.
- 🌍 "All Levels" courses receive the highest number of subscribers.
- 🏆 **Learn HTML5 Programming From Scratch** is the most subscribed course.
- ⭐ Web Development receives the highest number of reviews.
- 💲 Course price has little correlation with review count.
- 🐍 29 courses contain "Python" in their title.

---

# 🧹 Data Cleaning

- Checked missing values
- Removed duplicate records
- Parsed datetime columns
- Verified data consistency
- Prepared dataset for visualization

---

# 💡 Business Questions Answered

- Which subject has the most courses?
- Which course level is most common?
- Are paid courses more popular than free courses?
- Which type has more subscribers?
- Which course has the highest enrollment?
- Which subject receives the most reviews?
- Does price influence review count?
- How many Python-related courses exist?
- Which Python courses are the most popular?

---

# 📚 Python Concepts Used

- Pandas
- NumPy
- Data Cleaning
- Datetime Parsing
- GroupBy Aggregation
- Value Counts
- String Filtering (`str.contains`)
- Sorting & Ranking
- Countplots
- Barplots
- Scatterplots

---

# 🚀 Future Improvements

- 📈 Course Popularity Prediction
- 💰 Price Optimization Model
- 🤖 Machine Learning for Subscriber Prediction
- 📝 NLP-based Course Title Analysis
- 📊 Interactive Streamlit Dashboard
- 📅 Time-Series Analysis of Published Courses
- 🎯 Recommendation System for Courses

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/udemy-courses-eda.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
jupyter
```

Install manually

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

---

# 📸 Sample Output

Create an **images** folder and add screenshots from your notebook.

```
images/
├── subject_distribution.png
├── course_levels.png
├── free_vs_paid.png
├── top_courses.png
├── subject_reviews.png
├── price_vs_reviews.png
└── python_courses.png
```

---

# 👨‍💻 Author

**Prince Maheta**

📊 Aspiring Data Scientist | Data Analyst

🔗 **GitHub:** https://github.com/princemaheta2627-glitch

---

# ⭐ Show Your Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

---

# 📜 License

This project is intended for educational, learning, and portfolio purposes.
