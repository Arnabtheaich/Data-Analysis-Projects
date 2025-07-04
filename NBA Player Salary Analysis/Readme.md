# NBA Player Salary Analysis and Prediction

This project analyzes and predicts NBA player salaries based on physical attributes and categorical features. It uses **data visualization**, **correlation analysis**, **clustering**, and **linear regression modeling**.

## Project Overview

The project is developed in **Google Colab** and includes:

- Exploratory Data Analysis (EDA)
- Correlation heatmap for numeric features
- Clustering players based on physical attributes
- Predictive modeling using Linear Regression
- One-hot encoding of categorical variables (e.g., Position)

## Features Used

The following features are considered for modeling:

- Height (in feet)
- Age
- Weight
- Position (categorical)
- Salary (target variable)

## Files

- `NBA_Salary_Analysis.ipynb`: Main notebook with analysis and model training
- Dataset loaded from CSV (structured with player data including physical stats, position, and salary)

## Technologies Used

- Python 3
- Google Colab
- Pandas
- NumPy
- Seaborn & Matplotlib (for visualization)
- scikit-learn (for preprocessing, clustering, regression)

## Key Methods

- `sns.heatmap()`: Correlation visualization
- `KMeans()`: Clustering players by height and weight
- `LinearRegression()`: Predicting salary using age, height, and position
- `Pipeline`: Combining preprocessing and modeling
- `OneHotEncoder`: Encoding categorical data

## How to Use

1. Open the notebook in [Google Colab](https://colab.research.google.com/drive/1dSxgp_qNHfX5iotYYaLG7XSYUD4AiTtP).
2. Run the cells sequentially.
3. Modify features or model parameters as needed.

## Future Improvements

- Include player performance statistics (e.g., points per game)
- Try different regression models (Random Forest, Ridge, etc.)
- Deploy as a web app using Streamlit or Flask

## Contact

For questions or collaboration, feel free to open an issue or reach out via GitHub.
