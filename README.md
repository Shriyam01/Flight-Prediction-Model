# ✈️ Flight Price Prediction System

This repository contains a machine learning-based **Flight Price Prediction System** built using Python and popular ML libraries. It includes two core notebooks:

- `Flight_Regressor_Model.ipynb`: Handles data preprocessing, EDA (Exploratory Data Analysis), and model training.
- `Flight_Prediction_System.ipynb`: Uses the trained model to make real-time predictions based on user input.

---

## 📌 Objective

To build a system that predicts flight prices based on multiple input features such as airline, source, destination, number of stops, departure and arrival times, and journey duration.

---

## 📂 Repository Structure

📁 flight-price-predictor/
├── 📓 Flight_Regressor_Model.ipynb      # Handles data loading, preprocessing, model training, evaluation
├── 📓 Flight_Prediction_System.ipynb    # Uses the trained model to predict flight fares
├── 📦 saved_model.pkl                   # Serialized trained regression model (generated after training)
├── 📄 requirements.txt                  # List of Python dependencies (optional, can be added)
├── 📄 README.md                         # Project documentation (this file)
└── 📂 dataset/                          # Folder for the input CSV file (e.g., train_data.csv)


---

## 🧠 Technologies Used

- Python 🐍
- Jupyter Notebook 📓
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- XGBoost / RandomForest (based on model selection)
- Pickle (for model serialization)

---

## ⚙️ How to Run

1. **Clone the repository:**
   ```
   git clone https://github.com/your-username/flight-price-predictor.git
   cd flight-price-predictor
  q```

2. **Install the dependencies:**
It's recommended to use a virtual environment.
```
pip install -r requirements.txt
```

---
3.**Run the notebooks in order:**
Step 1: Open and run Flight_Regressor_Model.ipynb
- a)Cleans the dataset
- b)Performs feature engineering
- c)Trains multiple regression models
- d)Selects the best model
- e)Saves the model as a .pkl file

Step 2: Open and run Flight_Prediction_System.ipynb
- a)Loads the trained model
- b)Takes user input via widgets or manual code
- c)Predicts flight fare based on input features

---

**📈 Features**
- a)Regression-based fare prediction
- b)Model comparison using R² score and other metrics
- c)User-friendly input format
- d)Real-time prediction using saved model


















