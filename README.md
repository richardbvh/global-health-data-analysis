# Global Health Data Analysis

This project analyses global health indicators related to the United Nations Sustainable Development Goal 3 (SDG 3): ensuring healthy lives and promoting well-being for all.

The project examines how factors such as food insecurity, food prices, and government health expenditure influence health outcomes across multiple countries. It combines data preparation, exploratory data analysis, regression modelling, and clustering techniques to identify patterns and generate insights from global health data.

## Project Objective

The main objective of this project is to understand why some countries achieve better health outcomes than others and to explore how health indicators may change in the future.

This was done by analysing multiple global datasets covering food affordability, food insecurity, health expenditure, life expectancy, maternal mortality, and overall health achievement levels.

## Problem Statement

Many countries face significant challenges in achieving strong health outcomes for their populations. These outcomes are influenced by multiple interconnected factors, including access to nutritious food, affordability of healthy diets, public health investment, and broader health indicators.

This project addresses the following questions:

- How do food insecurity and food prices relate to health outcomes?
- How does government health expenditure affect life expectancy and maternal mortality?
- Which countries show similar health indicator patterns?
- How might selected health indicators change over time?

## Project Scope

The project focused on 10 selected countries from different continents and income groups to ensure geographic and economic diversity:

- Australia
- Canada
- Chile
- China
- Finland
- India
- Italy
- Nepal
- Nigeria
- Vietnam

## Dataset

This project uses multiple global health datasets:

- **Food_Prices_for_Nutrition.xlsx**  
  Contains information on the cost and affordability of a healthy diet across countries and years.

- **Food_Insecurity_nourishment_Indicators.xlsx**  
  Contains indicators related to food insecurity and undernourishment.

- **health-relatedindicators.xlsx**  
  Contains health-related metrics such as life expectancy, maternal mortality, vaccination coverage, and health expenditure.

- **overall health achievement level.xlsx**  
  Contains overall health achievement scores for countries across time.

- **HealthAcheivement-2024.xlsx**  
  Used as a reference dataset for prediction and comparison in the later modelling stage.

## Project Stages

### Phase 1 – Data Preparation and Exploratory Data Analysis

Phase 1 focused on preparing and understanding the data.

Tasks included:

- loading multiple datasets into Python
- standardising column names and country names
- handling missing values
- reshaping and merging datasets
- filtering selected countries
- generating descriptive statistics
- visualising variable distributions
- analysing relationships between health-related variables

Key analyses included:

- cost of healthy diet vs life expectancy
- government health expenditure vs life expectancy
- government health expenditure vs maternal mortality
- food insecurity vs life expectancy
- food insecurity vs maternal mortality
- food prices vs overall health achievement level

Phase 1 helped identify key patterns and build the foundation for deeper modelling.

### Phase 2 – Machine Learning and Pattern Discovery

Phase 2 extended the project into machine learning.

This stage included:

- clustering countries with similar health indicator patterns
- applying **K-Means Clustering**
- applying **Hierarchical Clustering**
- scaling data using **StandardScaler**
- selecting cluster structures using the **Elbow Method**
- evaluating clustering quality using **Silhouette Score**
- applying regression models for prediction and forecasting

Phase 2 focused on identifying country groups with similar health profiles and exploring future changes in selected health indicators.

## Methods Used

### Data Preparation
- Data cleaning
- Missing value handling
- Data transformation
- Data reshaping
- Dataset merging
- Feature alignment by country and year

### Exploratory Data Analysis
- Descriptive statistics
- Histogram
- Boxplot
- Scatter plot
- Cross-country comparison
- Relationship analysis

### Machine Learning
- Linear Regression
- K-Means Clustering
- Hierarchical Clustering
- StandardScaler
- Elbow Method
- Silhouette Score

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Key Findings

The analysis identified several important insights:

- Countries with higher government health expenditure generally showed better health outcomes.
- Higher food insecurity was associated with lower life expectancy.
- Countries with higher food insecurity also tended to experience higher maternal mortality.
- Food prices alone did not show a strong direct relationship with overall health achievement.
- Clustering methods helped identify countries with similar health indicator patterns.
- Regression models were used to forecast selected trends such as food costs, food insecurity, and life expectancy.

## Repository Structure

```text
global-health-data-analysis/
├── README.md
├── data/
├── notebooks/
└── reports/
```

## Files in This Repository

### Data
Contains raw datasets used for analysis and modelling.

### Notebooks
Contains Jupyter notebooks for:
- data cleaning and preprocessing
- exploratory data analysis
- clustering analysis
- regression and prediction

### Reports
Contains project report documents summarising methods, findings, and conclusions.

## Why This Project Matters

This project demonstrates how data analytics and machine learning can be used to study real-world global health challenges. It shows the practical value of combining data cleaning, visualisation, statistical analysis, and modelling to support evidence-based understanding of health outcomes across countries.

## Author

Richard Huynh  
Master of Information Technology & Systems  
University of Tasmania
