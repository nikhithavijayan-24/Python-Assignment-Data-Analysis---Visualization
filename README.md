# Python Data Analytics Assignment 2 – Data Visualization

## 📌 Project Overview

This project focuses on **data cleaning and data visualization using Python**. The Seaborn Taxis dataset is used to explore taxi trip information through different visualization techniques and identify patterns in fare, distance, tips, payment methods, and pickup locations.

The assignment demonstrates the practical use of Python libraries for data analysis and visual storytelling.

## 🎯 Objectives

- Load and explore the Taxis dataset.
- Identify and handle missing values using appropriate strategies.
- Visualize taxi fares, trip distances, tips, and payment methods.
- Analyze relationships between numerical variables.
- Compare trip patterns across pickup boroughs and zones.
- Practice creating clear and informative visualizations.

## 🛠️ Tools and Technologies

| Tool / Library | Purpose |
|---|---|
| Python | Data analysis and programming |
| Jupyter Notebook | Writing and executing Python code |
| Pandas | Data manipulation and aggregation |
| Matplotlib | Data visualization and plot customization |
| Seaborn | Statistical data visualization |

## 📂 Dataset

**Dataset:** Taxis dataset from Seaborn

The dataset contains information about taxi trips, including pickup timestamps, fares, distances, tips, payment methods, and pickup locations.

The dataset is loaded using:

```python
import seaborn as sns

df = sns.load_dataset("taxis")
```

## 🧹 Data Cleaning and Preprocessing

The dataset is checked for missing values before visualization.

The preprocessing steps include:

- Identifying columns containing missing values.
- Imputing missing categorical values using the mode where appropriate.
- Checking the dataset again after handling missing values.
- Preparing the relevant columns for visualization.

## 📊 Visualizations

### 1. Matplotlib / Pandas Visualizations

| Visualization | Purpose |
|---|---|
| Line Chart | Examine fare values over pickup timestamps. |
| Bar Chart | Compare total fare across pickup boroughs. |
| Pie Chart | Show the distribution of trips by payment method. |
| Histogram | Understand the distribution of trip distances. |
| Box Plot | Compare tip distributions across pickup boroughs. |

### 2. Seaborn Visualizations

| Visualization | Purpose |
|---|---|
| Count Plot | Display the number of trips in each pickup borough. |
| Scatter Plot | Explore the relationship between distance and fare, grouped by pickup borough. |
| Heatmap | Visualize correlations among distance, fare, tip, tolls, and total. |
| Pair Plot | Examine pairwise relationships between distance, fare, tip, and total, using pickup zone as the hue. |
| Violin Plot | Compare fare distributions across payment methods. |

## 📈 Key Learning Outcomes

Through this assignment, I practiced:

- Handling missing values in a dataset.
- Grouping and aggregating data for analysis.
- Creating different types of plots using Matplotlib and Seaborn.
- Customizing plot titles, axis labels, colours, and other visual properties.
- Using correlation matrices to explore relationships between numerical variables.
- Communicating data insights through visualizations.

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries if they are not already installed.
3. Open the Jupyter Notebook.
4. Run the cells sequentially from top to bottom.

Install the libraries using:

```bash
pip install pandas matplotlib seaborn jupyter
```

## 📁 Project Structure

```text
Python-DA-Assignment-2/
│
├── Python DA Assignment 2 - Data Visualization.ipynb
└── README.md
```

This project is part of my learning journey in Python, data analysis, and data visualization.
