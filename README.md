# retail-sales-data-science
Retail Sales Data Analysis and Visualization using Python
# Retail Sales Data Science Project

A beginner-friendly, end-to-end data science project that analyzes retail sales data to uncover trends, identify top-performing products/categories/cities, and generate actionable business insights.

The notebook is fully self-contained — it generates a sample retail sales dataset internally, so it runs out of the box with no external CSV file required.

## Project Workflow

1. **Create Sample Retail Sales Dataset** — synthetic dataset with Date, Product, City, Quantity, Unit_Price, Category, and Sales columns
2. **Inspect the Dataset** — shape, data types, summary statistics, missing values
3. **Data Cleaning and Feature Engineering** — derived columns such as Revenue, Month, etc.
4. **Key Business KPIs** — total revenue, total orders, average order value, and more
5. **Monthly Sales Trend** — time-series visualization of sales over months
6. **Sales by Category** — category-level performance breakdown
7. **Sales by City** — city-level performance breakdown
8. **Correlation Analysis** — heatmap of relationships between numeric features
9. **Business Insights** — automatically generated summary of top performers
10. **Conclusion** — recap of the full workflow

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Repository Structure

```
retail-sales-data-science-project/
├── notebooks/
│   └── retail_sales_data_science_project.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

## Getting Started

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd retail-sales-data-science-project
```

### 2. Create a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook notebooks/retail_sales_data_science_project.ipynb
```

## Key Insights (from sample data)

- Identifies the top-performing product, category, and city by revenue
- Highlights the best-performing month
- Surfaces correlations between quantity, price, sales, and revenue
- Provides a foundation management can use for marketing and inventory planning

## License

This project is open source and available for personal and educational use.
