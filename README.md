
# Apache Spark – Kaggle Online Retail Data Analysis

## Project Overview
This project demonstrates Apache Spark and PySpark for large-scale data processing and analysis using the Kaggle Online Retail dataset.

It explores distributed data processing, data cleaning, partitioning, lazy evaluation, caching, fault tolerance, and sales analysis.

## Technologies Used
- Python
- Apache Spark
- PySpark
- Google Colab
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset
**Online Retail Dataset – Kaggle**

Original records: 541,909 (as observed in the dataset).

The project cleans and processes the retail transaction data before performing analysis.

Dataset source:
https://www.kaggle.com/datasets/carrie1/ecommerce-data

## Project Features
- Data loading and exploration using PySpark
- Missing-value handling
- Duplicate removal
- Data type conversion
- Data cleaning and preprocessing
- Spark DataFrame operations
- Partitioning and repartitioning
- Lazy evaluation demonstration
- Execution plan analysis using `explain()`
- Caching and persistence
- RDD lineage and fault tolerance concepts
- Revenue analysis by country
- Top-selling product analysis
- Data visualization using Matplotlib
- Structured Streaming demonstration

## Partitioning Experiment

The project demonstrates Spark partitioning using 2, 4 and 8 partitions.

Example cleaned dataset partition counts:

| Partitions | Records per partition |
|---|---|
| 2 | 262,439 each |
| 4 | 131,219–131,220 |
| 8 | 65,609–65,610 |

## Spark vs Hadoop MapReduce

The project includes an educational comparison of:
- Hadoop MapReduce-style disk-based processing
- Apache Spark DataFrame processing
- In-memory caching
- Execution-time visualization

**Note:** The Python MapReduce implementation is a simulation, not an actual Hadoop cluster benchmark.

## How to Run

1. Open Google Colab.
2. Upload or open the Jupyter Notebook.
3. Install PySpark and Java if required.
4. Download the Kaggle dataset.
5. Run the notebook cells in order.
6. Explore the outputs and visualizations.

## Project Structure

```text
apache-spark-kaggle-online-retail/
│
├── Apache_Spark_Kaggle_Online_Retail.ipynb
├── README.md
└── requirements.txt
```

## Learning Outcomes
- Understanding Apache Spark architecture
- Learning distributed data processing concepts
- Working with PySpark DataFrames and RDDs
- Understanding partitioning and caching
- Exploring Spark performance concepts
- Performing real-world retail data analysis

## Author

**C M Karthik**

M.Sc. Data Science

GitHub: https://github.com/cmkarthik2004

Portfolio: https://cmkarthik.me

---

If you find this project useful, feel free to ⭐ the repository!
