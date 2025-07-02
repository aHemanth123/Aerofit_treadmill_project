# 🏃 AeroFit Treadmill Buyer Profile Analysis

## 📌 Objective
This project is part of a recruitment assessment used by AeroFit to analyze customer preferences and provide personalized treadmill recommendations. The aim is to:

- Understand how customer attributes (age, income, gender, fitness, education, etc.) influence product choice.
- Identify patterns and trends in treadmill purchases.
- Build customer profiles for each product (KP281, KP481, KP781).
- Provide actionable insights and recommendations.

---

## 📁 Dataset Overview

The dataset contains customer information for purchases made in the last 3 months. It includes:

| Column          | Description                                         |
|-----------------|-----------------------------------------------------|
| Product         | Treadmill model purchased: KP281, KP481, KP781     |
| Age             | Customer age in years                               |
| Gender          | Male / Female                                       |
| Education       | Years of formal education                           |
| MaritalStatus   | Single / Partnered                                  |
| Usage           | Expected weekly usage (days per week)              |
| Fitness         | Self-rated fitness (1 = Poor, 5 = Excellent)        |
| Income          | Annual income in USD                                |
| Miles           | Estimated miles walked/ran per week                |

---

## 🧪 Analysis Performed

- Descriptive statistics for each product
- Box plots for age, education, usage, fitness
- Count plots for gender, fitness levels, and usage patterns
- Crosstabs and conditional probabilities for age groups and product choices
- Revenue calculations per product
- Final business recommendations

---

## 📊 Visualizations Included

- Product preference by Age Group
- Usage & Fitness distribution across Products
- Gender-wise product purchases
- Education Level vs Product
- Average miles per product
- Revenue table (sales × price)

---

## 🧾 Business Recommendations

- **KP281**: Target casual users, students, or beginners.
- **KP481**: Ideal for regular exercisers; promote to working professionals.
- **KP781**: Premium users with high fitness and income; promote through fitness apps or partnerships.

---

## 🛠️ Tools & Libraries Used

- Python (Pandas, Matplotlib, Seaborn)
- Tabulate (for revenue reporting)
- Jupyter Notebook

---

## 🔮 Future Enhancements

### ✅ Planned Integration with Power BI:
We aim to create an interactive Power BI dashboard to visualize:
- Customer profiles by segment
- Dynamic product preference filters (age, gender, fitness)
- Revenue contribution & market segmentation
- Time-series tracking for future purchase trends (if more data becomes available)

Power BI will allow real-time interaction and decision-making support for the sales and marketing team.

---

## 🚀 How to Run

1. Clone this repository or download the notebook.
2. Open `1_updated.ipynb` in Jupyter or VSCode.
3. Ensure required libraries are installed:
   ```bash
   pip install pandas seaborn matplotlib tabulate
