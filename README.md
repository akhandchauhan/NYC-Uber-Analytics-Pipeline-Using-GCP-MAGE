# Uber_data_analytics

## Introduction
The goal of this project is to perform data analytics on Uber data using various tools and technologies, including GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio.

## Architecture

![Architecture](https://github.com/akhandchauhan/Uber_data_analytics/assets/112802105/2c072400-4f59-47bd-aeb0-ea3a629e9524)

## Services Used
![Services Used](https://github.com/akhandchauhan/Uber_data_analytics/assets/112802105/27bb4139-d963-41cd-b6b0-5d25fd770026)
## Dataset 

The dataset used for the analysis can be found here: [uber_data.csv](./uber_data.csv)
## Usage

To use the data in your analysis, you can download the CSV file and load it into your preferred data analysis tool or programming language. Here's an example in Python:

```python
import pandas as pd

# Load the dataset
df = pd.read_csv('path/to/uber_data.csv')

# Display the first few rows
print(df.head())
