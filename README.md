# 📊 Japan Life Expectancy - Exploratory Data Analysis (EDA)

## 📌 Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on Japan's **Life Expectancy Dataset** to understand historical trends, correlations, and patterns that influence life expectancy over time. Using Python and data visualization techniques, we analyze key factors and detect anomalies in the dataset.

## 📂 Project Structure
```
📁 Japan-Life-Expectancy-EDA
│── 📄 README.md           # Project documentation (this file)
│── 📄 Japan_Prediction.ipynb  # Jupyter Notebook with EDA
│── 📁 Data/               # Contains the dataset
│── 📁 Images/             # Saved plots and visualizations
│── 📄 requirements.txt    # Python dependencies
│── 📁 Scripts/            # Python scripts for additional analysis
│── 📄 LICENSE             # Project license file
```

## 📊 Dataset
- **File:** `Japan_life_expectancy.csv`
- **Contents:** Historical data on life expectancy in Japan.
- **Key Features:**
  - `Year` → The year of observation.
  - `Life Expectancy` → Average life expectancy in years.
  - `GDP` → Gross Domestic Product per capita.
  - `Population` → Total population count.
  - `Healthcare Expenditure` → Amount spent on healthcare per capita.
  - Other socio-economic factors (if applicable).

## 🔍 Exploratory Data Analysis (EDA) Steps
1. **Data Import & Preprocessing**
   - Load dataset using `pandas`.
   - Inspect missing values and handle them accordingly.
   - Convert data types if necessary.
2. **Statistical Summary**
   - Check data types and basic statistics (`df.describe()`).
   - Identify distributions of key variables.
3. **Trend Analysis**
   - **Line Plots:** Visualizing life expectancy over years.
   - **Bar Charts:** Comparing GDP and healthcare spending over time.
4. **Correlation Analysis**
   - **Heatmaps:** Checking relationships between variables.
   - **Pair Plots:** Examining variable distributions.
5. **Outlier Detection**
   - **Box Plots:** Identifying anomalies in life expectancy values.
   - **Scatter Plots:** Finding unusual patterns.
6. **Geospatial Analysis (Optional)**
   - If applicable, mapping life expectancy trends across different regions of Japan.

## 📈 Sample Visualization
![Life Expectancy Trend]

![image](https://github.com/user-attachments/assets/5dc2dfea-bde9-4831-aa3d-4e1c7dece92e)


## 🚀 How to Run This Project
### 1️⃣ Install Dependencies
Ensure you have Python installed, then run:
```bash
pip install -r requirements.txt
```

### 2️⃣ Run the Jupyter Notebook
```bash
jupyter notebook Japan_pred_EDA.ipynb
```

### 3️⃣ Explore the Data
Follow the step-by-step EDA process inside the notebook.

## 📌 Dependencies
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `jupyter`
- `scipy` (for statistical analysis)
- `plotly` (for interactive visualizations)

## 📌 Future Improvements
✅ Feature Engineering (Adding more relevant columns)  
✅ Predictive Modeling (Regression models to forecast life expectancy)  
✅ Interactive Dashboards using `Plotly`  
✅ Time Series Forecasting using ARIMA or LSTM  
✅ Data Cleaning Automation Scripts  

## ✨ Contributing
Contributions are welcome! Feel free to fork, improve, and submit a PR. 🚀



