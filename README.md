# Exploratory Data Analysis

**Estimated time:** 30 minutes

---

## Table of Contents

1. [Objectives](#objectives)  
2. [Import Data](#import-data)  
3. [Feature Visualization](#feature-visualization)  
   - Individual Patterns  
   - Categorical & Continuous Variables  
4. [Descriptive Statistics](#descriptive-statistics)  
5. [Grouping & Pivot Tables](#grouping--pivot-tables)  
6. [Correlation & Causation](#correlation--causation)  
7. [Conclusions](#conclusions)  
8. [Authors](#authors)  

---

## Objectives

After completing this lab you will be able to:

- Explore features to predict car price  
- Visualize individual patterns & run descriptive stats  
- Group data and build pivot tables  
- Quantify the effect of independent variables on price  

---

## Import Data

```python
import pandas as pd
import numpy as np

# download and load the CSV
file_url = ("https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/"
            "IBMDeveloperSkillsNetwork-DA0101EN-SkillsNetwork/"
            "labs/Data%20files/automobileEDA.csv")
df = pd.read_csv(file_url)
df.head()
