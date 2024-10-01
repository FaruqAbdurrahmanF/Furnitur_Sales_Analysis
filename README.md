# Furniture Sales Data Analysis

## Project Description
This project focuses on analyzing furniture sales data using PySpark. It covers data exploration, cleaning, transformation, and visualization of both categorical and numerical data. The project also includes scaling of features and a correlation analysis to better understand relationships between variables.

## Project Structure
- **Data Loading**: Reading the `Furniture.csv` file using PySpark.
- **Data Cleansing**: Removing rows with null values in key columns.
- **Data Transformation**: Adding new columns to analyze the impact of discounts on profit margins.
- **Scaling**: Scaling numerical features in preparation for further analysis.
- **Correlation Analysis**: Computing correlations between numerical variables and generating a correlation heatmap.
- **Data Visualization**: Visualizing the distribution of categorical and numerical features, along with boxplots for numerical data.

## Dependencies
- PySpark
- Seaborn
- Matplotlib
- Pandas

## How to Run the Project
1. Ensure that Spark and Python are installed on your system.
2. Install the required Python dependencies:
   ```
   pip install pyspark seaborn matplotlib pandas
   ```
3. Run `main.py` to perform the analysis.

## Visualizations
The project includes:
- A correlation heatmap to visualize relationships between numerical variables.
- Distribution plots for categorical and numerical features.
- Boxplots to detect outliers in numerical data.
