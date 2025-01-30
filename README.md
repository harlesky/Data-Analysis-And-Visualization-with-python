# Data-Analysis-And-Visualization-with-python 🐍📊
FreeCodeCamp Project on the course Data Visualisation with Python: This repository contains various Python projects focused on data analysis, using libraries like NumPy, Pandas, and Matplotlib.

## Projects Included
1. Mean, Variance, Standard Deviation Calculator
2. Demographic Data Analyzer
3. Medical Data Visualizer
4. Page View Time Series Visualizer
5. Sea Level Predictor


---

# 1️⃣ Mean, Variance, Standard Deviation Calculator  

### Overview  
This project uses NumPy to implement a function that calculates the mean, variance, standard deviation, max, min, and sum of a **3×3 matrix**.  

# Functionality  
- Converts a list of **9 numbers** into a **3×3 NumPy array**.  
- Computes **mean, variance, standard deviation, min, max, and sum** along:  
  - **Rows**
  - **Columns**
  - **Flattened array**  
- Returns a dictionary with these calculations.  
- Raises an exception if the input list contains fewer than 9 elements.

# Example Usage 
```python
from mean_var_std import calculate

result = calculate([0,1,2,3,4,5,6,7,8])
print(result)

#Expected Output
{
  "mean": [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],
  "variance": [[6.0, 6.0, 6.0], [0.666, 0.666, 0.666], 6.666],
  "standard deviation": [[2.449, 2.449, 2.449], [0.816, 0.816, 0.816], 2.581],
  "max": [[6, 7, 8], [2, 5, 8], 8],
  "min": [[0, 1, 2], [0, 3, 6], 0],
  "sum": [[9, 12, 15], [3, 12, 21], 36]
}
```


# 2️⃣ Demographic Data Analyzer
## Project Description 📊
In this project, I analyze a demographic dataset using Pandas. The dataset contains information about individuals from the 1994 Census, including attributes such as age, work class, education, occupation, and income. This project aims to gain insights into various demographic factors and how they relate to income levels. Specifically, I will analyze various features to uncover patterns related to age, education, race, and income.

## The tasks given in this project are: 📝
**Determine the number of people of each race**
    - Count how many individuals belong to each race within the dataset.

**Calculate the average age of men**
    - Find and display the average age of male individuals in the dataset.

**Percentage of people with a Bachelor's degree**
    - Calculate and display the percentage of people who have completed a Bachelor's degree.
      
**Percentage of people with advanced education who earn more than 50K**
    - Identify the percentage of individuals with advanced education (Bachelor’s, Master’s, or Doctorate) who earn more than $50,000 annually.
      
**Percentage of people without advanced education who earn more than 50K**
    - Determine the percentage of individuals without advanced education who earn more than $50,000 annually.

# 3️⃣ Medical Data Visualizer

## Project Description 🩺
In this project, I visualize medical data using Python and **Matplotlib**. The dataset contains medical statistics that allow for the analysis of trends over time. The primary focus is on visualizing how different medical metrics (such as heart rate, age, weight, etc.) are distributed and correlated. The goal is to create clear and informative plots that can help understand various health metrics.

## The tasks given in this project are: 📝
- **Visualize the distribution of medical data**  
   - Create histograms and boxplots to display the distribution of key medical metrics like age and blood pressure.

- **Show correlations between variables**  
   - Use scatter plots and line graphs to explore relationships between various medical attributes.

- **Display time-series data**  
   - Implement time-series plots to show how medical metrics evolve over time.

- **Create a health metrics dashboard**  
   - Combine various visualizations into a cohesive dashboard for better insights.

---

# 4️⃣ Page View Time Series Visualizer

## Project Description 📅
In this project, I visualize a time series of page view data using **Matplotlib**. The dataset contains the number of page views over a period, which is used to analyze trends in website traffic. The main objective is to create interactive plots that allow users to explore the data and understand peak periods, growth, and fluctuations in traffic over time.

## The tasks given in this project are: 📝
- **Create a time series plot of page views**  
   - Generate a line graph that shows the trend of page views over time.

- **Highlight peak periods of activity**  
   - Use annotations and markers to highlight periods with the highest traffic.

- **Add interactive features to the plot**  
   - Allow for zooming and panning to examine specific time periods in detail.

- **Show monthly statistics**  
   - Implement plots that group data by month to show average or total page views for each month.

---

# 5️⃣ Sea Level Predictor

## Project Description 🌊
In this project, I build a predictive model for sea level rise using **linear regression**. The dataset consists of historical data on sea levels, and the goal is to predict future sea levels based on existing trends. The project helps in understanding the relationship between sea level changes and time, with a focus on projecting future values.

## The tasks given in this project are: 📝
- **Plot historical sea level data**  
   - Create a plot that shows the change in sea level over the years.

- **Fit a linear regression model**  
   - Use **SciKit-Learn** to fit a linear regression model to the historical data.

- **Make predictions for future sea levels**  
   - Predict sea levels for the next 10 years using the fitted model.

- **Visualize predictions alongside historical data**  
   - Overlay the predicted sea levels on the historical data plot for comparison.


# Technologies Used: 
  - **Python**
  - **Numpy**
  - **Pandas**
  - **Matplotlib**

