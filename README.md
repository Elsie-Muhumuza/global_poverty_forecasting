# 🌍 Predicting Global Poverty with Machine Learning

## 📌 Project Overview
This project applies machine learning to **predict a country’s Human Development Index (HDI)**, a key measure of health, education, and living standards.  
The work is motivated by the **United Nations’ Sustainable Development Goals (SDGs)** and the need for **evidence-based policymaking** in tackling global poverty.  

By forecasting HDI trends, the model can help governments and international agencies:
- Anticipate development challenges
- Test the impact of different policy decisions
- Allocate resources more effectively  

---

## 📊 Dataset
- **Source:** [World Bank World Development Indicators (WDI)](https://databank.worldbank.org/source/world-development-indicators)  
- **Coverage:** 200+ countries, 50+ years of data  
- **Size:** ~1,500 indicators (economic, health, education, environment, trade, etc.)  
- **Target Variable:** Human Development Index (HDI)  
- **Features:** Selected socio-economic and health indicators (GDP per capita, education expenditure, life expectancy, etc.)  

---
## Team Work

### Collaborators

- [Elsie Muhumuza](https://github.com/Elsie-Muhumuza)
- [Nanyonga Pervin](https://github.com/pervincathie)
- [Nakiwala Jemimah Kuteesa](https://github.com/njemmie)
- [Nakimuli Claire](https://github.com/nasclaire08)
- [Naluyima Jackline](https://github.com/jeanjackie)
- [Joan Ahereza](https://github.com/JoanAhereza23)
  

#### Roles
Data sourcing: Joan, Claire, Jemmie, Pervin, Elsie, Jackie
Data Cleaning: Elsie, Jackie
Data Visualization: Elsie, Pervin, Jemmie
Models: Elsie, Pervin, Jackie
Documentation: Elsie, Pervin, Claire, Jackie
PowerPoint Slides: Jemmie
Presentation: All members

#### Collaboration: 
Shared Colab, no major disagreements, resolved blockers via daily check-ins.

#### Shared Understanding
Each explained another's work

---

## 🛠️ Methods
1. **Data Preparation**
   - Handle missing values
   - Feature engineering (e.g., lag features for time series)
   - Normalization & scaling  

2. **Exploratory Data Analysis (EDA)**
   - Trends in HDI distribution
   - Correlations between indicators
   - Univariate & multivariate visualizations  

3. **Modeling**
   - Random Forest, Linear Regression, Random Forest, XGBoost, 
 XGBoost (classical ML approach)  
   - Neural Network (deep learning approach)  

4. **Evaluation Metrics**
   - MAE (Mean Absolute Error)  
   - RMSE (Root Mean Square Error)  
   - R² (explained variance)  

---

## 📈 Results
- Both models were tested and compared on performance and interpretability.  
- Random Forest provided interpretable insights into **which features matter most** (e.g., education spending, life expectancy).  
- Neural Networks captured more complex patterns but required careful tuning to avoid overfitting.  

---
 ## 🖼️ **Visuals:**
### Distribution of HDI
![Distribution of HDI](https://raw.githubusercontent.com/Elsie-Muhumuza/global_poverty_forecasting/main/images/distribution_of_hdi.png)

### Correlation Heatmap of WDI Indicators
![Correlation Heatmap of WDI Indicators](https://github.com/Elsie-Muhumuza/global_poverty_forecasting/blob/main/images/correlation_heatmap_of_all_indicators.png)

### Feature Importance from Random Forest Regression
![Feature Importance from Random Forest Regression](https://github.com/Elsie-Muhumuza/global_poverty_forecasting/blob/main/images/feature_importance.png
)

### Training Vs Validation of Neural Networks
![Training Vs Validation](https://github.com/Elsie-Muhumuza/global_poverty_forecasting/blob/main/images/training_vs_validation_loss_plot.png)

### SHAP plot from Neural Networks
![SHAP plot](images/SHAP plot.png)

### Model Performance Comparison
![Model Performance Comparison](https://github.com/Elsie-Muhumuza/global_poverty_forecasting/blob/main/images/model_performance_comparison.png)

---
     
## 🌟 Impact
The project demonstrates how machine learning can be applied to:
- Provide **early-warning systems** for countries at risk of falling behind  
- Support **policy simulation** (e.g., effects of investing more in healthcare or education)  
- Contribute to **transparent, data-driven development planning**
- Guide resource allocation toward the most impactful areas
- Enable targeted aid for countries at risk
- Act as a data validation and cost-effective estimation tool
- Promote accountability and progress monitoring through explainable predictions

---



 
