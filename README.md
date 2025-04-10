# ERCOT_Analysis
## 📌 Overview

The task was structured around answering a set of analytical and interpretive questions related to ERCOT data. The following areas were covered:

### 🔍 Data Exploration
- Unique values of `Resource Name` and `QSE`
- Definitions and relationships between QSEs and resources
- QSE/Resource Name pair mappings and implications

### 🏷️ Resource Classification
- Cleaning and imputing missing values in the `Resource Type` column
- Creating a new `Fuel Type` column from `Resource Type`
- Merging classification data with output data

### 📊 Time Series Aggregation & Visualization
- Output summed by **day**
- Output summed by **hour-of-day**
- Output by **hour-of-day & fuel type**

### 📈 Time Series Analysis
- Testing for **stationarity** using unit root tests
- Differencing data and visualization
- Fitting an **AR(3)** model and evaluating its appropriateness

### 🧮 Regression Models
Dummy variable regressions were used to understand drivers of electricity output:
- By **Fuel Type**
- By **Day of the Week**
- By **Week**
