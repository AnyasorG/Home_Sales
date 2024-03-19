# Module 22 Challenge - Home Sales Data Analysis

## Table of Contents
1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Project Structure](#project-structure)
4. [Instructions](#instructions)
5. [Files](#files)
6. [Usage](#usage)
7. [Code Source](#code-source)
8. [Ethical Considerations](#ethical-considerations)
9. [License](#license)
10. [Summary](#summary)
11. [Author](#author)

## Overview:

This project analysed home sales data using PySparkSQL. The goal is to perform various SparkSQL queries to extract key metrics and optimize performance using caching and Parquet-formatted data.

## Dataset:

The dataset used in this project is sourced from "https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.2/22-big-data/home_sales_revised.csv" and it was generated by edX Boot Camps LLC, intended for educational purposes only. It consists of home sales records with information such as date, price, bedrooms, bathrooms, square footage, and other relevant details.

## Project Structure:

- `Home_Sales.ipynb`: Jupyter Notebook containing the PySparkSQL code for data analysis.
- `home_sales_revised.csv`: Dataset file containing home sales data in CSV format.

## Instructions:

**1. Google Colab:** Use Google Colab instead of Jupyter Notebook.

**2. Repository Setup:**
   - Clone the repository to your local machine.
   - Inside the local repository, create a directory dedicated to the Home Sales Data Analysis project.
   - Push the changes, including the new directory, to GitHub.

**3. Files:**
   - Download the necessary files for the challenge.
   - home_sales_revised.csv
   - Home_Sales.ipynb 
   - README.md

## Usage:

Ensure you have PySpark installed in your environment. Open the `Home_Sales.ipynb` notebook and execute the code cells to perform the analysis.

## Code Source:

Parts of the code were adapted from documentation and resources, including:
  - [PySpark documentation](https://spark.apache.org/docs/latest/api/python/index.html)
  - [Stack Overflow](https://stackoverflow.com/)
  - [PySpark Tutorials](https://www.analyticsvidhya.com/blog/category/spark/)
  - [Official Apache Spark GitHub Repository](https://github.com/apache/spark)

## Ethical Considerations:

- All code is publicly available, promoting transparency in the analysis.

## License:

This project is open-source and is made available under the terms of the MIT License. Refer to the [LICENSE](LICENSE) file for full details.

## Summary:

The project successfully analyzes home sales data using PySparkSQL, leveraging caching and Parquet-formatted data for optimization. 

- The results of executing the same query on different versions of the data reveal distinct performance characteristics.
- When querying the original DataFrame directly, the runtime was approximately 1.21 seconds, showcasing the baseline performance.
- Utilising cached data improved query execution speed, with a runtime of about 0.84 seconds, highlighting the efficiency gains from caching.
- However, leveraging Parquet-formatted data demonstrated the most significant enhancement, with a runtime of approximately 0.53 seconds, underscoring the superiority of optimized storage formats for data processing tasks.
- This performance disparity underscores the importance of caching and employing efficient data storage strategies, such as Parquet, to expedite query execution and enhance overall system performance.
​
See data at https://github.com/AnyasorG/Home_Sales.git.

## Author:
Godswill Anyasor
