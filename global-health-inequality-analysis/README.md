# 🌍 Global Health Inequality Analysis  
### Bridging the Gap: How Inequality and Treatment Access Shape Adolescent AIDS Outcomes

## 📊 Overview
This project analyzes global adolescent AIDS mortality and identifies key structural drivers behind unequal health outcomes across countries.

Using UNICEF’s *State of the World’s Children 2024* dataset, the analysis focuses on how **prevention, treatment access, gender inequality, and income levels** influence mortality rates among adolescents aged 10–19.

👉 Full report: :contentReference[oaicite:0]{index=0}

---

## 🎯 Research Question
**What factors most strongly explain differences in adolescent AIDS mortality across countries?**

---

## 🧠 Key Insights

### 1. Awareness ≠ Survival
- Countries with higher HIV awareness often show **higher mortality rates**
- This reflects **response to crisis**, not effectiveness
- 👉 Awareness alone is insufficient without treatment access

### 2. Treatment Gap is the Strongest Predictor
- Larger ART (antiretroviral therapy) gaps → significantly higher mortality
- Structural issues (healthcare access, funding, infrastructure) drive outcomes

### 3. Gender Inequality Matters
- Female adolescents have consistently **higher mortality rates**
- Driven by:
  - Biological vulnerability
  - Social constraints (access, stigma, power imbalance)

### 4. Income Inequality Drives Everything
- ~95% of deaths occur in low- and lower-middle-income countries
- Poverty limits:
  - Diagnosis
  - Treatment access
  - Long-term care

---

## 🛠️ Methods

### Data Sources
- UNICEF SOWC 2024
- World Bank (WDI)
- UNAIDS

### Techniques
- Data cleaning & transformation
- Feature engineering (treatment gap, prevention index)
- Cross-country comparative analysis
- Visualization:
  - Bar charts
  - Scatter plots (log-scale)
  - Dumbbell charts
  - Boxplots

### Tools
- **R**
- `dplyr`, `ggplot2`, `readxl`, `countrycode`

---

## 📈 Key Variables

- **AIDS mortality rate (per 100,000)**
- ART treatment coverage
- Treatment gap (unserved population)
- Prevention index (knowledge, testing, condom use)
- Gender-specific mortality
- Income classification

---

## 📊 Visualizations

- Prevention vs Mortality (bar chart)
- Treatment Gap vs Mortality (scatter + LOESS)
- Gender disparity (dumbbell chart)
- Income inequality (boxplot)

---

## 🚧 Limitations

- Cross-sectional analysis (not causal)
- Data gaps across countries
- External factors (policy, culture) not fully captured

---

## 💡 Takeaway

> Awareness can inform, but only access can save.

The findings highlight that **structural inequality—not individual behavior—is the primary driver of global health outcomes.**
