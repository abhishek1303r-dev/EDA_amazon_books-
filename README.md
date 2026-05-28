
Amazon Books EDA Project
Overview

This project is based on Exploratory Data Analysis (EDA) on an Amazon Books dataset.
The main goal of this project is to clean, analyze, and visualize book-related data to discover useful insights such as:

Most popular book categories
Highest-rated books
Price distribution
Relationship between ratings and reviews
Best-selling authors
Data trends and patterns

This project was created using Python libraries commonly used in Data Analytics and Data Science.

Project Objectives
Understand the structure of real-world datasets
Perform data cleaning and preprocessing
Handle missing values and duplicates
Analyze numerical and categorical columns
Create visualizations for better understanding
Generate meaningful business insights from the dataset
Tech Stack
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Dataset Information

The dataset contains information related to Amazon books such as:

Book Title
Author Name
Ratings
Reviews
Price
Category/Genre
Bestseller Information
Features of the Project
Data Cleaning
Removed null values
Removed duplicate records
Renamed columns for better readability
Checked data types
Exploratory Data Analysis
Top-rated books analysis
Most reviewed books
Price analysis
Author-wise analysis
Rating distribution
Correlation analysis
Data Visualization
Bar charts
Histogram plots
Count plots
Heatmaps
Scatter plots
Project Workflow
Import dataset
Understand dataset structure
Clean the dataset
Perform exploratory analysis
Create visualizations
Generate insights
Conclusion
Example Insights
Some categories contain a higher number of bestselling books.
Highly reviewed books often have strong ratings.
A few authors dominate the bestseller list.
Most books fall within a specific price range.
Folder Structure
Amazon-Books-EDA/
│
├── dataset/
│   └── amazon_books.csv
│
├── notebooks/
│   └── amazon_books_eda.ipynb
│
├── images/
│   └── charts_and_graphs.png
│
├── README.md
└── requirements.txt


Install required libraries:

pip install pandas numpy matplotlib seaborn

Run Jupyter Notebook:

jupyter notebook
Sample Code
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns


# Load dataset
books = pd.read_csv('amazon_books.csv')


# Display first 5 rows
print(books.head())
Future Improvements
Build interactive dashboard
Add machine learning prediction models
Deploy project online
Add advanced visualizations
Screenshots

Add your project screenshots here after uploading graphs and outputs.

Example:

Data Cleaning Output
Heatmap Visualization
Rating Distribution Graph
Top Authors Analysis
Conclusion

This project helped in understanding how EDA is performed on real-world datasets using Python. It demonstrates data cleaning, visualization, and analytical skills that are important in Data Analytics and Data Science projects.
