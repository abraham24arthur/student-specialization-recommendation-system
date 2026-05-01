# Student Specialization Recommendation System

## 📌 Overview
This project aims to recommend suitable specializations for students based on their academic performance. It compares a rule-based approach with a Manhattan Distance method to provide data-driven recommendations.

---

## 🎯 Objectives
- Help students choose the right specialization
- Compare rule-based vs distance-based methods
- Demonstrate data-driven decision making

---

## 🗂️ Dataset
This project uses a synthetic dataset representing student performance across several subjects:

- Math
- Programming
- Database
- Network
- GIS
- Systems
- GPA

---

## ⚙️ Methodology

### 🔹 Rule-Based Approach
Uses predefined thresholds:
- High Math + Programming → Data Science
- High Programming → Software Engineering
- High Network → Network Engineering
- Otherwise → General IT

---

### 🔹 Manhattan Distance Approach
Each specialization has an ideal profile. The system calculates distance:

d(x, y) = Σ |xᵢ - yᵢ|

The closest specialization is selected.

---

## 📊 Results
- Network Engineering is the most recommended
- Data Science is the second
- Software Engineering is the least

---

## 🔍 Insights
- Rule-based model may produce ambiguous results (General IT)
- Manhattan Distance provides more consistent recommendations
- Data can support better academic decision-making

---

## ⚠️ Limitations
- Synthetic dataset
- Manually defined profiles

---

## 🚀 Future Work
- Use real student data
- Add machine learning models
- Build interactive dashboard

---

## 👤 Author
Abraham – Informatics Graduate, Universitas Papua
