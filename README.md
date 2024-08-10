## World Happiness Report Analysis

This project analyzes the World Happiness Report dataset to gain insights into the factors influencing happiness across different countries. By examining data from 2015 and 2023, we aim to identify the key determinants of happiness, explore regional variations, and develop predictive models for happiness scores.

## Project Structure

This repository contains the following files:

1. **World_Happiness_Report_Analysis.ipynb**: The Jupyter Notebook containing the full analysis, including data preprocessing, exploratory data analysis (EDA), correlation analysis, and machine learning models.
2. **2015.csv**: The dataset containing World Happiness Report data from 2015, used to gather regional information.
3. **WHR2023.csv**: The dataset containing World Happiness Report data from 2023, which serves as the primary dataset for analysis.

## Data Sources

The datasets used in this analysis are sourced from Kaggle:

- [World Happiness Report 2023](https://www.kaggle.com/code/lukestarnes/world-happiness-report-2023/input?select=WHR2023.csv)
- [World Happiness Report 2015](https://www.kaggle.com/datasets/unsdsn/world-happiness/data?select=2015.csv)

## Objectives

1. **Identify Key Factors Influencing Happiness**: Determine the most significant variables affecting happiness scores, such as GDP, social support, and life expectancy.
2. **Regional Happiness Analysis**: Explore regional differences in happiness and identify trends across different regions.
3. **Categorization and Prediction**: Develop machine learning models to categorize and predict happiness scores based on key factors.

## Methodology

The analysis is carried out through the following steps:

1. **Data Preprocessing**: Handling missing values, normalizing data, and merging datasets for comprehensive analysis.
2. **Exploratory Data Analysis (EDA)**: Visualizing and analyzing data distributions, outliers, and regional trends.
3. **Correlation Analysis**: Using statistical methods to identify relationships between happiness scores and various factors.
4. **Machine Learning Models**: Implementing decision tree regression and linear regression to predict happiness scores.

## Results Overview

- **Key Factors**: GDP, Social Support, and Healthy Life Expectancy are the most influential factors for happiness scores.
- **Regional Analysis**: Western Europe, North America, Australia, and New Zealand have the highest happiness scores, while Asia and Africa lag behind.
- **Prediction Models**: The Decision Tree Regression model explained approximately 83% of the variance in happiness scores, showcasing its effectiveness.

## Installation

To run the Jupyter Notebook in this repository, you'll need to install the required Python libraries. You can do this using `pip` and the provided `requirements.txt` file.

### Using pip

1. Clone the repository:

   ```bash
   git clone https://github.com/prashantvnsi/Analyse-World-Happiness.git

2. Navigate to the project directory:

    ```bash
    cd Analyse-World-Happiness

3. Install the required libraries:

    ```
    pip install -r requirements.txt

4. Run the Unraveling the Science of Happiness.ipynb file from Jupyter notebook
