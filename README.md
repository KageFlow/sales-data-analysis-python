# Sales Data Analysis Using Python

An intermediate data-analysis project using **Pandas, NumPy, and Matplotlib** to explore sales performance and produce business insights.

## Project objectives
- Load and inspect a sales CSV file.
- Clean column names, missing values, invalid values, and duplicate records.
- Calculate revenue from quantity and unit price.
- Analyze monthly revenue, top products, and city-wise sales.
- Visualize findings with Matplotlib.
- Export cleaned data and summary tables.

## Repository structure
```
sales-data-analysis-python/
├── data/
│   ├── README.md
│   └── sales_data.csv
├── output/                 # Created when the notebook runs
├── sales_analysis.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

## Run in Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Select **File → Upload notebook** and upload `sales_analysis.ipynb`, or open the notebook from GitHub.
3. Run the cells from top to bottom.
4. When prompted, upload your own sales CSV. If you skip upload, the included **synthetic demo dataset** is used.

## Run locally
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Start Jupyter:
   ```bash
   jupyter notebook sales_analysis.ipynb
   ```

## Expected CSV columns
The notebook expects date, product, quantity, unit price, and city fields. It recognizes common variations such as `date`, `product_name`, `qty`, and `price`. Rename columns if your dataset uses different terminology.

Revenue is calculated as:

```
Sales = Quantity × Unit Price
```

## Outputs
The notebook displays monthly revenue, top products, city-wise revenue, and data-driven insights. It also saves CSV summaries in the `output/` folder.

## Dataset note
`data/sales_data.csv` is synthetic sample data created for demonstration and testing. It is not real company data. For the internship submission, replace it with a suitable real-world dataset that you are permitted to use, and mention the dataset source in your report.

## Skills demonstrated
Python, Pandas, NumPy, data cleaning, grouping and aggregation, CSV handling, Matplotlib, and basic business analysis.
