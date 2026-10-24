# USA Regional Sales Analysis 📊

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on Acme Co.'s USA regional sales data from 2014 to 2018. The objective is to understand sales performance, identify revenue and profit drivers, analyze regional and product-level trends, and generate actionable business insights.

Using Python and data visualization libraries, the analysis explores sales channels, customer segments, product performance, regional distribution, profitability, and sales trends to support data-driven business decisions.

## 🎯 Project Objectives

- Analyze revenue, costs, profit, and profit margins.
- Identify top-performing and underperforming products.
- Evaluate sales performance across channels and US regions.
- Analyze monthly and yearly sales trends.
- Identify unusual transactions and potential outliers.
- Explore relationships between quantity, unit price, revenue, cost, and profit.
- Compare product performance against available 2017 budget data.
- Develop data-driven recommendations for business growth.

## 🛠️ Tools & Technologies

- **Python** — Data analysis and processing
- **Pandas** — Data manipulation, cleaning, and aggregation
- **NumPy** — Numerical computations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Jupyter Notebook / Google Colab** — Interactive analysis

## 📂 Dataset Description

The dataset contains USA sales records from 2014 to 2018 and supporting information from multiple tables:

- **Sales Orders:** Order dates, customers, sales channels, quantities, unit prices, revenue, and unit costs.
- **Customers:** Customer identifiers and names.
- **Products:** Product identifiers and names.
- **Regions:** Geographic information, including state, city, population, and other regional attributes.
- **State Regions:** Mapping of US states to geographic regions.
- **2017 Budgets:** Product-level budget information for 2017.

The sales orders table contains **64,104 records and 12 columns** before data transformation.

*Note: The original dataset is loaded from a Google Drive Excel workbook. Ensure you have authorized access to the source data before running the notebook.*

## 🔍 Project Workflow

### 1. Data Loading and Inspection
- Loaded multiple sheets from an Excel workbook.
- Inspected dataset dimensions, column names, and sample records.
- Examined data types and the structure of supporting tables.

### 2. Data Cleaning and Preprocessing
- Checked missing values and duplicate sales records.
- Corrected the headers in the state-region mapping table.
- Prepared data for analysis and combined relevant tables.
- Derived analytical metrics, including revenue, total cost, profit, and profit margin.

### 3. Exploratory Data Analysis
- Examined revenue, unit prices, quantities, costs, and profit margins.
- Analyzed sales performance by product, customer, channel, state, and region.
- Investigated monthly and yearly revenue trends.
- Examined outliers and relationships among numerical variables.

### 4. Data Visualization
Created visualizations to explore:
- Revenue trends over time.
- Product and sales-channel performance.
- Regional and state-level revenue.
- High- and low-revenue customers.
- Customer segmentation by revenue and profit margin.
- Correlations among key financial and sales metrics.

### 5. Business Insights and Recommendations
Interpreted analytical findings to identify opportunities related to pricing, cost management, channel expansion, sales planning, and regional performance.

## 📈 Key Findings

### Revenue and Sales Trends
- Monthly revenue generally remained within approximately $23 million–$26.5 million during 2014–2017.
- A notable decline to approximately $21.2 million occurred in early 2017 and warrants further investigation.
- No consistent recurring monthly revenue seasonality was identified.

### Sales Channel Performance
The reported channel mix was:
- **Wholesale:** 54%
- **Distributor:** 31%
- **Export:** 15%

This distribution highlights the importance of wholesale sales and a potential opportunity to explore export-channel growth.

### Product Performance
The leading products by reported revenue were:
- **Product 26:** Approximately $118 million
- **Product 25:** Approximately $110 million
- **Product 13:** Approximately $78 million

These findings can help prioritize product-level performance reviews and further profitability analysis.

### Regional Performance
- California led the reported state-level analysis, generating approximately $230 million in revenue and more than 7,500 orders.
- Illinois, Florida, and Texas generated approximately $85 million–$110 million each.
- New York and Indiana generated approximately $54 million each.

### Profitability and Correlation
- Reported profit margins varied considerably, ranging from approximately 18% to 60%.
- Revenue and profit showed a strong positive correlation of approximately **0.87**.
- Unit price and revenue showed a strong positive correlation of approximately **0.91**.
- Quantity had a comparatively weaker correlation with revenue, at approximately **0.34**.

*These are descriptive findings from the notebook's analysis. Correlation does not establish causation, and results should be revalidated against the final cleaned dataset before business use.*

## 💡 Business Recommendations

1. **Improve product profitability:** Review the pricing, costs, and margins of underperforming products.
2. **Expand export opportunities:** Investigate potential overseas markets and distributor partnerships.
3. **Investigate unusual sales periods:** Examine the early-2017 revenue decline to identify possible operational or market-related explanations.
4. **Review outlier transactions:** Separate unusual bulk orders or promotional transactions when appropriate to avoid misleading averages.
5. **Strengthen regional planning:** Use state-level revenue and order data to guide further market analysis.
6. **Prepare a business dashboard:** Develop a Power BI dashboard covering sales trends, product performance, channel mix, regional performance, and profitability.

## 📁 Repository Structure

```text
USA-Regional-Sales-Analysis/
│
├── EDA_Regional_Sales_Analysis.ipynb
├── README.md
├── Sales_data(EDA Exported).csv
└── requirements.txt
```

The exported CSV should be included only if it exists in the repository and can be shared. Dataset files may be kept in a separate `data/` directory if preferred.

## 🚀 How to Run the Project

### Prerequisites
- Python 3.x
- Jupyter Notebook or Google Colab
- Access to the source Excel workbook

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
```

### Run the Notebook

1. Clone or download this repository.
2. Open `EDA_Regional_Sales_Analysis.ipynb` in Jupyter Notebook or Google Colab.
3. Make the source Excel workbook accessible.
4. Update the file path in the data-loading cell to match your environment.
5. Install the required libraries.
6. Run the notebook cells in sequence to reproduce the analysis.

## 🔮 Future Improvements

- Develop an interactive Power BI dashboard.
- Add SQL-based analysis of sales and profitability.
- Improve automated data validation and preprocessing.
- Investigate the causes of unusual revenue fluctuations.
- Add reproducible data-loading instructions that do not depend on a personal Google Drive path.

## 👩‍💻 Author

**Anishka Jain**

Data Analytics | Python | Pandas | NumPy | Data Visualization

