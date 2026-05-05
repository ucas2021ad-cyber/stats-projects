
# 🎵 Spotify Song Popularity Analysis

## 📌 Overview

This project analyzes how musical attributes influence song popularity on Spotify from 2015 to present.
Using multiple linear regression, the goal is to identify which features contribute most to commercial success.

---

## 🔍 Research Question

How do musical attributes (danceability, energy, loudness, valence, tempo, duration, etc.) impact song popularity?

---

## 📊 Data

* Dataset: *Top 10,000 Spotify Songs (1960–Now)*
* Source: Kaggle (Spotify API data)
* Response variable: **Popularity (0–100)**
* Predictors: Danceability, Energy, Loudness, Valence, Tempo, Duration, etc. 

---

## ⚙️ Methodology

* Built a **multiple linear regression model**
* Checked assumptions:

  * Linearity
  * Constant variance
  * Normality
* Applied transformations (Box-Cox, log transformations)
* Conducted:

  * ANOVA test (overall significance)
  * t-tests (individual predictors)
  * Partial F-tests (model refinement)
* Evaluated models using:

  * Adjusted R²
  * AIC / BIC

---

## 📈 Key Findings

* **Danceability** → strong positive effect on popularity
* **Loudness** → positive effect
* **Duration** → positive effect
* **Valence (positivity)** → negative effect

👉 Suggests that emotionally intense or less “happy” songs may perform better.

---

## 📉 Limitations

* Low R² → many external factors (e.g., marketing, trends) not captured
* Songs with 0 popularity excluded → potential bias
* Mild violation of normality assumption

---

## 🛠 Tools Used

* R (linear regression, diagnostics)
* Data visualization
* Statistical testing

---

## 🎯 Takeaway

This project demonstrates how statistical modeling can be used to extract actionable insights from real-world data, particularly in understanding consumer preferences in the music industry.
