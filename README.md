## **Predictive Sales Analysis for Pharma Products**

Predicting future demand and optimizing inventory management can be done by using historical data of the products, after cleaning the data its ready for applying a range of predictive machine learning algorithms. The main goal is to forecast future demand and predict sales a key insight for managing products. This enables executive management to make informed decisions regarding marketing, promotions, and overall business strategy. What to sell and when to sell it !

**Data**

The data set is taken from kaggle  

url: https://www.kaggle.com/datasets/milanzdravkovic/pharma-sales-data

DOI: 10.34740/kaggle/ds/466126

All rights reserved with original authors.


**DATA DESCRIPTION**
The dataset is taken from kaggle, original author built it from 600000 transactional data points over a timeperiod of 6 years (period 2014-2019), indicating date and time of sale, pharmaceutical drug brand name and sold quantity, exported from Point-of-Sale system in the individual pharmacy. Then the author preprocessed and bunched these 57 drugs into groups of these following Anatomical Therapeutic Chemical (ATC) Classification System categories:

M01AB - Anti-inflammatory and antirheumatic products, non-steroids, Acetic acid derivatives and related substances
M01AE - Anti-inflammatory and antirheumatic products, non-steroids, Propionic acid derivatives
N02BA - Other analgesics and antipyretics, Salicylic acid and derivatives
N02BE/B - Other analgesics and antipyretics, Pyrazolones and Anilides
N05B - Psycholeptics drugs, Anxiolytic drugs
N05C - Psycholeptics drugs, Hypnotics and sedatives drugs
R03 - Drugs for obstructive airway diseases
R06 - Antihistamines for systemic use
Sales data are resampled to the hourly, daily, weekly and monthly periods. Data is already pre-processed, where processing included outlier detection and treatment and missing data imputation.







**Predictive analysis using machine learning**  
Predictive analytics involves analyzing large datasets to identify patterns and predict future outcomes using machine learning algorithms. This document explores multiple machine learning algorithms to achieve the most accurate predictions. 


**1. ARIMA**
-  Stands for AutoRegressive Integrated Moving Average.
-  Ideal for time series forecasting with trend and seasonality.
-  Models relationships between past values and future predictions.
-  Best for datasets with consistent, predictable patterns.
- 
**2. Random Forest**
- Ensemble model using multiple decision trees.
- Handles both classification and regression tasks.
- Reduces overfitting by averaging multiple predictions.
- Robust against noisy data and missing values.
  
**3. Neural Networks**
-  Mimics the human brain's structure for deep learning.
-  Effective for complex, non-linear relationships in data.
-  Learns from large datasets to improve prediction accuracy.
-  Flexible, can be used for time series, classification, and more.


These models are chosen based on their ability to handle time series data and other relevant factors. 

**Data Analysis and Visualization with Python**  
Python is used for both the analysis and visualization of the forecasted data. Python has an advantage over other languages with its already present libraries to analyse data quickly and accurately. Following are a few libraries i will be using;


**1. Pandas**
-  Data manipulation and cleaning.
-  Handles large datasets efficiently.
-  Essential for organizing data before analysis.

  
**2. NumPy**
-  Provides support for numerical computations.
-  Efficiently handles large arrays and matrices.
-  Integral for mathematical operations on data.

  
**3. Scikit-Learn**
-  Implements various machine learning models.
-  Tools for model evaluation and selection.
-  Key for predictive analysis.

  
**4. Statsmodels**
-  Specialized in statistical modeling and time series.
-  Ideal for ARIMA and other forecasting models.
-  Supports hypothesis testing.

  
**5. Matplotlib and Seaborn**
-  Creates clear and informative visualizations.
-  Seaborn has beautiful aesthetics.
-  for presenting data and model results in a visually appealing and understandable manner.

- 
**6. TensorFlow/PyTorch**
-  Used for building and training neural networks.
-  Handles complex models and large datasets.
-  Important for deep learning applications.

### **Benefits of Predictive Sales Forecasting**


**Improved Decision-Making**
-  Helps executive management refine marketing and promotional strategies by providing data-driven insights. (It helps managers decide the best ways to sell products.)
  
  
**Supply and Budget Planning**
-  Ensures a balanced approach to supply and budgeting, avoiding overstock or stockouts in inventory. (It helps prevent buying too much or too little of a product.)
  
  
**Strategic Insights**
-  Provides a clear understanding of the company's business strategy across different regions, aiding in sales improvement. (It shows how well the company is selling in different places, helping to improve sales.)


