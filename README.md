# Data-Driven Airbnb – Data Analytics and Machine Learning  

## Introduction  
This project analyzes Airbnb listings using **data analytics and machine learning** to uncover market insights and predict outcomes such as rental prices and host credibility. By exploring key factors like location, host verification, reviews, and availability, the project provides data-driven recommendations that can help both hosts and guests.  

---

## Dataset  
The dataset includes Airbnb listing details such as:  
- **Id, Name, Host Information**  
- **Neighbourhood Group & Neighbourhood**  
- **Latitude & Longitude**  
- **Room Type, Price, Availability**  
- **Number of Reviews & Review Ratings**  
- **Host Verification Status**  

---

## Project Workflow  

### 1. Data Preprocessing  
- Handled missing values & duplicates  
- Encoded categorical variables  
- Scaled numerical features  
- Removed outliers  

### 2. Exploratory Data Analysis (EDA)  
- Neighborhood & borough analysis  
- Price distribution & trends  
- Room type and availability patterns  
- Correlation analysis (heatmaps & plots)  

### 3. Machine Learning Models  
- **Regression Models** → Predict Airbnb prices  
- **Classification Models** → Analyze host verification & credibility  
- **Model Evaluation** → RMSE, MAE, Accuracy, F1-score  

---

## Key Insights  
- Location, host credibility, and number of reviews significantly influence **pricing & booking trends**.  
- Predictive models provide useful pricing guidance for hosts.  
- Neighborhood-specific analysis highlights areas with **high demand vs. affordability**.  

---

## Tech Stack  
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Environment**: Jupyter Notebook  
- **Techniques**: Data Wrangling, Feature Engineering, Visualization, Regression & Classification  

---

## How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/data-driven-airbnb.git
   cd data-driven-airbnb
   ```  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Open the notebook:  
   ```bash
   jupyter notebook Data_Driven_Airbnb_Group4_Modified.ipynb
   ```  

---

## Future Work  
- Incorporate time-series analysis for seasonal demand forecasting  
- Use advanced ML models (XGBoost, Random Forest)  
- Build a web dashboard for interactive exploration  

---

## Contributor 
- Trupti Lone
