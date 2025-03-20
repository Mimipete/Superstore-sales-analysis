# Superstore Sales Analysis

## Project Overview
This project analyzes sales data from a Superstore dataset to identify key factors affecting profitability, sales performance, and loss-making orders. The analysis explores relationships between discounts, shipping costs, and regional sales to derive actionable business insights.

## Project Objectives
- Identify key factors contributing to **loss-making orders**, including discounts and shipping costs.
- Analyze the impact of **discounts on sales and profits** using correlation analysis.
- Determine the **most and least profitable regions** based on sales performance.
- Use **visualizations** to present trends and relationships within the dataset.
- Provide **actionable insights** for optimizing discount strategies and improving overall profitability.

## Data Sources
The dataset includes sales transaction data from a retail superstore, containing information such as:
- **Order details**: Order ID, Date, Category, Sub-category
- **Sales information**: Sales, Profit, Quantity, Discount
- **Customer data**: Customer ID, Segment, Region
- **Shipping details**: Ship Mode, Shipping Cost

## Analysis Performed
- **Exploratory Data Analysis (EDA)**: Identified patterns and outliers in sales and profitability.
- **Correlation Analysis**: Measured relationships between profit, discount, sales, and shipping costs.
- **Visualization**:
  - Bar charts to show average discounts by region.
  - Heatmaps for correlation analysis.
  - Other plots to compare regional sales and profitability.

## Key Findings
- **Loss-making orders** are strongly influenced by **high shipping costs and excessive discounts**.
- **Discounts negatively impact profits** and show a weak negative correlation with sales (-0.16).
- The **Central region** had the highest average discount for loss-making orders.
- **Shipping cost and sales have a strong positive correlation (0.96)**, indicating expensive shipping is tied to high-value orders but also impacts profitability.

## Technologies Used
- **Python** (Pandas, Matplotlib, Seaborn, NumPy)
- **Jupyter Notebook** for interactive data analysis
- **Power BI / Tableau** (optional) for advanced visualizations

## Repository Structure
```
📂 Superstore-Analysis
│── 📁 data          # Raw and cleaned datasets
│── 📁 notebooks     # Jupyter notebooks with analysis
│── 📁 visuals       # Charts and plots generated from analysis
│── README.md        # Project documentation
```

## How to Use This Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Superstore-Analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the Jupyter Notebook and run the analysis:
   ```bash
   jupyter notebook
   ```

## Future Improvements
- Apply **machine learning models** to predict loss-making orders.
- Develop a **dashboard** for real-time sales monitoring.
- Optimize **pricing and discount strategies** based on customer behavior.

## Contributing
Feel free to fork this repository and submit pull requests with improvements or new insights.

## License
This project is licensed under the **MIT License**.

