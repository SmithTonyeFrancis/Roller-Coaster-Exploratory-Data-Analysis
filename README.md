**Roller Coaster Data Cleaning & Exploratory Data Analysis**

A data cleaning and exploratory data analysis (EDA) assessment completed as part of my studies at Vephla University. This project uses `pandas`, `matplotlib`, and `seaborn` to clean and explore a real-world roller coaster dataset sourced from Kaggle.

**Project Overview:**
The goal of this project was to take a messy, raw dataset and turn it into something clean, reliable, and ready for analysis. The workflow follows four stages:

1. **Data Understanding** — inspect shape, column names, data types, and summary statistics.
2. **Data Preparation** — drop irrelevant columns, fix data types, rename columns for consistency, and remove duplicate records.
3. **Feature Understanding** — visualize the distribution of individual features (histograms, KDE plots, bar charts).
4. **Feature Relationships** — explore relationships between features using scatter plots, a pairplot, and a correlation heatmap, then answer a concrete question about the data.

**Question answered:**

1. Which locations have the fastest roller coasters on average (minimum of 10 coasters per location)?
This is answered using a `groupby` aggregation, visualized as a horizontal bar chart.

**Dataset Used** 
This project uses the Coaster DB dataset, sourced from [Kaggle](https://www.kaggle.com). It includes:
- Coaster name, location, and manufacturer
- Year introduced and opening date
- Speed (mph), height (ft), inversions, and G-force
- Coaster type and status (operating, closed, etc.)

The dataset is not included directly in this repository, in line with Kaggle's dataset terms.

**Tools & Libraries**
- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

**Key Data Cleaning Steps**
- Selected only the relevant columns for analysis.
- Converted the opening date from text to a proper date format.
- Renamed columns for clarity and consistency.
- Checked for missing values.
- Identified and removed duplicate records, including cases where two different coasters shared a name but were located in different places.

**Visualizations Included**
- Top 10 years coasters were introduced
- Distribution of coaster speed (histogram + KDE)
- Speed vs. height (scatter plot)
- Pairplot across key numeric features
- Correlation heatmap
- Average coaster speed by location
