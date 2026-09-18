# PySpark Lab

Basic PySpark examples covering RDDs, DataFrames, and Spark SQL.

## Requirements

- Python 3
- [Project dependencies](requirements.txt)
- JupyterLab

Install the dependencies with:

```bash
pip install -r requirements.txt
```

## Notebooks

| File | Description |
|---|---|
| [01-PySpark-Get-Started.ipynb](01-PySpark-Get-Started.ipynb) | First steps with PySpark. |
| [02-Create-SparkContext.ipynb](02-Create-SparkContext.ipynb) | Creating and using `SparkContext`. |
| [03-Create-SparkSession.ipynb](03-Create-SparkSession.ipynb) | Creating and using `SparkSession`. |
| [04-RDD-Operations.ipynb](04-RDD-Operations.ipynb) | RDDs, transformations, actions, and text files. |
| [05-DataFrame-Intro.ipynb](05-DataFrame-Intro.ipynb) | Introduction to DataFrames and comparison with RDDs. |
| [06-DataFrame-from-various.ipynb](06-DataFrame-from-various.ipynb) | Reading and writing CSV, JSON, and Parquet files. |
| [07-DataFrame-Operations.ipynb](07-DataFrame-Operations.ipynb) | Selecting, filtering, grouping, and aggregating data. |
| [08-Spark-SQL.ipynb](08-Spark-SQL.ipynb) | SQL queries, temporary views, subqueries, and window functions. |

## Sample data

| File | Usage |
|---|---|
| [data.txt](data/data.txt) | Text file used in the RDD examples. |
| [stocks.txt](data/stocks.txt) | Stock market data in text format. |
| [persons.csv](data/persons.csv) | People data in CSV format. |
| [products.csv](data/products.csv) | Product data in CSV format. |
| [products_singleline.json](data/products_singleline.json) | Products in single-line JSON format. |
| [products_multiline.json](data/products_multiline.json) | Products in multi-line JSON format. |
| [products.parquet](data/products.parquet) | Product data in Parquet format, created by Spark. |

## Run

```bash
jupyter-lab
```

Open the notebooks in order, from `01` to `08`.
