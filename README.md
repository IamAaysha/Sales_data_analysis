# Sales Data Analysis with Python  

## Project Overview  
This project analyzes sales data to uncover insights into product sales trends, revenue generation, and customer purchasing behavior. Using Python and key data analysis libraries like Pandas, NumPy, and Matplotlib, the dataset is processed, cleaned, and visualized to derive meaningful conclusions.  

## Key Features & Analysis  
- **Data Acquisition & Preprocessing**  
  - Downloaded dataset using `kagglehub` and loaded it into a Pandas DataFrame.  
  - Cleaned data by handling missing values and converting data types.  
  - Added new columns such as `Revenue`, `Year`, `Month`, and `Day` for deeper insights.  

- **Exploratory Data Analysis (EDA)**  
  - Identified top-selling products by quantity sold.  
  - Determined highest revenue-generating products.  
  - Analyzed monthly sales performance to identify peak sales months.  
  - Examined daily sales trends to find the most profitable day.  
  - Calculated the average revenue per transaction.  

- **Data Visualization**  
  - Bar charts for top-selling products and highest revenue-generating products.  
  - Line and scatter plots to analyze sales trends over time.  
  - Monthly revenue breakdown using bar charts.  

## Tools & Technologies Used  
- Python  
- Pandas & NumPy (Data manipulation and analysis)  
- Matplotlib (Data visualization)  
- Google Colab (Development environment)  
- Kaggle API (Dataset access)  

## Insights Gained  
- The AAA Batteries (4-pack) had the highest sales by quantity.  
- MacBook Pro Laptop generated the most revenue.  
- December had the highest total sales revenue.  
- The peak sales day was April 22, 2019.  
- The average revenue per transaction was $185.49.  

## How to Run the Project  
1. Clone this repository:  
   ```bash
   git clone <repository_url>
   cd <project_directory>
   ```
2. Open the Jupyter Notebook or Google Colab.  
3. Install dependencies (if required):  
   ```bash
   pip install pandas numpy matplotlib kagglehub
   ```
4. Run the script to generate insights and visualizations.  

## Future Enhancements  
- Perform time-series forecasting to predict future sales.  
- Use machine learning models to identify key factors affecting revenue.  
- Analyze customer buying patterns for targeted marketing strategies.  
