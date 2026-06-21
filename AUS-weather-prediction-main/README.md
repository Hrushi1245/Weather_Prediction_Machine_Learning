# 🌧️ AUS-weather-prediction : Predicting Rainfall with Machine Learning  

This project applies **Machine Learning** to the [Australian Weather Dataset](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package) to **predict rainfall for the next day**.  
It covers everything from **data preprocessing and visualization** to **feature engineering, model training, and evaluation**.  

---

## 📊 Dataset Overview
- **Source**: kaggle 
- **Features**:  
  - Temperature, Humidity, Wind Speed, Air Pressure, Cloud Cover, etc.  
- **Target Variable**: `RainTomorrow` (Yes/No)  

---

## ⚙️ Workflow
1. **Data Collection & Cleaning**  
   - Load dataset  
   - Handle missing values  
   - Convert categorical variables  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution plots  
   - Correlation heatmaps  
   - Rainfall patterns across regions  

3. **Feature Engineering**  
   - Encoding categorical data  
   - Scaling numerical features  
   - Creating new derived features  

4. **Modeling**  
   - Logistic Regression  
   - Decision Tree Classifier  
   - Random Forest Classifier  

5. **Evaluation**  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion Matrices  
   - Feature Importance Analysis  

---

## 🚀 Results
- **Best Model**: Random Forest Classifier  
- **Insights**:  
  - Humidity and cloud cover are strong predictors of rainfall.  
  - Logistic Regression performed well but lacked complexity for non-linear relationships.  

📈 Random Forest delivered the **highest accuracy and balanced performance** across metrics.  

---

## 🛠️ Tech Stack
- **Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Tools**: Jupyter Notebook, Git, GitHub  

---

## 💻 How to Run
```bash
# Clone the repository
cd AUS-weather-prediction

# (Optional) create virtual environment
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt

# Run Notebook
jupyter notebook FinalProject_AUSWeather.ipynb
```

---

## 📌 Future Improvements

- Perform hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
- Try Gradient Boosting / XGBoost models
- Deploy model as a Streamlit app for real-time rainfall prediction
- Integrate with live weather APIs

## 👨‍💻 Author

Developed by Hrushikesh Sarvade

---

## 🔖 Keywords  
Machine Learning · Rainfall Prediction · Australian Weather Dataset · Random Forest · Logistic Regression · Decision Trees · Data Science
