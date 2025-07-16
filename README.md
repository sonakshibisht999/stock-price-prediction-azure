# 📈 Stock Price Prediction using Linear Regression

This project aims to predict the *closing price* of Infosys stock using historical data from the *NSE (National Stock Exchange)*. The model leverages features like Open, High, Low, and Volume to forecast the Close price using a *Linear Regression model*.

> 📌 Developed as part of the *Microsoft Azure AI Internship* in collaboration with *Edunet Foundation* and *AICTE*.

---

## 🗃 Dataset

- Source: Official Infosys data from NSE
- Format: .csv
- Features used:
  - OPEN
  - HIGH
  - LOW
  - VOLUME
  - CLOSE (target variable)

---

## 🧠 Tools & Technologies

- Python 3.13
- Jupyter Notebook
- pandas, numpy
- scikit-learn (Linear Regression, train/test split, evaluation)
- matplotlib (visualization)

---

## 🔍 Model Workflow

1. Data Loading & Cleaning
2. Feature Selection (OPEN, HIGH, LOW, VOLUME)
3. Train/Test Split (80/20)
4. Linear Regression Model Training
5. Model Evaluation
6. Visualization of Actual vs Predicted Prices

---

## 📊 Model Evaluation

| Metric | Value |
|--------|-------|
| R² Score | e.g., 0.84 |
| RMSE     | e.g., 12.57 |

📷 *Screenshots*:
- [✔ Actual vs Predicted Graph](screenshots/actual_vs_predicted_chart.png)
- [✔ Model Evaluation Output](screenshots/model_metrics_output.png)

---

## 📂 Project Structure
📁 stock-price-prediction-azure/ ├── infosys_stock_data.csv ├── stock_price_prediction.ipynb ├── Project_Report.pdf ├── Presentation.pptx ├── screenshots/ │   ├── actual_vs_predicted_chart.png │   └── model_metrics_output.png └── README.md
---

## ✅ Outcome

This project demonstrates the application of *basic machine learning* for financial prediction using real-world data. The model's performance shows promising predictive power and provides insight into trends in Infosys stock pricing.

---

## 📌 Author

*Sonakshi Bisht*  
Intern, Microsoft Azure AI Program  
Specialization: MBA – Business Analytics & Finance  
GitHub: [@sonakshibisht999](https://github.com/sonakshibisht999)

---

## 📬 Acknowledgment

This project was completed under the guidance of the *Edunet Foundation* and *AICTE* as part of the *Microsoft Azure AI Internship Program*.
