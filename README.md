# Seasonal Agriculture Performance Analysis

## Project Overview

Seasonal Agriculture Performance Analysis is a data analysis project that studies agricultural performance across different seasons, crops, and regions.

The project analyzes 4,000 farm records and 28 variables covering environmental conditions, soil characteristics, farming practices, resource usage, crop yield, production, revenue, cost, profit, water efficiency, and disease/pest risk.

The main goal is to identify seasonal patterns, differences, relationships, variations, and unusual observations that can support better agricultural planning and decision-making.

---

## Problem Statement

Agricultural performance varies across seasons due to changes in environmental conditions, farming practices, resource availability, and market conditions.

However, raw agricultural data does not clearly show how performance changes across seasons.

This project analyzes agricultural data to identify seasonal differences, patterns, trends, relationships, and variations in yield, production, resource usage, and economic performance.

---

## Objectives

- Clean and preprocess the agricultural dataset.
- Compare agricultural performance across seasons.
- Analyze crop-wise seasonal performance.
- Study relationships between environmental conditions and crop performance.
- Analyze resource usage such as water and fertilizer.
- Compare economic performance across seasons and crops.
- Analyze water efficiency.
- Study disease and pest risk.
- Identify unusual patterns and variations.
- Provide evidence-based recommendations.

---

## Dataset

The dataset contains:

- **4,000 farm records**
- **28 variables**

### Major Data Categories

- Farm location
- Crop and season
- Farm area
- Rainfall
- Temperature
- Humidity
- Sunlight
- Soil pH
- Soil moisture
- Nitrogen, phosphorus, and potassium
- Irrigation method
- Fertilizer usage
- Pesticide usage
- Seed quality
- Crop yield
- Production
- Market price
- Total cost
- Revenue
- Profit
- Water usage
- Water efficiency
- Disease and pest risk

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- CSV Dataset

---

## Data Preprocessing

The dataset was checked for missing values and incomplete observations.

Missing values were identified in:

- Rainfall
- Soil Moisture
- Yield

The missing values were handled using the median value of their respective columns.

After preprocessing, the dataset contained no missing values.

---

## Analysis Performed

The project includes:

### 1. Seasonal Analysis

Comparison of:

- Yield
- Production
- Revenue
- Cost
- Profit
- Rainfall
- Temperature
- Water usage
- Water efficiency
- Disease and pest risk

across Kharif, Rabi, and Zaid seasons.

### 2. Crop-wise Analysis

Crop performance was compared using average yield and profitability.

Sugarcane and Chilli were among the strongest-performing crops in terms of profitability.

### 3. State-wise Analysis

Agricultural performance was compared across different states and seasons.

### 4. Environmental Analysis

The relationship between crop performance and environmental conditions such as rainfall, temperature, humidity, sunlight, and soil moisture was studied.

### 5. Water Efficiency Analysis

Water usage and water efficiency were analyzed across seasons and irrigation methods.

### 6. Statistical Analysis

The Kruskal-Wallis statistical test was used to determine whether crop yield differed significantly across seasons.

### 7. Correlation Analysis

Correlation analysis was performed to understand relationships between agricultural and economic variables.

### 8. Outlier Analysis

The Interquartile Range (IQR) method was used to identify unusual profit observations.

---

## Key Findings

- **Kharif performed best overall**, with an average yield of approximately **5.63 tonnes/ha**.
- Kharif also recorded the highest average profit of approximately **₹178,915**.
- **Zaid showed weaker economic performance**, with an average profit of approximately **-₹24,805**.
- **Sugarcane recorded the highest average yield** across the analyzed crops.
- Sugarcane and Chilli were among the most profitable crops.
- Zaid recorded the highest average water usage of approximately **6419.89 m³**.
- Zaid recorded the lowest water efficiency of approximately **4.41 tonnes/1000 m³**.
- Kharif recorded the highest water efficiency among seasons at approximately **5.89 tonnes/1000 m³**.
- **Punjab–Rabi recorded the highest state-season yield** at **8.61 tonnes/ha**.
- **Maharashtra–Zaid recorded the lowest state-season yield** at **2.28 tonnes/ha**.
- Punjab showed the highest seasonal yield variation.
- Telangana showed the lowest seasonal yield variation.
- The Kruskal-Wallis test showed a statistically significant difference in yield across seasons.
- **404 unusual profit observations** were identified using IQR-based outlier detection.

---

## Visualizations

The project includes visualizations such as:

- Average Profit by Season and Crop
- Average Profit by Crop
- State × Season Yield Heatmap
- Water Efficiency by Irrigation Method
- Profit Outlier Boxplot
- Correlation Heatmaps
- Seasonal comparison charts

---

## Recommendations

Based on the analysis:

- Focus on high-performing crops such as Sugarcane and Chilli where conditions are suitable.
- Give special attention to Zaid season because of its lower water efficiency and negative average profit.
- Improve water management during seasons with high water requirements.
- Consider regional and seasonal differences when selecting crops.
- Investigate unusually high profits and large losses before making major decisions.
- Use seasonal yield and profitability trends for better agricultural planning.
- Promote efficient irrigation and resource-use practices.

---

## Future Scope

The project can be extended by:

- Developing machine learning models for crop yield prediction.
- Predicting agricultural profitability.
- Building crop recommendation systems.
- Integrating weather forecasting data.
- Creating an interactive agricultural dashboard.
- Using real-time agricultural and market data.
- Developing personalized crop and resource recommendations.
- Performing deeper market price and cost analysis.

---

## Project Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── Seasonal_Agriculture_Performance_Analysis.ipynb
├── Seasonal_Agriculture_Performance_Analysis.csv
└── README.md
