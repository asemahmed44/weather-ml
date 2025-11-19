
# 🌦️ Weather History Analysis using Python & Machine Learning

This project analyzes historical weather data to understand temperature trends, humidity patterns, wind speed variations, and other meteorological indicators.  
It includes data cleaning, preprocessing, visualization, and applying machine learning models to predict temperature or other weather attributes.

---

## 📌 Project Overview

The goal of this project is to explore historical weather conditions and build machine learning models that can predict future weather values based on previous observations.

The analysis includes:

- Temperature trends  
- Humidity & wind speed distribution  
- Missing value treatment  
- Feature engineering  
- ML model training & evaluation  

---

## 📂 Dataset Used

Dataset Source: **Kaggle – Weather Dataset**

🔗 https://www.kaggle.com/datasets/muthuj7/weather-dataset

The dataset includes:

- Formatted Date  
- Temperature (C°)  
- Apparent Temperature  
- Humidity  
- Wind Speed  
- Visibility  
- Pressure  
- Daily Summary  

Contains thousands of weather observations across multiple years.

---

## 🛠️ Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook / Script  

---

## 🧹 Data Preprocessing

✔ Converted date column to datetime  
✔ Handled missing values  
✔ Converted numeric columns to proper types  
✔ Generated new features (Month, Year, Day)  
✔ Normalized/Standardized necessary columns  
✔ Prepared dataset for ML models  

---

## 🔍 Analysis Steps

### **1️⃣ Load the Dataset**
Explore data types, descriptive stats, and missing values.

### **2️⃣ Clean & Process Weather Data**
- Remove duplicates  
- Fix formats  
- Extract time-based features  

### **3️⃣ Exploratory Data Analysis**
Includes graphical analysis for:

- Temperature over time  
- Humidity distribution  
- Wind speed variation  
- Monthly/seasonal trends  

### **4️⃣ Machine Learning Preparation**
Selected features include:

- Temperature  
- Humidity  
- Wind Speed  
- Pressure  
- Visibility  
- Date-based features  

---

## 🤖 Machine Learning Model

A **Linear Regression** model was implemented to predict temperature (or other weather metrics).

Model steps:

1. Feature selection  
2. Train-test split  
3. Fit the regression model  
4. Evaluate performance using:  
   - Mean Squared Error (MSE)  
   - R² Score  

---

## 📊 Key Insights

- Clear temperature patterns across months and seasons  
- Humidity has strong influence on apparent temperature  
- Wind speed and pressure show predictable trends  
- Linear Regression provides a solid baseline for weather prediction  

---

## 🚀 How to Run the Project

### **Install Dependencies**

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
````

### **Run the Script**

```bash
python weatherhistory.py
```

The script will:

* Load & clean data
* Generate visualizations
* Train the ML model
* Print evaluation metrics

---

## 📁 Project Structure

```
weather-history-analysis/
│── weatherhistory.py
│── weatherHistory.csv  (from Kaggle)
│── README.md
```

---

## 📬 Contact

Created by **Asem Ahmed**

# 🔥 جاهز لأي مشروع تاني  
ابعتلي المشروع اللي بعده — وأنا أعمل لك README بنفس المستوى أو أحسن 💯
```
