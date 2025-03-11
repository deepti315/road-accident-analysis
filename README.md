# Road Accident Analysis & Prediction

## Project Objective
Road accidents are a major global concern, causing thousands of deaths and injuries each year. This project aims to analyze road accident data using **Python, SQL, and Machine Learning** to:
- Identify key factors contributing to road accidents.
- Visualize accident trends using data analysis techniques.
- Predict accident severity using Machine Learning models.

---

## Dataset Details
The dataset used for this project contains information on road accidents, including:
- **Date & Time** of the accident
- **Location** (latitude, longitude, city, etc.)
- **Weather Conditions** (rain, fog, snow, etc.)
- **Road Conditions** (wet, dry, icy, etc.)
- **Vehicle & Driver Details** (speed, vehicle type, driver behavior)
- **Severity** (minor, serious, fatal)

### Dataset Source:
- [https://www.kaggle.com/datasets/tsiaras/uk-road-safety-accidents-and-vehicles]
- If dataset is too large, download from [Google Drive](#) or [Kaggle](#)

---

## Steps of Analysis & Prediction
### **1. Data Collection & Cleaning**
- Load dataset using **Pandas**
- Handle missing values and duplicates
- Convert categorical data into numerical format

### **2. Exploratory Data Analysis (EDA)**
- Visualize accident trends over time
- Identify accident-prone areas using **geospatial mapping**
- Find correlations between weather, road conditions, and accidents

### **3. Data Preprocessing**
- Feature selection and engineering
- Train-test split for machine learning models
- Normalize data where necessary

### **4. Machine Learning Model for Prediction**
- **Logistic Regression** for accident severity classification
- **Random Forest** and **XGBoost** for better accuracy
- Model evaluation using **Accuracy, Precision, Recall, F1-score**

### **5. Insights & Conclusion**
- Key findings from data analysis
- Important factors influencing accidents
- Recommendations for reducing accidents

---

## How to Run the Code
1. Clone this repository:
   ```sh
   git clone https://github.com/deepti315/road-accident-analysis.git
   cd road-accident-analysis
   ```

2. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

3. Run Jupyter Notebook:
   ```sh
   jupyter notebook
   ```

4. Open the `road_accident_analysis.ipynb` file and execute the cells step-by-step.

---

## Dependencies
Make sure you have the following Python libraries installed:
```sh
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
folium  # For geospatial mapping
``` 
Install all dependencies using:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn xgboost folium
```

---

## Results & Visualization
- Heatmaps and bar charts for accident trends
- Geospatial accident mapping
- ML model predictions for accident severity

---

## Contributors
- **Deepti** ([@deepti315](https://github.com/deepti315))

If you have any questions, feel free to raise an issue! 🚀
