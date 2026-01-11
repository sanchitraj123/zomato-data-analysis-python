# 🍽️ Zomato Data Analysis Using Python

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on Zomato restaurant data to understand **customer preferences**, **restaurant trends**, and **ordering behavior**.  
The goal is to extract **actionable business insights** using Python and data visualization techniques.

---

## 🎯 Objectives
The analysis aims to answer the following business questions:

- Do more restaurants offer **online delivery** or **offline dining**?
- Which **types of restaurants** are most preferred by customers?
- What **price range** do couples prefer while dining?
- How do **ratings differ** between online and offline orders?

---

## 🛠️ Tools & Technologies Used
- **Programming Language:** Python  
- **Libraries:**  
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Seaborn  
- **IDE:** VS Code  
- **Version Control:** Git & GitHub  

---

## 📂 Project Structure
ZOMATO_DATA_ANALYSIS/
│
├── data/
│ └── Zomato-data-.csv
│
├── notebooks/
│ └── zomato_analysis.ipynb
│
├── README.md
└── requirements.txt




---

## 🧹 Data Cleaning & Preparation
- Converted the `rate` column to numeric values
- Checked and handled missing values
- Verified column data types for correctness
- Ensured dataset consistency before analysis

---

## 📊 Key Analysis Performed
- Distribution of restaurant types (`listed_in(type)`)
- Online vs offline order availability
- Customer rating distribution
- Votes comparison across restaurant categories
- Approximate cost preference for couples
- Online vs offline rating comparison
- Heatmap of restaurant type vs order mode

---

## 🔍 Key Insights
- 🍽️ **Dining restaurants** dominate the Zomato platform  
- 📵 Majority of restaurants **do not accept online orders**  
- ⭐ Most restaurant ratings lie between **3.5 and 4.0**  
- 💰 Couples prefer restaurants costing around **₹300 for two**  
- ☕ **Cafes receive more online orders** compared to dining restaurants  

---

## 📈 Visualizations Included
- Count plots  
- Line plots  
- Histograms  
- Box plots  
- Heatmaps  

These visualizations help in **quick decision-making** and **understanding customer behavior**.

---

## 📝 How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/zomato-data-analysis-python.git

2. Navigate to project folder:
   cd zomato-data-analysis-python


3. Install dependencies:
   pip install -r requirements.txt


4. Open Jupyter Notebook:
   jupyter notebook notebooks/zomato_analysis.ipynb


Run the notebook cells step by step.

💡 Future Improvements

Add predictive modeling (restaurant rating prediction)
Perform sentiment analysis on reviews (if available)
Include more advanced visualizations (like interactive dashboards)

📚 References

Zomato Dataset on Kaggle

Python Pandas, Matplotlib & Seaborn Documentation

👤 Author

Your Name – Sanchit Raj | Python 


