# 🚗 Used Car Price Prediction

A Machine Learning project to predict the **selling prices** of used cars based on various attributes such as brand, year, mileage, fuel type, and transmission.  
The project demonstrates **data preprocessing**, **exploratory data analysis (EDA)**, **feature engineering**, and **regression modeling**.

---

## 📂 Dataset
The dataset used: **Used Car Prices.csv**  
It contains information such as:
- Car brand & model
- Year of manufacture
- Present price
- Kms driven
- Fuel type
- Transmission type
- Owner count
- Selling price (target)

---

## 🛠 Tech Stack
- **Python**
- **Pandas / NumPy**
- **Matplotlib / Seaborn** (Data Visualization)
- **Scikit-learn** (Modeling & Evaluation)

---

## 📊 Workflow
1. **Data Loading & Cleaning**
   - Handle missing values
   - Convert categorical features into numeric form
2. **Exploratory Data Analysis**
   - Correlation heatmaps
   - Price trends by brand, age, fuel type, etc.
3. **Feature Engineering**
   - Car age calculation
   - Encoding categorical variables
4. **Modeling**
   - Linear Regression
   - Random Forest Regressor
   - XGBoost Regressor
5. **Evaluation**
   - R² Score
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)

---

## 📈 Key Visualizations
### Price Distribution
![Price Distribution](images/price_distribution.png)

### Correlation Heatmap
![Correlation Heatmap](images/correlation_heatmap.png)

### Feature Importance (Random Forest)
![Feature Importance](images/feature_importance.png)

---

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/yourusername/Used-Car-Price-Prediction.git
cd Used-Car-Price-Prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Used_Car_Price_Prediction_Regression.ipynb
```

---

## 📌 Results
- Best model: **Random Forest Regressor**
- Achieved **R² Score: ~0.92**
- Key factors affecting price: **Present Price**, **Car Age**, **Kms Driven**, **Fuel Type**

---

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
