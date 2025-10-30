# Movie Correlation Project

## Overview
The **Movie Correlation Project** is a data analysis and visualization endeavor aimed at exploring the key factors that correlate with a movie's **Gross Revenue**. Using a comprehensive dataset, this project performs data cleaning, handles missing values, and employs correlation matrices and scatter plots to quantify the relationships between variables such as **budget**, **score**, **votes**, **director**, **writer**, and **gross revenue**.

---

## Key Findings
The Pearson correlation analysis revealed several significant relationships with **Gross Revenue**:

- **Budget and Gross**: A strong positive correlation (~0.74) indicates that movies with higher budgets tend to generate significantly higher gross revenues.  
- **Votes and Gross**: A moderately strong positive correlation (~0.63) suggests that more popular movies (with a higher number of votes) are generally more financially successful.  

> **Note:** While categorical variables like company, director, and genre do impact gross revenue, a simple Pearson correlation on their encoded labels does not accurately capture this real-world effect.

---

## Data Source
The project uses a dataset named `movies.csv`, which contains thousands of movie records with the following attributes:

- `name`
- `rating`
- `genre`
- `year`
- `released`
- `score`
- `votes`
- `director`
- `writer`
- `star`
- `country`
- `budget`
- `gross`
- `company`
- `runtime`

---

## Technologies and Libraries
This project is built using **Python** and leverages the following key libraries for data manipulation, analysis, and visualization:

- **Pandas (`pd`)**: For data loading and manipulation  
- **NumPy (`np`)**: For numerical operations  
- **Seaborn (`sns`)**: For statistical data visualization (correlation heatmaps, scatter plots)  
- **Matplotlib (`plt`)**: For plotting and customizing visualizations  
