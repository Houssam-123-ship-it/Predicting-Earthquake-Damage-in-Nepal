

---

# 🏗️ Earthquake Damage Prediction in Nepal

This project is part of the **Applied Data Science Lab** by WorldQuant University and demonstrates an **end-to-end machine learning workflow** using real-world data from the 2015 Nepal earthquake. The objective is to predict **building damage severity** based on structural and demographic features.

🔗 **Live Repository:** (https://github.com/Houssam-123-ship-it/Predicting-Earthquake-Damage-in-Nepal-End-to-End-Machine-Learning-Project)

---

## 📌 Project Workflow

### 1. **Prepare Data**

* Connected to a SQLite database using `sqlite3` and extracted data
* Conducted Exploratory Data Analysis (EDA) using `pandas`, `matplotlib`, and `seaborn`
* Split data into training and test sets using `train_test_split`

### 2. **Build Model**

* Developed two classification models:
  ✅ **Logistic Regression**
  ✅ **Decision Tree Classifier**
* Tuned model parameters and evaluated performance using metrics such as accuracy, precision, recall, and F1-score

### 3. **Communicate Results**

* Analyzed the impact of **socio-economic and demographic factors** on earthquake vulnerability
* Visualized feature importances and model behavior
* Reflected on **bias and fairness** in disaster modeling

---

## 📘 Included Notebooks

| Notebook                        | Description                               |
| ------------------------------- | ----------------------------------------- |
| `041-sqlite.ipynb`              | Data acquisition from SQL database        |
| `042-logistic-regression.ipynb` | Logistic Regression model                 |
| `043-decision-tree.ipynb`       | Decision Tree model and tuning            |
| `044-demographics.ipynb`        | Demographic analysis and bias exploration |

---

## 🧠 Skills Gained

* SQL data extraction & schema understanding
* Data cleaning & visualization (EDA)
* Perform a randomized train-test split
* Classification modeling (logistic regression  & decision tree classifier model for classification)
* Model tuning and evaluation
* Ethical considerations in machine learning
* Communication of technical findings
---

## 🛠️ Dependencies

Install the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn sqlite3
```

---

## 📊 Data Source

Data is sourced from a SQLite database and includes real building structure and demographic information from Nepal's Gorkha region post-earthquake.

---

## ✅ How to Run

1. Clone the repo
2. Install dependencies
3. Run notebooks in order
4. Explore, modify, and build upon the models!

---

## 🏁 Final Thoughts

This project was an exciting opportunity to apply theory to real-world disaster data. It challenged my ability to think critically, model responsibly, and communicate results clearly.


---


