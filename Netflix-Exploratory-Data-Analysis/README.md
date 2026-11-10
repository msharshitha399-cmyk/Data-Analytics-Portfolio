# Netflix Exploratory Data Analysis (EDA)

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a Netflix dataset to understand its content library, identify patterns, and discover insights through data analysis and visualization.

The analysis explores the distribution of Movies and TV Shows, content-producing countries, genres, ratings, release years, and the growth of Netflix's content library over time.

## Objectives

- Understand the structure and characteristics of the Netflix dataset.
- Identify and examine missing values and duplicate records.
- Analyze the distribution of Movies and TV Shows.
- Explore the countries contributing Netflix content.
- Identify the most common content genres and ratings.
- Examine content release trends and yearly additions.
- Present findings through data visualizations.

## Dataset

**Dataset file:** `netflix_titles_nov_2019.csv`

The dataset contains information about Netflix titles, including:

- Show ID
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Listed In (Genres)
- Description
- Type (Movie or TV Show)

**Dataset dimensions:** 5,837 rows and 12 columns.

## Technologies and Libraries Used

- **Python** – Programming language used for analysis.
- **Jupyter Notebook** – Development environment.
- **Pandas** – Data manipulation and analysis.
- **NumPy** – Numerical operations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical data visualization.

## Data Analysis Performed

### 1. Data Exploration
- Loaded the dataset using Pandas.
- Examined the first five records.
- Checked dataset dimensions, columns, and data types.
- Generated descriptive statistical summaries.

### 2. Data Cleaning
- Identified missing values across columns.
- Examined the distribution of missing values.
- Checked for duplicate records.
- Removed duplicate records.

### 3. Exploratory Data Analysis
- Analyzed Movies vs TV Shows.
- Identified the top 10 countries producing Netflix content.
- Explored the top 10 genres.
- Analyzed content ratings.
- Examined the distribution of content release years.
- Analyzed Netflix content additions by year.

### 4. Data Visualization

Created visualizations using Matplotlib and Seaborn to represent:
- Distribution of Movies and TV Show
- Top 10 countries producing Netflix content.
- Distribution of content ratings.


## Key Findings

- The dataset contains **5,837 records** and **12 columns**.
- Movies account for **3,939 titles**, while TV Shows account for **1,898 titles**.
- A total of **3,536 missing values** were identified across the dataset.
- The Director column contains the highest number of missing values.
- No duplicate records were identified.
- The analysis explores country-wise content distribution, popular genres, ratings, and content trends over time.

## Project Structure

```text
Netflix-Exploratory-Data-Analysis/
│
├── Netflix_EDA.ipynb
├── netflix_titles_nov_2019.csv
└── README.md
```

## How to Run the Project

1. Download or clone this project repository.
2. Ensure that Python and Jupyter Notebook are installed.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Keep the notebook and dataset in the same directory.
5. Open Jupyter Notebook.
6. Run `Netflix_EDA.ipynb` to execute the analysis.

## Learning Outcomes

Through this project, I gained practical experience in:

- Working with real-world datasets.
- Data exploration and preprocessing.
- Identifying and handling missing values.
- Using Pandas and NumPy for data analysis.
- Creating visualizations using Matplotlib and Seaborn.
- Interpreting data patterns and deriving insights.

## Project Information

**Project Type:** Data Analytics / Exploratory Data Analysis

**Domain:** Entertainment and Streaming Services

**Tools:** Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, Seaborn

---

*This project was completed as part of my learning journey in Python-based Data Analytics and Exploratory Data Analysis.*
