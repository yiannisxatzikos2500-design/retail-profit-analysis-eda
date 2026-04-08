# Regional Sales & Profitability Analysis

This project analyzes retail performance data to identify the disconnect between high sales volume and net profitability across different regions and product categories.

## Project Overview
The goal of this analysis is to refine advertising policies and regional sales strategies. By identifying "Profit Killers"—products or regions with high volume but negative margins—we can reallocate marketing resources toward segments that actually drive growth.

## Key Insights
* **The Volume-Profit Gap:** High-volume states like **Texas** and **Pennsylvania** are operating at a net loss, proving that sales growth does not always translate into profit.
* **Regional Anomalies:** While **Binders** are generally a profitable category, they incur major losses in specific regions. 
* **Machine Losses:** The **Machines** category is driving substantial deficits, with the impact being especially severe in **Ohio**.
* **Strategic Targeting:** Analyzing profit by **Region** provides more useful intelligence for the marketing team to target larger, high-efficiency segments rather than individual states.

## Technologies Used
* **Python**
* **Pandas**: For data manipulation and aggregation.
* **Matplotlib / Seaborn**: For data visualization.
* **Jupyter Notebook**: For interactive analysis.

## Analysis Results
The analysis includes several visualizations:
1. **Profit/Loss by State**: Identifying which states are leaders and which are bleeders.
2. **Category Deep-Dives**: Comparing the product mix of profitable states (CA, NY) against loss-making states (TX, OH, PA, IL).
3. **Sales vs. Profit Growth**: Visualizing how sales volume fails to scale with profit in certain territories.

## How to Use
1. Clone the repository.
2. Install requirements: `pip install pandas matplotlib seaborn`.
3. Open the `.ipynb` file in VS Code or Jupyter Notebook.
4. Run the cells to generate the latest profitability reports.
