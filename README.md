# Industrial-Prediction

## 📌 Project Overview
This research aims to analyze and predict outcomes within a manufacturing or e-commerce context, specifically focusing on identifying the factors that drive successful conversions or system anomalies. The project leverages a dataset of 12,330 sessions with 18 attributes to capture user or machine interaction patterns.

## 📊 Dataset & Variables
The dataset comprises both numerical and categorical features that describe the "what, when, and how" of each session:
* **Target Variable:** `Revenue` (Boolean), indicating whether a session or process finalized in a successful transaction or target outcome.
* **Numerical Features:** Includes metrics like `Administrative`, `Informational`, `ProductRelated` durations, and `PageValues`.
* **Categorical Features:** Includes `Month`, `VisitorType`, `Weekend`, and closeness to a `SpecialDay`.

## 🛠️ Methodology
The project employs a structured statistical approach to binary classification:
* **Primary Model:** **Logistic Regression** (Binomial GLM with Logit link).
* **Rationale:** This model was chosen for its suitability for binary outcomes and its ability to provide **interpretable coefficients (odds ratios)**.
* **Analysis Focus:** Investigating the impact of navigation patterns (e.g., `ExitRates`, `Bounce Rates`) and seasonal impacts (e.g., holidays and weekends) on conversion rates.

## 🚀 Key Insights & Expected Outcomes
* **Predictive Power:** `PageValues` has been identified as a strong positive predictor of successful outcomes.
* **Conversion Obstacles:** High bounce and exit rates are expected to negatively impact the final conversion or success rate.
* **Segment Behavior:** The study investigates whether different types of visitors (New vs. Returning) behave differently during peak months.
* **Business Value:** The findings help identify "high-fidelity" areas that require optimization to improve overall performance.

## 📁 Repository Structure
* `model.ipynb`: Jupyter Notebook containing data analysis, feature exploration, and model implementation.
* `A1 Competition.pdf`: Detailed project proposal and research framework.
* `final_submission.csv`: The final predicted output and classification results.

---
**Course:** STAT 4620/5620 – Data Analysis
