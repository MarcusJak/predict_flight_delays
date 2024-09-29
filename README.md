# Flight Predictor ✈️

The **Flight Delay Predictor** is a data-intensive project designed to predict flight delays at U.S. airports. By using Apache Spark for data processing and advanced machine learning algorithms, this project aims to determine whether a flight will be delayed by more than 15 minutes, based on historical data.

![image](https://github.com/user-attachments/assets/1988f993-b8ce-40d4-b12a-20b98c07d8aa)

## Project Overview

The goal of this project is to predict if a flight delay will exceed 15 minutes using 21 attributes, including time, carrier, and airport details. We employ a **Logistic Regression model** to achieve accurate predictions and provide insightful visualizations to understand flight delay patterns.

### Features

- **Data Storage**: Leveraging **HDFS** for handling large-scale flight datasets.
- **Processing**: Utilizing **Apache Spark** for distributed data processing.
- **Prediction Model**: Applying **Logistic Regression** to predict flight delay probabilities.

## Technologies

- **Apache Spark**: For scalable data processing.
- **HDFS**: For big data storage and management.
- **Machine Learning**: Logistic Regression for delay prediction.
- **Python**: Core language for scripting and data manipulation.

## Dataset

- **Source**: [Kaggle's Flight Delay Data](https://www.kaggle.com/datasets/arezaei81/flights/data).
- **Attributes**: The dataset includes 21 attributes, such as flight times, delay reasons, carrier information, and more.

### Prerequisites

- **Python 3.8+**
- **Java 8**
- **Apache Spark**
- **Hadoop** (for HDFS)

## Running the Code

### 1. Hadoop Setup

Follow this guide to set up Hadoop: [Install Hadoop on Ubuntu](https://codewitharjun.medium.com/install-hadoop-on-ubuntu-operating-system-6e0ca4ef9689).

### 2. Upload Dataset

Upload the dataset to HDFS:
  ```sh
  hdfs dfs -put flight_data.csv /user/data/
  ```
### 3. Run the Notebook
  Make sure all dependencies are set up, and then execute the notebook to process the data and make predictions.
  
