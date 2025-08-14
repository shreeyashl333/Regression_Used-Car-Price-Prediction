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

## 📌 

# 🚗 Used Car Price Prediction

This project predicts used car prices using regression techniques, with a clear focus on data exploration, feature analysis, and model evaluation.

---

### 📊 Data Exploration & Cleaning

<img src="images_ucp/plot_01.png" alt="plot_01.png" width="400"/> <img src="images_ucp/plot_02.png" alt="plot_02.png" width="400"/>

<img src="images_ucp/plot_03.png" alt="plot_03.png" width="400"/>



### 🔍 Feature Correlation & Importance

<img src="images_ucp/plot_04.png" alt="plot_04.png" width="400"/> <img src="images_ucp/plot_05.png" alt="plot_05.png" width="400"/>

<img src="images_ucp/plot_06.png" alt="plot_06.png" width="400"/>



### 🤖 Model Training & Evaluation

<img src="images_ucp/plot_07.png" alt="plot_07.png" width="400"/> <img src="images_ucp/plot_08.png" alt="plot_08.png" width="400"/>

<img src="images_ucp/plot_09.png" alt="plot_09.png" width="400"/>



### 📈 Predictions & Results

<img src="images_ucp/plot_10.png" alt="plot_10.png" width="400"/> <img src="images_ucp/plot_11.png" alt="plot_11.png" width="400"/>

<img src="images_ucp/plot_12.png" alt="plot_12.png" width="400"/>




Results
- Best model: **Random Forest Regressor**
- Achieved **R² Score: ~0.92**
- Key factors affecting price: **Present Price**, **Car Age**, **Kms Driven**, **Fuel Type**
