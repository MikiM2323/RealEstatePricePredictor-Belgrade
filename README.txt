Real Estate Price Predictor Belgrade

Overview
- Collected and cleaned over 10,000 real estate listings from a popular Serbian real estate website using Python.
- Built a machine learning model to predict apartment prices using regression and clustering techniques.
- Achieved high prediction accuracy through iterative model tuning and feature engineering.
- Evaluated model performance using R-squared (82%) and RMSE for interpretability and predictive power.

Dataset
- Features Used:
  - Price (€)
  - Size (m²)
  - Location (clustered using K-Means)
  - Number of Rooms (later determined to be causing high multicollinearity, and in the end not being used)
  - Title (scraped but not used in modeling)
- Data Storage: CSV format
- Data Cleaning: Handled missing values, outliers, and formatted categorical features

Machine Learning Approach
- Clustering: K-Means (to classify locations)
- Prediction Model: Linear Regression
- Performance: R² ≈ 82%

Installation & Usage
1. Clone the repository:
   git clone https://github.com/YOUR-USERNAME/RealEstatePricePredictor-Belgrade.git
   cd RealEstatePricePredictor-Belgrade

2. Environment Setup
   - This project was developed using Anaconda’s general virtual environment.
   - Open the project in Jupyter Notebook through Anaconda and run the code.

Future Improvements
- Incorporate additional features (e.g., floor level, property age, neighborhood data)
- Optimize clustering to improve location classification
- Experiment with advanced models (XGBoost, Random Forest, etc.)

Disclaimer
- The dataset was scraped from a popular real estate website in Serbia for research purposes.
- The scraping script is private and not included in this repository.
- If you use or modify this project, please ensure compliance with data usage policies and ethical guidelines.