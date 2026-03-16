# Global Health SDG3 Analysis

This project explores global health outcomes related to **United Nations Sustainable Development Goal 3 (SDG 3)**, which focuses on ensuring healthy lives and promoting well-being for all.

Using multi-country datasets on **food affordability, food insecurity, health expenditure, life expectancy, maternal mortality, and overall health achievement**, this project applies **data cleaning, exploratory data analysis, regression modelling, and clustering techniques** to identify patterns and generate insights into health performance across countries.

## Project Context

This project was completed as part of an academic data analytics project at the **University of Tasmania**.

My contribution included:
- data cleaning and preprocessing
- dataset integration and transformation
- exploratory data analysis and visualisation
- regression modelling and forecasting
- clustering analysis using unsupervised learning
- notebook development and result interpretation

## Project Objective

The objective of this project is to understand why some countries achieve better health outcomes than others and to explore how selected health indicators may change over time.

The analysis focuses on the relationship between:
- food insecurity and health outcomes
- food affordability and health performance
- government health expenditure and life expectancy
- government health expenditure and maternal mortality
- country-level health indicator patterns across time

## Key Questions

This project addresses the following questions:

- How do food insecurity and food prices relate to health outcomes?
- How does government health expenditure affect life expectancy and maternal mortality?
- Which countries show similar health indicator patterns?
- How might selected health indicators change over time?

## Project Scope

The project focused on 10 selected countries from different continents and income groups to provide geographic and economic diversity:

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

## Datasets

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

## Project Workflow

### 1. Data Preparation and Cleaning
This stage focused on preparing the datasets for analysis by:
- loading multiple Excel datasets into Python
- standardising column names and country names
- handling missing values
- reshaping and transforming data
- aligning features by country and year
- merging datasets into analysis-ready tables

### 2. Exploratory Data Analysis (EDA)
This stage focused on understanding patterns and relationships in the data through:
- descriptive statistics
- cross-country comparisons
- variable distribution analysis
- scatter plots and trend exploration
- relationship analysis across health, food, and expenditure indicators

Key analyses included:
- cost of healthy diet vs life expectancy
- government health expenditure vs life expectancy
- government health expenditure vs maternal mortality
- food insecurity vs life expectancy
- food insecurity vs maternal mortality
- food prices vs overall health achievement level

### 3. Predictive Modelling
Regression models were used to explore trends and forecast selected indicators, including:
- food costs
- food insecurity
- life expectancy
- SDG 3 achievement-related outcomes

### 4. Clustering and Pattern Discovery
Unsupervised learning methods were applied to identify countries with similar health indicator profiles:
- **K-Means Clustering**
- **Hierarchical Clustering**
- **Elbow Method**
- **Silhouette Score evaluation**

This stage helped group countries based on shared health patterns and compare higher-performing and lower-performing clusters.

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
- Histograms
- Boxplots
- Scatter plots
- Cross-country comparison
- Relationship analysis

### Machine Learning
- Linear Regression
- K-Means Clustering
- Hierarchical Clustering
- StandardScaler
- MinMaxScaler
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

## Key Skills Demonstrated

- Data cleaning and preprocessing
- Multi-source dataset integration
- Exploratory data analysis (EDA)
- Data visualisation
- Regression modelling and forecasting
- Unsupervised learning
- Insight generation from real-world datasets
- Communicating analytical findings through notebooks and reports

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
global-health-sdg3-analysis/
├── README.md
├── data/
├── notebooks/
│   ├── data-cleaning-and-eda.ipynb
│   ├── sdg3-achievement-prediction.ipynb
│   └── country-health-clustering.ipynb
├── report/
```
## Author

**Richard Huynh**  
Master of Information Technology & Systems  
University of Tasmania
