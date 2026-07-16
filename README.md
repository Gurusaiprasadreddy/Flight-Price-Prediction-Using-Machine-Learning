# ✈️ Flight Price Prediction Using Machine Learning

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Project Overview

Flight ticket prices vary based on several factors such as airline, journey date, departure time, arrival time, duration, route, and number of stops. Predicting airfare accurately can help travelers make informed booking decisions and assist airlines in optimizing pricing strategies.

This project develops a **Machine Learning Regression Model** that predicts airline ticket prices using historical flight booking data. The project follows a complete **Predictive Analytics Workflow**, including:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Machine Learning Model Development
- Model Evaluation
- Prediction on Unseen Data

---

# 🎯 Project Objective

The objective of this project is to build a predictive analytics model capable of estimating airline ticket prices using historical flight booking data.

The project demonstrates practical implementation of:

- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Regression Algorithms
- Model Evaluation
- Prediction

---

# 📂 Dataset Information

**Dataset Source**

- Kaggle Flight Fare Prediction Dataset

**Files**

```
Data_Train.xlsx
Test_set.xlsx
Sample_submission.xlsx
```

**Dataset Size**

| Description | Value |
|------------|-------|
| Training Records | 10,683 |
| Features | 11 |
| Target Variable | Price |

---

# 📊 Features Used

- Airline
- Date of Journey
- Source
- Destination
- Route
- Departure Time
- Arrival Time
- Duration
- Total Stops
- Additional Information

Target Variable

```
Price
```

---

# ⚙️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Joblib

---

# 🧠 Machine Learning Models

The following regression models were implemented and compared:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Among all models, **Random Forest Regressor** achieved the best performance.

---

# 🔄 Project Workflow

```
Historical Flight Data
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Encoding
        │
        ▼
Train-Test Split
        │
        ▼
Machine Learning Models
        │
        ▼
Model Evaluation
        │
        ▼
Prediction
```

---

# 📈 Exploratory Data Analysis

Several visualizations were created to better understand the dataset, including:

- Flight Price Distribution
- Airline Distribution
- Airline vs Ticket Price
- Source Airport Distribution
- Destination Distribution
- Total Stops Distribution
- Ticket Price by Journey Month
- Flight Duration Distribution
- Duration vs Ticket Price
- Correlation Heatmap
- Outlier Detection
- Feature Importance

---

# 📉 Model Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics helped compare the prediction performance of different regression models.

---

# 🏆 Project Results

The Random Forest Regressor outperformed the other models by providing:

- Lowest Mean Absolute Error
- Lowest Root Mean Squared Error
- Highest R² Score

The model successfully predicts airline ticket prices with high accuracy.

---

# 📁 Repository Structure

```
Flight-Price-Prediction-Using-Machine-Learning/

│

├── dataset/
│   ├── Data_Train.xlsx
│   ├── Test_set.xlsx
│   └── Sample_submission.xlsx
│
├── notebook/
│   └── Flight_Price_Prediction.ipynb
│
├── images/
│   ├── flight_price_distribution.png
│   ├── airline_distribution.png
│   ├── airline_vs_price.png
│   ├── duration_vs_price.png
│   ├── correlation_heatmap.png
│   ├── feature_importance.png
│   └── model_comparison.png
│
├── models/
│   ├── Flight_Price_Prediction_Model.pkl
│   └── Model_Features.pkl
│
├── outputs/
│   ├── Flight_Price_Predictions.csv
│   ├── Model_Comparison.csv
│   └── Processed_Flight_Dataset.csv
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/Gurusaiprasadreddy/Flight-Price-Prediction-Using-Machine-Learning.git
```

---

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Flight_Price_Prediction.ipynb
```

Run all cells sequentially.

---

# 📦 Required Libraries

```
numpy
pandas
matplotlib
seaborn
scikit-learn
openpyxl
joblib
```

---

# 💡 Key Insights

- Airline selection significantly affects ticket prices.
- Flight duration has a strong positive relationship with airfare.
- Journey month influences ticket pricing due to seasonal demand.
- Flights with multiple stops exhibit different pricing patterns.
- Departure and arrival times contribute to price variations.

---

# 🚀 Future Improvements

Future enhancements may include:

- Hyperparameter Tuning
- XGBoost
- LightGBM
- CatBoost
- Streamlit Web Application
- Real-Time Flight Price Prediction
- API Integration
- Automated Model Retraining

---

# 📚 Learning Outcomes

This project demonstrates practical experience in:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Regression Modeling
- Machine Learning
- Predictive Analytics
- Data Visualization
- Model Evaluation
- Python Programming

---

# 👨‍💻 Author

**Guru Sai Prasad Reddy**

B.Tech Computer Science and Engineering

Amrita Vishwa Vidyapeetham

GitHub

https://github.com/Gurusaiprasadreddy

LinkedIn

(Add your LinkedIn profile here)

---

# ⭐ If you found this project useful, consider giving it a star!
