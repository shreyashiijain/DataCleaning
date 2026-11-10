# DataCleaning
# 🎬 Netflix Data Cleaning & Exploratory Data Analysis

A Python-based data analysis project focused on cleaning and exploring the Netflix Movies and TV Shows dataset to discover patterns, trends, and insights through data visualization.

## 📌 Project Overview

This project explores the Netflix dataset to understand its content library, identify patterns in movie and TV show distribution, and analyze trends across countries, genres, release years, and durations.

The project involves data cleaning, preprocessing, exploratory data analysis (EDA), and visualization using Python libraries.

## 🎯 Objectives

- Understand and explore the Netflix dataset.
- Identify and handle missing values.
- Clean and preprocess data for accurate analysis.
- Analyze the distribution of Movies and TV Shows.
- Explore content distribution across different countries.
- Examine release trends over the years.
- Visualize insights using charts and graphs.

## 🛠️ Technologies Used

- **Python** – Programming language
- **Pandas** – Data cleaning and manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Jupyter Notebook / Google Colab** – Development environment

## 📂 Project Structure

```text
DataCleaning/
│
├── netflix.ipynb
├── netflix_titles.csv
│
├── added dates movie and tv show.png
├── movie duration distribution.png
├── movie vs shows.png
├── no of season in tv shows.png
├── releases over time.png
├── top 10 countries .png
│
└── README.md
```

## 🔍 Project Workflow

### 1. Data Loading
- Imported the required Python libraries.
- Loaded the Netflix dataset using Pandas.
- Explored the dataset using `head()`, `info()`, and `describe()`.

### 2. Data Cleaning
- Identified missing values in different columns.
- Handled missing values using appropriate replacement techniques.
- Replaced missing entries with "Unknown".
- Processed country information for better analysis.

### 3. Exploratory Data Analysis (EDA)
Performed analysis to understand:

- Distribution of Movies and TV Shows.
- Number of seasons in TV Shows.
- Movie duration distribution.
- Top 10 countries contributing content.
- Content added to Netflix over time.
- Release trends across different years.

### 4. Data Visualization
Created visualizations using Matplotlib to represent the findings and make patterns easier to understand.

## 📊 Visualizations

### 1. Movies vs TV Shows
![Movies vs TV Shows](movie%20vs%20shows.png)

### 2. Movie Duration Distribution
![Movie Duration Distribution](movie%20duration%20distribution.png)

### 3. Number of Seasons in TV Shows
![Number of Seasons](no%20of%20season%20in%20tv%20shows.png)

### 4. Top 10 Countries
![Top 10 Countries](top%2010%20countries%20.png)

### 5. Content Added Over Time
![Content Added Over Time](added%20dates%20movie%20and%20tv%20show.png)

### 6. Releases Over Time
![Releases Over Time](releases%20over%20time.png)

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/shreyashiijain/DataCleaning.git
```

2. Navigate to the project directory:

```bash
cd DataCleaning
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib jupyter
```

4. Open the Jupyter Notebook:

```bash
jupyter notebook netflix.ipynb
```

5. Run all the cells to explore the data cleaning process and visualizations.

Alternatively, you can run the notebook directly on Google Colab:

[Open in Google Colab](https://colab.research.google.com/drive/1AA1Q9fVFKMf_4nTRxo1Wcmg5tWLbCPcR)

## 📌 Key Learnings

- Practical experience with data cleaning and preprocessing.
- Handling missing values in datasets.
- Working with Pandas DataFrames.
- Using grouping and aggregation for data analysis.
- Exploring
