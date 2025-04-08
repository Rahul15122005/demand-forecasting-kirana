Price Optimization & Demand Forecasting

This project predicts the demand (`units_sold`) for local kirana stores based on various features like price, discount, inventory levels, and competitor pricing.

---

Problem Statement

Retailers need to optimize prices and manage inventory effectively. This model helps predict demand and supports pricing decisions using machine learning.

---

Features Used
- Price
- Discount
- Inventory Control
- Competitor Price
- Holiday Indicator
- Day of Week
- Weekend Status (Derived)

---

Models Built
- Linear Regression (Baseline)
- Random Forest Regressor (Tuned using GridSearchCV)

---

Evaluation Metrics
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- R² Score

---

Final Model Performance

| Model | MAE | MSE | R² |
|-------|-----|-----|-----|
| Random Forest (Tuned) | 3.79 | 22.49 | 0.95 |

---

Project Structure

- `notebook/`: Contains the full EDA, model building, tuning and evaluation.

- `models/`: Saved `.pkl` model file.

- `data/`: Cleaned dataset.

- `README.md`: Project overview and summary.

- `requirements.txt`: Required packages.

---

Skills Used

- EDA
- Feature Engineering
- Machine Learning (Regression)
- Model Tuning
- Residual Analysis
- Model Evaluation
- Project Packaging

---

How to Run

1. Clone the repo  
2. Install dependencies  
```bash
pip install -r requirements.txt
