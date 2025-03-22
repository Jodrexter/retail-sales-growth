# Retail Sales Data Analysis

This project aims to conduct an in-depth analysis of retail sales data to uncover insights into sales performance and data quality. The analysis involves fetching data from Kaggle, cleaning and processing it with pandas, integrating with MySQL for efficient querying, and extracting meaningful insights.

## Project Objectives

- Acquire and preprocess retail sales data.
- Integrate with MySQL for structured data storage.
- Perform data cleaning to handle duplicates and null values.
- Extract meaningful insights from the cleaned data.

## Project Workflow

1. **Data Acquisition:**
   - Retrieved retail sales dataset from Kaggle.
2. **Data Cleaning and Preprocessing:**
   - Identified and handled duplicate records and null values using pandas.
   - Standardized date formats and categorical data.
3. **Database Integration:**
   - Connected Jupyter Notebook to MySQL using `mysql-connector-python`.
   - Designed and created database schema to store cleaned data.
   - Inserted cleaned data into MySQL tables for optimized querying.
4. **Insight Extraction:**
   - Queried MySQL database to extract meaningful insights.

## Technologies Used

- Python (pandas)
- Jupyter Notebook
- MySQL
- Kaggle
- SQL for querying

## Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/Jodrexter/retail-sales-growth.git
```

2. Install required packages:

```bash
pip install pandas mysql-connector-python jupyter
```

3. Run Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the notebook and follow the steps for data cleaning and querying.

## Future Enhancements

- Perform detailed sales trend analysis.
- Develop a Power BI dashboard to visualize insights interactively.
- Automate data pipeline from Kaggle to MySQL.

## Author

[Jodrexter](https://github.com/Jodrexter)

## Acknowledgments

- Kaggle for the dataset.
- Open-source community for support.

---

Feel free to contribute or reach out for collaboration!
