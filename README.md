# IMDb Movies Dataset Analysis

## Introduction

This project involves the analysis of the IMDb (The Movie Database) Movies Dataset. This dataset contains information about thousands of movies released since 1960. The primary objective of this analysis is to explore and gain insights into various aspects of the movie industry, such as revenue trends over the years and the actors who have played the most lead roles.

## Project Structure

The project is structured as follows:

1. **Data Wrangling:** In this section, I prepared the data for analysis. I loaded the dataset, removed unnecessary columns, and handled missing values. 

2. **Exploratory Data Analysis:** This section focuses on exploring the data and answering the research questions.

3. **Conclusions:** Here, I summarize the findings from the analysis and provide conclusions based on the results.

## Tools Used

I utilized the following Python libraries for this analysis:

- NumPy: For numerical operations and calculations.
- Pandas: For data manipulation and analysis.
- Matplotlib: For data visualization.

## Research Questions

### Research Question 1: Average Revenue of Movies Over the Years

I explored the trend in average movie revenue over the years. To do this, I calculated the mean revenue for each year and visualized the results using a line plot.

### Research Question 2: Which Actors Had the Most Lead Roles?

To identify the actors with the most lead roles, I parsed the "cast" column and separated actors by "|". I then counted the occurrences of actors in lead roles and co-starring roles, presenting the top actors in each category.

## Key Findings

- The analysis of average movie revenue over the years showed a general upward trend since 1960. However, it's important to note that this analysis does not account for inflation or other factors that could affect revenue trends.

- In terms of lead roles, Nicholas Cage emerged as the actor with the most lead roles, having appeared as the lead in 37 movies. Notably, there was a significant gender imbalance in this analysis, with no female lead actors appearing in the top ten.

- In contrast, the actor Gene Hackman led the way in co-starring roles, tying with Jennifer Aniston and Morgan Freeman, each appearing in 13 movies as co-stars.

## Conclusion

This data analysis project provided insights into the IMDb Movies Dataset, focusing on revenue trends and prominent lead actors. While the findings are informative, it's essential to remember that further research and analysis are required to draw more definitive conclusions.

Feel free to explore the code and analysis notebooks for more details on the methodology and specific findings.
