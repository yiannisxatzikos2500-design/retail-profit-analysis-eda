# Superstore Sales & Customer Analysis

This project provides a comprehensive analysis of the "Sample - Superstore" dataset. It involves data cleaning, exploratory data analysis (EDA), and customer segmentation to identify profit drivers and loss-making areas.

## Project Overview
The primary goal is to analyze sales, profit, and customer behavior across different product categories and regions. The analysis highlights specific areas of concern, such as losses in "Tables" and "Bookcases," and utilizes clustering to segment customers into value-based groups.

## Key Features
* **Data Preparation**: Handling date conversions, cleaning column names, and verifying dataset integrity.
* **Exploratory Data Analysis (EDA)**: Visualizing sales trends and profit margins by Category, Sub-Category, and Region.
* **Customer Segmentation**: Identifying high-value "Whale" customers versus low-value segments to better target marketing efforts.
* **Profit Gap Analysis**: Investigating why certain segments and products (like Machines and Tables) are underperforming.

## Key Insights
* **The "Profit Leak"**: High sales in Tables and Bookcases often result in a net loss due to high discounts or low margins.
* **The Machine Gap**: Identified a significant profit gap in certain machine sales between low-value customer segments and top-tier customers.
* **Customer Distribution**: California, New York, and Washington are identified as high-activity states.

## Technologies Used
* Python
* Pandas (Data Manipulation)
* Matplotlib & Seaborn (Data Visualization)
* Scikit-learn (Customer Clustering/Segmentation)
* Jupyter Notebook

## How to Run
1. Clone this repository.
2. Ensure you have the `Sample - Superstore.csv.csv` file in the same directory as the notebook.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
