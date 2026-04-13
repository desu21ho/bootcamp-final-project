# bootcamp-final-project
# Ethiopia Agriculture Productivity Analysis 🇪🇹

## 📊 Project Overview
This project analyzes agricultural productivity in Ethiopia using advanced data science techniques. The goal is to identify key factors affecting farm performance and uncover non-obvious patterns through multi-dimensional and statistical analysis.

---

## 🎯 Objectives
- Understand the impact of environmental and input factors on productivity
- Identify high-performing farm characteristics
- Analyze regional and structural differences
- Apply advanced analytical techniques beyond basic statistics

---

## 📁 Dataset Description
The dataset contains 800 observations of Ethiopian farms with the following features:

- Rainfall (mm)
- Soil Type (Clay, Loam, Sandy)
- Fertilizer Use (0 = No, 1 = Yes)
- Land Size (hectares)
- Yield per hectare (tons)
- Total Production (tons)
- Price per ton (birr)
- Total Revenue (birr)
- Region
- Political Stability Index

---

## ⚙️ Feature Engineering
The following new features were created to enable deeper analysis:

- **Revenue per hectare** → measures farm efficiency
- **Rainfall category** → Low, Medium, High classification
- **Performance segment** → Low, Medium, High farms (based on percentiles)
- **Input efficiency** → output per unit of fertilizer

---

## 🧠 Analytical Techniques Used
This project goes beyond basic analysis and applies advanced methods:

- Cross-tabulation (rainfall × soil interaction)
- Multi-dimensional analysis (3+ variable interaction)
- Percentile analysis (top 10% and 5%)
- Outlier investigation (top-performing farms)
- Cohort analysis (regional comparison)
- Correlation analysis (relationship strength)
- Ratio analysis (efficiency metrics)
- Statistical testing (t-test for significance)

---

## 🔍 Key Findings (Quantified Insights)

- 🌧️ **Rainfall Impact:**  
  Revenue increases by **57.68%** from low to high rainfall (p < 0.001), confirming a strong and statistically significant effect.

- 🌱 **Fertilizer Impact:**  
  Fertilizer improves productivity by **17.84%**, which is over **3× lower than rainfall impact**, indicating environmental dominance.

- 📊 **Top Performance Distribution:**  
  Top 10% of farms generate **18.27% of total revenue**, while top 5% contribute **8.84%**, showing relatively balanced productivity.

- 🌍 **Regional Differences:**  
  Top region (**Gambela**) outperforms lowest (**Amhara**) by ~**16%**, indicating geographic inequality.

- 🌾 **Soil & Rainfall Interaction:**  
  Under high rainfall, **Loam soil (81,636 birr)** outperforms Sandy soil by ~**31%**, showing strong interaction effects.

- ⚡ **Efficiency Insight:**  
  Input efficiency increases from **2.02 → 3.22** (~60% increase) as rainfall improves, showing environmental amplification of inputs.

- 📈 **Correlation Insight:**  
  Rainfall strongly affects yield (**r = 0.77**), which then drives revenue (**r = 0.51**), indicating an indirect productivity pathway.

- 📏 **Land Size Insight:**  
  Land size has near-zero correlation with productivity (**r ≈ 0**), meaning efficiency matters more than scale.

---

## 🧪 Statistical Validation
A t-test was conducted to validate differences between rainfall groups:

- **T-statistic:** -12.29  
- **P-value:** 2.52 × 10⁻³⁰  

This confirms that observed differences are **statistically significant and not due to random variation**.

---

## 🧠 Conclusion
Agricultural productivity in Ethiopia is primarily driven by environmental factors, particularly rainfall, but is strongly influenced by the interaction between climate, soil, and efficiency.

The findings highlight that:
- Productivity is not controlled by a single factor
- Environmental conditions amplify input effectiveness
- Performance differences are systemic, not isolated

👉 A multi-dimensional strategy is required for improving agricultural outcomes.

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- SciPy
- Jupyter Notebook / Kaggle
- GitHub

---

## 🚀 Project Structure
bootcamp-final-project/
│
├──final-project(1).ipynb 
├── ethiopia_agriculture_dataset.xlsx
├── README.md

