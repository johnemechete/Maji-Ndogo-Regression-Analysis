# 🌾 Predicting Crop Yields in Maji Ndogo: A Linear Regression Learning Journey

This repository contains the code, data, and visuals used in the **Maji Ndogo Crop Yield Analysis** project — a data science exploration of how environmental factors such as temperature and pollution influence agricultural productivity.

What began as an ALX classroom assignment evolved into a personal project to strengthen my data analysis and storytelling skills.  
I refined the original notebook, explored the data more deeply, and transformed it into a portfolio piece that showcases both technical understanding and interpretation.

---

## 📊 Project Overview

**Goal:**  
To determine whether temperature or pollution levels have a measurable linear relationship with standardized crop yield in Maji Ndogo.

**Key Findings:**
- 🌡️ **Average Temperature:** Showed almost no linear relationship with yield.  
- 🏭 **Pollution Level:** Displayed a weak negative correlation — higher pollution slightly reduced yield.  
- 📈 **Model Evaluation:** Low R² (~0.08) suggests pollution alone cannot explain yield variations.  
- 🔍 **Residual Analysis:** Residuals were mostly random, but minor heteroscedasticity hints at missing variables.  

📖 **Read the full article on Medium:**  
👉 [Predicting Crop Yields in Maji Ndogo: A Linear Regression Learning Journey](https://medium.com/p/257feef77a7e/edit)

---

## 🧩 Repository Structure

Maji-Ndogo-Regression-Analysis/
│
├── data/
│ └── maji_ndogo.db # SQLite database
│
├── notebooks/
│ └── Maji_Ndogo_Regression_Analysis.ipynb
│
├── visuals/
│ ├── temperature_vs_yield.png
│ ├── pollution_vs_yield.png
│ ├── residual_histogram.png
│ └── residuals_vs_predicted.png
│
├── requirements.txt
└── README.md


---

## 🚀 How to Run

1. **Clone this repository**
   ```bash
   git clone https://github.com/JohnEmechete/Maji-Ndogo-Regression-Analysis.git
   cd Maji-Ndogo-Regression-Analysis


Install dependencies

pip install -r requirements.txt


Launch the notebook

jupyter notebook notebooks/Maji_Ndogo_Regression_Analysis.ipynb


(Optional) Download the helper files via the link provided in the notebook or Medium article.

📈 Evaluation Metrics
Metric	Meaning	Result (Approx.)
R²	Proportion of yield variance explained by pollution	0.08
MAE	Mean Absolute Error	0.086
MSE	Mean Squared Error	0.011
RMSE	Root Mean Squared Error	0.107

These results show that while pollution has some predictive power, crop yield is likely influenced by a combination of multiple environmental factors — not a single variable.

🧠 Future Roadmap
Phase	Focus	Description
02	Multiple Regression	Combine variables (temperature, rainfall, pollution) to improve accuracy
03	Nonlinear Models	Use polynomial and tree-based methods to capture complex relationships
04	Crop-Specific Analysis	Study how different crops respond to environmental changes
🧾 Dependencies

Python 3.10+

pandas

numpy

matplotlib

seaborn

scikit-learn

sqlite3 (standard library)

Install all with:

pip install -r requirements.txt

✍️ Author

John Emechete
Data Science Enthusiast | Engineer | Problem Solver

📫 Connect with me:
LinkedIn
 • Medium: https://medium.com/@johnemechete_3592
 • GitHub: https://www.linkedin.com/mynetwork/grow/
