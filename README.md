# Pharma-business-sales-Analysis
This project involves an in-depth analysis of a pharmaceutical business dataset to derive insights into sales trends, product performance, and market segmentation. It showcases skills in data exploration, visualization, statistical analysis, and predictive modeling.

## Objectives
- **Exploratory Data Analysis (EDA)**: Understand data distribution and trends.
- **Data Visualization**: Illustrate key insights using effective charts.
- **Sales Performance Analysis**: Identify top-performing products and regions.
- **Market-Specific Analysis**: Uncover regional revenue trends.
- **Time-Based Seasonality Analysis**: Examine seasonality in sales.
- **Product Revenue and Quantity Correlation**: Analyze relationships between revenue and sales quantity.
- **Predictive Modelling**: Implement linear regression and decision trees for forecasting.
- **Time Series Forecasting**: Predict future sales trends.
- **K-Means Clustering**: Segment sales data to identify patterns.

## Tools and Technologies Used
- **Python**: Core language for analysis.
- **Pandas & NumPy**: Data manipulation.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning models.
- **Statsmodels**: Time series forecasting.
- **Jupyter Notebook**: Coding and documentation.

## Key Analyses and Models
### 1. Exploratory Data Analysis
- Initial data exploration to summarize and clean the dataset.

### 2. Data Visualization
- Created bar plots, scatter plots, and time series charts to highlight key trends.

### 3. Sales Performance Analysis
- Analyzed revenue and sales quantity by product and country.

### 4. Market-Specific Analysis
- Investigated revenue contributions by region.

### 5. Time-Based Seasonality Analysis
- Detected seasonal trends in sales data.

### 6. Product Revenue and Quantity Correlation
- Explored correlations between product sales and revenue.

### 7. Predictive Modelling
- Applied linear regression and decision trees for future sales prediction.

### 8. Time Series Forecasting
- Used time series models to forecast future revenue.

### 9. K-Means Clustering
- Clustered sales data to segment products and regions based on performance.

## Sample Code
```python
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression

# Load the dataset
df = pd.read_excel('/kaggle/input/pharmaceutical-business-dataset/Business dataset.xlsx')
print(df.head())
```

## How to Run
1. Clone the repository.
2. Run `pip install -r requirements.txt` to install dependencies.
3. Open and run the Jupyter Notebook.

## Future Enhancements
- **Interactive Dashboards**: Enhance with tools like Plotly.
- **Advanced Models**: Implement deeper machine learning models for prediction.

## Author
Mwende Mutuku

