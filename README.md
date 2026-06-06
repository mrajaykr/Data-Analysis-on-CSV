# Data-Analysis-on-CSV
A Python data analysis project using Pandas to analyze sales data from a CSV file and generate visual insights through charts.

## Overview

This project demonstrates basic data analysis using Python and Pandas. A sales dataset stored in CSV format is analyzed to generate useful insights and visualizations.

## Features

* Load CSV data using Pandas
* Analyze sales information
* Group data by product and region
* Calculate total sales
* Generate charts and visualizations

## Technologies Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

## Project Structure

```text
Data-Analysis-on-CSV/
│
├── sales_analysis.ipynb
├── sales_data.csv
├── README.md
└── charts/
    ├── total_sales_by_product.png
    └── total_sales_by_region.png
```

## Installation

Install required libraries:

```bash
pip install pandas matplotlib
```

## Analysis Performed

### 1. Load CSV File

```python
df = pd.read_csv("sales_data.csv")
```

### 2. Group Data by Product

```python
df.groupby("Product")["Sales"].sum()
```

### 3. Group Data by Region

```python
df.groupby("Region")["Sales"].sum()
```

### 4. Generate Visualizations

* Bar Chart for Product Sales
* Pie Chart for Regional Sales Distribution

## Sample Output

### Total Sales by Product

```text
Laptop    150000
Mobile    105000
Tablet     45000
```

### Total Sales by Region

```text
East     70000
North    85000
South    85000
West     60000
```

## Screenshots

```markdown
![Sales by Product](charts/sales_by_product.png)

![Sales by Region](charts/sales_by_region.png)
```

## Author

Ajay Kumar
