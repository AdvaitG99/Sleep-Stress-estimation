# Sleep-Stress-estimation
A linear regression machine learning model that predicts human stress levels from sleep habits, featuring data cleaning, EDA, and model evaluation

# Sleep vs. Stress: Predictive Analysis & Machine Learning

An end-to-end data science project exploring the mathematical relationship between lifestyle habits and mental well-being, concluding with a predictive Machine Learning model.

---

## 📊 Phase 1: Exploratory Data Analysis (EDA)
* **Data Cleaning:** Handled missing values, dropped irrelevant features, and verified data types across the dataset.
* **Key Insight (The "Stress Cliff"):** Visualized a sharp increase in stress levels when sleep drops below **6.3 hours**.
* **The Demographic Anomaly:** Discovered that **Teachers** exhibited a unique resilience to moderate sleep deprivation, maintaining lower stress levels (4.0) compared to high-stakes fields like healthcare.

## 🤖 Phase 2: Machine Learning Implementation
Built a **Linear Regression** model using `Scikit-Learn` to predict an individual's stress level based on their sleep duration.

* **Data Split:** Implemented an 80/20 train/test split, yielding a training set of **299 rows** and a validation test set of **75 rows**.
* **Model Performance:** Achieved a **Mean Squared Error (MSE) of 0.957**, indicating the model's predictions are, on average, within less than 1 unit on the stress scale.
* **Predictive Power:** * Predicted Stress for **5 hours of sleep**: `9.13` (High Stress)
    * Predicted Stress for **9 hours of sleep**: `2.08` (Low Stress)

## 📈 Visualizing the Best Fit Line
The model creates a linear mathematical trendline through the messy, real-world data points. Residual analysis revealed that the model's largest outliers (~2.5 units off) occurred around the 6.5-hour sleep mark, indicating opportunities for future multi-variable modeling.
