# Netflix-Content-Distribution-Analysis

![netflix-symbol-black](https://github.com/user-attachments/assets/ef940839-1d5c-4543-b035-c7f98423a2ce)


This project involves exploring and analyzing Netflix's content dataset to answer various business questions related to content distribution, genre popularity, release trends, and more. The insights derived from this analysis can help in understanding Netflix's content strategy and user preferences.


## **Table of Contents**
1. [Project Overview](#project-overview)  
2. [Dataset Description](#dataset-description)  
3. [Business Questions](#business-questions)  
4. [Tools and Technologies](#tools-and-technologies)  
5. [Analysis Steps](#analysis-steps)  
6. [Results](#results)  
7. [How to Run the Project](#how-to-run-the-project)  
8. [Future Enhancements](#future-enhancements)  
9. [Contributors](#contributors)


## **Project Overview**

Netflix is one of the largest streaming platforms, offering a wide range of movies and TV shows globally. The goal of this project is to analyze Netflix's content catalog to gain actionable insights regarding content trends, regional availability, genre popularity, and more.

## **Dataset Description**

The dataset used in this analysis contains detailed information about Netflix’s content, including:
- **Title**: Name of the movie or TV show  
- **Type**: Movie or TV Show  
- **Release Date**: Date when the title was added to Netflix  
- **Country**: Countries where the title is available  
- **Genre**: Genres associated with the content  
- **Director**: Name(s) of the director(s)  
- **Cast**: List of actors involved in the title  
- **Duration**: Duration of movies (in minutes) or number of seasons for TV shows  
- **Rating**: Age group suitability of the content  
- **Date Added**: The date when the content was added to Netflix  
- **Date Removed**: The date when the content was removed from Netflix, if applicable


## **Business Questions**

This project aims to answer the following key business questions:

1. **Regional Availability**  
   - How many movies and TV shows are available in each region?

2. **Popular Genre Analysis**  
   - What are the most popular genres based on the number of titles in each genre?

3. **Content Added Over Time**  
   - How many titles were added to Netflix each year?

4. **Frequent Actors and Directors**  
   - Who are the most frequently featured actors or directors in Netflix content?

5. **Content Distribution by Type**  
   - What is the proportion of movies versus TV shows available on Netflix?

6. **Seasonal Content Release Trends**  
   - During which months or seasons is content most frequently released?

7. **Age Group Suitability**  
   - What is the distribution of content ratings (e.g., PG, PG-13, R)?

8. **Longest-Running TV Shows**  
   - Which TV shows have the highest number of seasons or episodes?

9. **International Content Availability**  
   - Which countries contribute the highest number of titles to Netflix?

10. **Genre vs. Popularity**  
    - Which genres correlate most with high viewer ratings or popularity metrics?

11. **Expired Content Analysis**  
    - Which titles have been removed from Netflix, and what are the trends in content removal?


## **Tools and Technologies**

- **Programming Language**: Python  
- **Data Manipulation**: Pandas, NumPy  
- **Data Visualization**: Matplotlib, Seaborn  
- **Database Querying**: SQL  
- **Dashboard Creation**: Tableau / Power BI  
- **Jupyter Notebooks**: For running and documenting the analysis steps


## **Analysis Steps**

1. **Data Cleaning and Preprocessing**  
   - Handle missing values  
   - Format date fields  
   - Normalize genres, countries, and cast columns for easier analysis

2. **Exploratory Data Analysis (EDA)**  
   - Visualize key statistics (e.g., number of titles by type, region, and genre)  
   - Identify trends over time in content additions and removals  
   - Analyze actor and director frequency in the dataset

3. **Feature Engineering**  
   - Create new features (e.g., seasons count, duration in hours)  
   - Generate genre popularity metrics  
   - Categorize content based on age group suitability

4. **Data Visualization**  
   - Use various plots (bar charts, line plots, pie charts, etc.) to present insights  
   - Create interactive dashboards for content distribution and trends analysis

5. **Answer Business Questions**  
   - Apply SQL queries and Python code to extract answers to each business question


## **Results**

1. **Regional Availability**  
   - The highest number of titles is available in [Country/Region Name].  
   - TV shows are predominantly available in [Region], while movies dominate in [Region].

2. **Popular Genres**  
   - The most popular genres are [List Top Genres].  
   - [Action], [Drama], and [Comedy] are consistently popular across all regions.

3. **Content Added Over Time**  
   - There has been a steady increase in content additions since [Year].  
   - The highest number of titles was added in [Year].

_(Add brief summaries for other questions)_


## **How to Run the Project**

1. Clone this repository using:  
   ```bash
   git clone https://github.com/yourusername/netflix-content-analysis.git
   ```  
2. Install the required libraries:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Run the Jupyter Notebook for analysis:  
   ```bash
   jupyter notebook netflix_analysis.ipynb
   ```  
4. (Optional) Open the dashboard using Tableau or Power BI for interactive exploration.


## **Future Enhancements**

- Include sentiment analysis of user reviews (if available).  
- Perform clustering to identify content types that are frequently watched together.  
- Add predictive models for content popularity based on genres and regions.



## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

