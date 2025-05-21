🌸 Iris Dataset Analysis Project
📌 Project Description
This project is a beginner-friendly data analysis exercise using the famous Iris flower dataset. The goal is to understand how different flower measurements (like petal and sepal lengths and widths) differ across three types of iris species:

Iris-setosa

Iris-versicolor

Iris-virginica

The analysis includes steps like data cleaning, exploration, and creating charts to help visualize trends and relationships in the data.

## TECH STACK
This project is written in Python and done inside a Jupyter Notebook. Below are the main libraries and what they were used for:

Library	Purpose
pandas	Load and handle the dataset (dataframes)
matplotlib	Create basic plots and graphs
seaborn	Create more attractive and detailed visualizations
Jupyter Notebook	Step-by-step interactive analysis

## Dataset Information
### File used: Iris.csv.
## Dataset contains: Information about 150 iris flowers.

Main columns:

SepalLengthCm and SepalWidthCm

PetalLengthCm and PetalWidthCm

Species (the type of iris)

Note: The column names originally had the "Cm" suffix (e.g., SepalLengthCm) which were removed for cleaner analysis.

 ## Step-by-Step Breakdown
 Load the Data
The CSV file is loaded using pandas.read_csv()

Used .head() to view the first few rows

Checked for missing values using .isnull().sum()

 Data Cleaning
Removed the suffix “Cm” from column names for easier plotting

Verified that all values are present (no missing data)

Data Exploration
Used .value_counts() to check how many records exist for each species

Explored data types and summary statistics (.info() and .describe())

Data Visualization
Using matplotlib and seaborn, several types of charts were created:

Histograms – to see distribution of flower measurements

Boxplots – to see spread and outliers

Pair Plots – to compare all variables against each other

Heatmaps – to show correlation (relationships) between variables

📊 Key Findings
Petal measurements (especially PetalLength and PetalWidth) are the most useful for distinguishing between the flower species.

Setosa is clearly separable from the others in visual plots.

The data is clean and well-structured, making it suitable for machine learning tasks later.

📘 Insights from This Project
How to work with structured data using Pandas

How to clean and inspect real-world datasets

How to create simple yet powerful visualizations

How to interpret and present data insights

📌 What Can Be Done Next
You can extend this project by:

Building a machine learning model (e.g., classification with KNN or Logistic Regression)

Applying PCA (Principal Component Analysis) to reduce dimensions



▶️ Pointers to running the Project

Make sure Python and Jupyter Notebook are installed on your machine.

Download the notebook file (iris_analysis.ipynb) and the dataset (Iris.csv).

Open the notebook using Jupyter.

Run the cells one by one to follow the analysis and see the results.
