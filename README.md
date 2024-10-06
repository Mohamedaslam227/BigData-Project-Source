
# 2021 Tokyo Olympics Data Analysis

This project leverages the **2021 Tokyo Olympics dataset** to perform Big Data analytics using modern data processing tools like Apache Spark and Hadoop.

## Data Source

- **Dataset**: [2021 Olympics in Tokyo](https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo)
- **Source**: Kaggle
- **License**: Public

## Objective

The primary goal of this project is to analyze the performance of athletes and countries during the 2021 Tokyo Olympics. We aim to uncover trends, perform visualizations, and predict future performance using Big Data techniques.

## Features

- **Country Analysis**: Medal distribution by country.
- **Athlete Analysis**: Performance metrics of top athletes.
- **Event Analysis**: Distribution of medals across different sporting events.
- **Trend Analysis**: Predictive analytics for future Olympics.

## Tools & Technologies

- **Big Data Frameworks**: Apache Spark, Hadoop
- **Data Processing**: Python (Pandas, NumPy), Spark SQL
- **Visualization**: Matplotlib, Seaborn
- **Development Environment**: Jupyter Notebook, PySpark

## Installation & Setup

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/olympics-bigdata-analysis.git
    cd olympics-bigdata-analysis
    ```

2. Download the dataset from Kaggle:
    [2021 Olympics Dataset](https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo)

3. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Configure your Hadoop and Spark environments for the project.

## Usage

- Run Jupyter Notebooks to explore and analyze the dataset.
- Use Spark for distributed data processing:
    ```bash
    spark-submit olympics_analysis.py
    ```

## Results

- Medal distribution visualizations.
- Predictive models for performance in future Olympics.
- In-depth analysis of trends over different countries and events.
