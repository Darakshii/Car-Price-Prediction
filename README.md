# Car-Price-Prediction

Project Flow - Start -> Data Collection and Preprocessing -> EDA -> Feature Engineering -> Model Building and Selection -> Model Evaluation -> Business Impact -> End

**Problem Statement**:
- Developed a predictive model to help an Automobile Company understand the factors influencing car prices in the US market.
- Conducted comprehensive EDA, visualizing data through 20+ plots to uncover insights.
- Discovered strong correlations between 'enginesize,' 'horsepower,' and 'price' (correlation coefficients above 0.8).

**Data Collection and Preprocessing**:
- Collected a large dataset of cars across the American market.
- Preprocessed the data by handling missing values, encoding categorical variables, and creating new features such as 'fueleconomy' and 'carsrange.'

**Exploratory Data Analysis (EDA)**:
- Utilized various EDA techniques including histograms, box plots, and correlation heatmaps to gain insights into the dataset.
- Identified outliers and handled them appropriately to ensure data quality.

**Feature Engineering using RFE**:
- Engineered features by creating dummy variables for categorical features and scaling numerical features using MinMaxScaler.
- Employed Recursive Feature Elimination (RFE) to select relevant features for model building.

**Model Building and Selection**:
- Built multiple linear regression models using RFE-selected features to predict car prices.
- Refinement of models involved dropping insignificant variables based on statistical analysis (e.g., p-values, VIF).

**Model Evaluation**:
- Evaluated model performance using metrics such as R-squared value, F-statistic, and residual analysis.
- Ensured model robustness and validity through rigorous testing on the test dataset.

**Business Impact**:
- Derived actionable insights from the model, aiding Geely Auto in strategic decision-making and pricing strategies in the US market.
- Demonstrated the ability to translate data-driven findings into actionable business recommendations.

**Skills and Tools**:
- Utilized Python programming language along with libraries such as pandas, NumPy, scikit-learn for data manipulation, analysis, and modeling.
- Leveraged data visualization tools like Matplotlib and Seaborn for visualizing insights from the data.
- Applied statistical techniques, machine learning algorithms, and feature engineering methodologies to solve complex business problems.

**Challenge faced**:
During the Car Price Prediction project, I encountered a challenge related to feature selection. It was crucial to identify the most relevant features that significantly influenced car prices for accurate model predictions. To overcome this challenge, I employed the Recursive Feature Elimination (RFE) technique. RFE automatically selects the top features based on their importance, leading to improved model performance and accuracy. This approach not only addressed the feature selection challenge but also enhanced the overall effectiveness of the predictive model.
