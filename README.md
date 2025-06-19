# Housing Prices Prediction using Regression
This project builds a Machine Learning pipeline to predict house sale prices based on real-world housing data. The goal is to create a robust model capable of accurately estimating property values based on multiple structural, geographical, and qualitative features.

## Key Highlights
End-to-end pipeline: from data cleaning and feature engineering to model evaluation and final pipeline deployment.

Comprehensive exploratory data analysis (EDA) performed on both numerical and categorical features.

Multiple regression models tested and compared: Linear, Ridge, Lasso, ElasticNet.

ElasticNet selected as the final model after achieving the best balance of bias and variance.

Final model packaged into a fully reusable Scikit-learn pipeline, ready for production use.

Achieved strong prediction accuracy:

R²: 0.9075 (explaining ~91% of price variability)

MAE: $15,462 (only ~8.5% average error relative to mean price)

# Dataset Features
The dataset includes 80+ features covering:

Lot size, frontage, and land attributes

House configuration: rooms, floors, basements, garages, porches

Year built, renovations, construction materials

Neighborhood and location

Overall quality, exterior and interior condition ratings

Target variable: SalePrice (continuous)

# Tools & Libraries
Python Pandas NumPy Scikit-learn Seaborn Matplotlib
