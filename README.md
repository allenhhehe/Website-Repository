# California Housing Price Prediction (End-to-End ML Project)

This project builds a complete Machine Learning pipeline to predict median house values in California using the classic **California Housing Dataset** (sklearn).

## 🚀 Project Features

### ✔ 1. Exploratory Data Analysis (EDA)
- Feature distributions
- Correlation heatmap
- Outlier inspection
- Discussion on feature importance

### ✔ 2. Data Preprocessing
- Train/Test split  
- Custom StandardScaler (written from scratch)  
- Normalization and scaling  
- Target analysis  

### ✔ 3. Model Training (Two Approaches)
#### ① **Linear Regression from Scratch**
- Manual implementation of:
  - Cost function (MSE)
  - Gradient Descent
  - Parameter updates
  - Convergence curve

#### ② **scikit-learn LinearRegression**
- Used for comparison
- Evaluation vs scratch model

### ✔ 4. Evaluation Metrics
- MSE  
- RMSE  
- MAE  
- Residual plots  
- Predicted vs True visualization  

### ✔ 5. Figures & Visualizations
- Loss/cost curve  
- Prediction scatter plot  
- Residual distribution  

---

## 🧩 Project Structure
housing_pred/
│
├── data.py
├── preprocess.py
├── model_scratch.py
├── train.py  
├── evaluate.py
└── plots.py
├── requirements.txt
└── README.md

---

## 🛠 How to Run

Install dependencies:

pip install -r requirements.txt

Train the model:

python -m src.train

Generate evaluation plots:

python -m src.plots

---

## 📌 Future Improvements
- Add RandomForest and GradientBoosting models
- Add hyperparameter tuning
- Add modular config (YAML)
- Convert pipeline to sklearn Pipeline API
- Deploy prediction API using Flask/FastAPI

---

## 📚 Purpose
This project demonstrates:
- ML fundamentals  
- Understanding of EDA  
- Data preprocessing  
- Gradient Descent mathematics  
- Model evaluation  
- Clean code & engineering structure  

Suitable for ML Engineer / Data Analyst job screening.

