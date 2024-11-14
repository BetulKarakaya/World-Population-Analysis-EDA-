#  Exploratory Data Analysis (EDA) on World Population Dataset

## 📋 Project Overview
This project analyzes population trends by continent from 1970 to 2022, highlighting demographic changes over time. Using Python libraries for data handling and visualization, it fills missing values logically and visualizes results with a modern, engaging color palette. The analysis provides clear insights into population growth patterns, helping to identify trends and outliers across different continents, offering a foundation for understanding global demographic shifts.

## 📊 Data Description
| Column             | Data Type | Null Data Count|
| :---------------- | :------: | ----: |
| Rank        |   int64    | 0 |
| CCA3           |   object   | 0 |
| Country    |  object   | 0 |
| Capital |  object  | 0 |
| Continent |  object  | 0 |
| 2022 Population |  float64  | 4 |
| 2020 Population |  float64  | 1 |
| 2015 Population |  float64  | 4 |
| 2010 Population |  float64  | 7 |
| 1990 Population |  float64  | 5 |
| 1980 Population |  float64  | 5 |
| 1970 Population |  float64  | 4 |
| Area (km²) |  float64  | 2 |
| Density (per km²)|  float64  | 4 |
| Growth Rate |  float64  | 2 |
| World Population Percentage |  float64  | 0 |

## 📑 Dataset
The dataset that i use for this analysis [World Population Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/world-population-dataset/code).

## 🛠 Methodology
#### Data Preprocessing
* Handled missing values using linear interpolation, ensuring a smooth filling of gaps in the data.

#### Statistical Analysis
* Performed basic statistical analysis with methods like info() and describe() to understand the dataset.
* Calculated the correlation matrix to identify relationships between variables.

#### Data Visualization
* Created univariate, bivariate, and multivariate visualizations using Matplotlib and Plotly, enabling high-resolution, interactive insights into population trends.

#### Reporting & Documentation
* Saved visualizations in HTML format for easy, interactive viewing.
* Compiled comprehensive reporting on significant findings, including key population trends and correlations.

## 🔍 Key Insights
Linear Interpolation was used to handle missing data, providing a more accurate representation of the population over time.
Identified significant correlations between population changes and time periods, visualized through both static and interactive charts.
The visualization of population trends across continents helped in understanding demographic growth patterns.

## Contributions
We welcome any feedback and contributions. If you would like to contribute to the project, please submit a pull request or open an issue.
