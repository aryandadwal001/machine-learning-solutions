# Sonar Signal Classification: Rock vs. Mine Detection

## Project Goal
Develop a Machine Learning model to accurately classify underwater sonar signals, distinguishing between benign **Rocks** ('R') and hazardous **Mines** ('M'). This project establishes a foundational safety mechanism for marine navigation.

---

## Technical Implementation
* **Model:** **Logistic Regression** (Used as a highly interpretable and efficient baseline classifier).
* **Data:** Sonar Dataset (208 samples, 60 features representing frequency band energies).
* **Methodology:**
    * Data Exploration and Class Balance Check (`M`: 111, `R`: 97).
    * **Stratified Train-Test Split (90/10)** to maintain class proportions.
    * Model Training and performance evaluation on unseen data.
* **Environment:** Python, NumPy, Pandas, **Scikit-learn**.

---

## Key Results & Performance

| Metric | Score (Range) | Interpretation |
| :--- | :--- | :--- |
| **Training Accuracy** | ~83% - 85% | Model learned signal patterns effectively. |
| **Test Accuracy** | **~76% - 81%** | Strong generalization ability on unseen, real-world data. |

> **Conclusion:** The Logistic Regression model demonstrates reliable performance, providing a solid, interpretable solution for critical underwater threat assessment.

***
