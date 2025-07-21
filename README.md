# Iris Dataset Exploration

## Objective:
This project explores the classic Iris dataset using Python libraries such as pandas, seaborn, and matplotlib. The main goal is to analyze the structure, understand the distribution of features, and visualize the relationships between them to gain insights about the different Iris flower species.

## Dataset Description:
The Iris dataset is a multivariate dataset introduced by the British biologist and statistician Ronald Fisher. It includes:
- 150 samples of Iris flowers
- 3 species: setosa, versicolor, and virginica
- 4 features:
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)

## Tools & Libraries Used:
- Python 3.x
- Pandas – for loading data, manipulation and analysis
- Seaborn – for statistical visualizations
- Matplotlib – for plotting graphs and charts
- Jupyter Notebook – for code execution and visualization

## Approach:
1. Data Loading
    - Used seaborn.load_dataset("iris") to import the dataset.

2. Exploratory Data Analysis (EDA)
    - Checked dataset shape, column types, and basic statistics (.info(), .describe())

3. Visualizations
     - Boxplot: Highlighted distribution, median, and outliers for each feature by species
     - Histograms: Showed frequency distribution for all features
     - Scatter plots: Focused on relationships between sepal and petal features
  
## Results & Insights:
- Iris species show clear visual separation in petal and sepal sizes.
- Useful visualizations helped detect spread and outliers.
- Species separation:
    1.Setosa is clearly distinguishable from the other two species based on petal length and width.
    2.Versicolor and virginica overlap more but still show visual separation.

## Conclusion:
The Iris dataset is simple yet powerful for demonstrating data visualization and classification. Through this exploration, we identified clear patterns in petal features that separate the three Iris species. These insights can guide future classification tasks using machine learning.
