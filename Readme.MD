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
_Auto-extracted from the notebook for better clarity and flow._

### 📊 Data Exploration & Cleaning
<img src="images_ucp/plot_01.png" alt="EDA 1" width="400"/> <img src="images_ucp/plot_02.png" alt="EDA 2" width="400"/>
<img src="images_ucp/plot_03.png" alt="EDA 3" width="400"/>

### 🔍 Feature Correlation & Importance
<img src="images_ucp/plot_04.png" alt="Feature view 1" width="400"/> <img src="images_ucp/plot_05.png" alt="Feature view 2" width="400"/>
<img src="images_ucp/plot_06.png" alt="Feature view 3" width="400"/>

### 🤖 Model Training & Evaluation
<img src="images_ucp/plot_07.png" alt="Training/Eval 1" width="400"/> <img src="images_ucp/plot_08.png" alt="Training/Eval 2" width="400"/>
<img src="images_ucp/plot_09.png" alt="Training/Eval 3" width="400"/>

### 📈 Predictions & Results
<img src="images_ucp/plot_10.png" alt="Predictions 1" width="400"/> <img src="images_ucp/plot_11.png" alt="Predictions 2" width="400"/>
<img src="images_ucp/plot_12.png" alt="Predictions 3" width="400"/>

**Results:**
- Best model: **Random Forest Regressor**
- Achieved **R² Score: ~0.92**
- Key factors affecting price: **Present Price**, **Car Age**, **Kms Driven**, **Fuel Type**


