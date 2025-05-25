# Customer Personality Analysis 👥

This project explores customer behavior using a marketing dataset that includes demographics, spending patterns, and campaign responses. The goal is to extract actionable insights through statistical hypothesis testing.

---

## 📊 Dataset Overview

The dataset contains information about:

- Age, Education, Marital Status  
- Household structure (children/teens at home)  
- Income  
- Spending across product categories  
- Response to previous marketing campaigns  

Derived variables include:

- `Total_Spending` → Sum of spending in all categories  
- `Has_Children` → Indicator for children at home  
- `Spending_Before` / `Spending_After` → Before/after last campaign  
- `Purchase_Before` / `Purchase_After` → Binary flag for purchases  

---

## 🧪 Statistical Tests Applied

| Business Question                                             | Statistical Test           |
|--------------------------------------------------------------|----------------------------|
| Does education affect income levels?                         | Kruskal-Wallis H Test      |
| Is spending different before vs. after a campaign?           | Wilcoxon Signed-Rank Test  |
| Do customers with children spend differently?                | Mann-Whitney U Test        |
| Is satisfaction different across product categories?         | Friedman Test              |
| Did purchasing behavior change after a campaign?             | McNemar Test               |

All tests are non-parametric and performed using `scipy.stats`.

---

## 💡 Key Insights

- 🎓 Education level has a significant impact on income  
- 💸 Customers spent more after targeted campaigns  
- 👨‍👩‍👧 Families with children spend differently than others  
- 🧼 Product satisfaction varies across categories  
- 🔁 Campaigns led to measurable change in buying behavior  

---

## 🛠 Technologies Used

- Python  
- Pandas  
- Scipy (stats)  
- Seaborn  
- Jupyter Notebook  

---

## 📂 Files

- `CustomerPersonality.ipynb` → Full analysis and visualizations  
- `CustomerPersonalityReport.pdf` → Final report summary  

---

## 🚀 How to Run

1. Clone the repo  
2. Open `CustomerPersonality.ipynb` in Jupyter Notebook  
3. Run all cells to reproduce analysis and plots  

---

📌 Useful for marketing analysts, data science students, and anyone exploring behavioral segmentation.
