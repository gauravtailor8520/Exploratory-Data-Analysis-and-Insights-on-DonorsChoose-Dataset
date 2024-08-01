# Exploratory-Data-Analysis-and-Insights-on-DonorsChoose-Dataset
Exploratory Data Analysis (EDA) on DonorsChoose Dataset

In this project, we perform exploratory data analysis on the DonorsChoose dataset to uncover insights. The dataset includes various entities like donors, donations, projects, schools, teachers, and resources. The analysis involves merging these datasets and visualizing the data to answer specific questions.

Overview

This analysis aims to:
1. Explore the structure and content of the datasets.
2. Merge datasets based on the Entity Relationship Diagram (ERD).
3. Answer key questions through data exploration and visualization.
4. Identify patterns and insights from the merged dataset.

Steps and Insights

Data Loading and Initial Exploration
- Load datasets: Resources.csv, Schools.csv, Donors.csv, Donations.csv, Teachers.csv, Projects.csv.
- Display the shape and first few rows of each dataset.
- Identify column names, data types, and missing values.

Data Merging
- Merge the datasets step-by-step based on the ERD.
- Create a combined dataframe containing projects, donations, donors, schools, and teachers.

Analysis and Visualizations
1. Number of Schools by State: Visualize the number of schools involved in projects by state.
2. Average Donation Amount by State: Identify and visualize states with the highest average donations per project.
3. Donation Amount Statistics: Calculate and visualize mean, median, percentiles, and the ECDF of donation amounts to identify outliers.
4. Donations by Donor State: Analyze the number of donations made by donors in each state.
5. Projects vs. Donations: Explore the relationship between the number of projects and the number of donations using scatter plots and correlation coefficients.
6. Project Types and Donations: Identify different project types and the total donation amount for each type.
7. Project Subject Categories: Analyze the top project subject categories by donation amount.
8. Project Funding Time by State: Calculate and visualize the average time taken for projects to be fully funded by state.

Key Findings
- Positive correlation between the number of projects and donations.
- Significant outliers in donation amounts.
- States vary significantly in average project funding time.
- Certain project types and categories attract more donations.

Conclusion
The analysis provides valuable insights into the DonorsChoose dataset, highlighting trends and patterns in donations and project funding. Further analysis can delve deeper into specific areas of interest.

Running the Code
To run this analysis, ensure you have the necessary libraries installed:
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from matplotlib import style
import datetime as dt
style.use("ggplot")
