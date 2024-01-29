# Film Investment Analysis

This project was completed as the final Phase 2 assessment in the Flatiron School’s Data Science Bootcamp. 

Analysis by Erin Wasserman, February 2024


# Overview

This project analyzes which types of movies generate the most revenue at the box office. Descriptive analysis of movie data sets collected from Box Office Mojo, IMBD, Rotten Tomatoes, The Movie DB, and The Numbers, will highlight specific movie characteristics that increase ROI such as, genre selection, month of the film's release, and the length/runtime of the movie. This analysis can be used by the company to make decisions on these specific movie criteria and help the company's new movie studio operate with the lowest risk in their new business endeavor.


# Business Problem

Analyzing several movie datasets can provide valuable insights that can lead to concrete business recommendations in various aspects of the film industry. When considering characteristics of a successful movie, I analyzed the movie data to identify movies with the greatest return on investment. Based on this analysis, which is explained below, I can recommend . Furthermore, below are three recommendations based on my analysis:

* **Action and/or Adventure genre movies gross higher than other genres**
* **Most successful release months are May, June, November, and December**
* **The most profitable movies are 85-125 minutes in length**

It's important to note that any business recommendations derived from data analysis should be accompanied by careful consideration of the specific context, legal and regulatory requirements, and limitations of the dataset. Additionally, these recommendations should be subject to ongoing evaluation and refinement based on updated data and emerging industry practices.


# Data Understanding

Some media databases provide public data that includes various data about historical and current films both domestically and internationally. Each database has a variety of variables some of which may match other databases. The quantity of data provided was excllent, however, the quality of these various datasets were weak.  

Overview of dataset:

   **Independent Sources:** 
   * **Internet Movie Database (IMDb)** 
   * **The Movie Database (TMDb)** 
   * **Box Office Mojo** 
   * **The Numbers**
 
   **About:** Selected film industry data reported between 1915-2020. Due to the differences in the  independent databases, when choosing variables several considerations were made:
   * **Data Relevance**
   * **Data Quantity**
   * **Data Quality**
 
   **Decision-based Variables used:**
   * **Profit/Profit Margin**
   ** **Average Domestic Gross**
   * **Movie Runtime** 
   * **Movie Release Date** 
   * **Genre of Movie**
 
   **Missing Values:** In the case of data quality, missing data were handled on a case by case basis. Some considerations made were the relative importance of the variable in a particular analysis, how much data was needed, and finally, the possibility of filling data with a central measure of tendency and the statistical implications.  


# Methodology

This project uses descriptive analytics to report film financial performance across several variables using historical and current data. This analysis organizes and uses data from a variety of datasets to alert, explore, and report trends and insights into the potential gross earnings of new films based on genre, runtime, and release date. 

There are two main sections:
<ol>
  <li>1. Data preparation
    <ol>
       <li>The steps include:

-Importing libraries
-Reading and cleaning provided data
-Dealing with missing values
-Joining datasets
<ol>
  <li>2. Visualisations and insights
    <ol>
      <li>For each characteristic:

-Conduct feature engineering where applicable
-Create visualisations
-Draw conclusions
-Provide recommendations


# Key Findings

## Profit and Profit Margin

* A strong, positive, linear association between profit and average domestic gross with a few outliers.
* The median profit is approximately 500 million US dollars.
* The median profit margin for a top 100 all-time grossing movie is approximately 85%.
* No correlation between budget and adjusted average domestic gross.

<img src="Photos/profit_analysis/domestic_gross_profit.png" alt="other_image" style="width: 1500px; height: 400px; display: block; margin: auto;">

<img src="Photos/profit_analysis/budget_profit_margin.png" alt="other_image" style="width: 1500px; height: 400px; display: block; margin: auto;">


## Genre

* The top three all-time grossing genres are Action, Adventure, and Comedy.
* Almost 40% of the 100 top grossing movies of all time fall into the top three, all-time grossing genres of Action, Adventure, and Comedy.
* More than 50% of all the movies listed are in the genre categories of Drama, Documentary, and Comedy.

<img src="Photos/genre_analysis/bubble_plot_domestic_gross_by_genre.png" alt="other_image" style="width: 1500px; height: 400px; display: block; margin: auto;">

<img src="Photos/genre_analysis/t100_percent_by_genre.png" alt="other_image" style="width: 1500px; height: 400px; display: block; margin: auto;">

<img src="Photos/genre_analysis/production_count_by_genre.png" alt="other_image" style="width: 1500px; height: 400px; display: block; margin: auto;">


## Release Date

* The most successful months are May, June, July, November, and December.
* Most movies are released on a Friday.

<img src="Photos/release_date_analysis/release_month_all.png" alt="other_image" style="width: 1500px; height: 400px; display: block; margin: auto;">

<img src="Photos/release_date_analysis/t100_release_month.png" alt="other_image" style="width: 1500px; height: 400px; display: block; margin: auto;">


## Runtime

* The average runtime is 85 minutes.
* Top grossing movies run between 85-125 minutes.
* Movies that run between 85-125 minutes have a larger adjusted average domestic gross.

<img src="Photos/runtime_analysis/runtime_minute_distribution.png" alt="other_image" style="width: 1500px; height: 400px; display: block; margin: auto;">

<img src="Photos/runtime_analysis/runtime_range_movie_count.png" alt="other_image" style="width: 1500px; height: 400px; display: block; margin: auto;">

<img src="Photos/runtime_analysis/runtime_domestic_gross.png" alt="other_image" style="width: 1500px; height: 400px; display: block; margin: auto;">


# Actionable Insights

1. Produce a movie with a runtime between 85-125 minutes.
2. Aim for a May/June or November/December release date.
3. Produce a movie with a genre of action or adventure. 
4. Plan for a budget of $50-$250 million.


# Next Steps

While providing valuable insights, the analysis acknowledges the need for further investigation to address nuances and ensure a comprehensive understanding of movie dynamics influencing financial success.

1. In-Depth Genre Analysis:
Conduct a detailed investigation into genres with zero CPI-adjusted average domestic gross. Verify the data sources and integrity, explore reasons for the absence of financial information, and determine if these genres are genuinely unprofitable or if there are data gaps.

2. Mixed-Genre Film Exploration:
Devote a segment of the analysis to understanding the influence of mixed-genre films on financial performance. This could involve categorizing movies with multiple genres and examining how these combinations contribute to box office revenue. Insights gained could refine genre-specific recommendations.

3. External Factors Impacting Release Timing:
Extend the analysis to consider external factors influencing release timing, beyond month-based trends. Factors like major ecomonmic events, holidays, or cultural phenomena may impact movie profitability. Identifying and understanding these factors can provide more nuanced recommendations for optimal release schedules.

4. Consumer Preferences and Genre Evolution:
Investigate evolving consumer preferences in movie genres over time. Analyze historical trends to identify shifts in audience interests. Understanding how genres have evolved can inform strategic decisions about genre selection/combination and potential shifts in the future.

5. Comprehensive ROI Forecasting Model:
Develop a comprehensive model that incorporates specific factors prioritized by the film company based on their staff strengths and goals. This could involve collaboration with stakeholders to identify key performance indicators (KPIs) and create a forecasting model tailored to the company's unique priorities.

These next steps aim to address identified inconsistencies, enhance the robustness of the analysis, and provide more actionable insights for the film company's decision-making processes.


# Author

Name: Erin Wasserman

GitHub: [Cellister](https://github.com/cellister)

Email address: cellister at gmail .com


# Repository Structure

* **Jupyter Notebook**

The [Jupyter Notebook](https://github.com/cellister/Film-Investment-Analysis-Project/blob/main/Film%20Investment%20Analysis%20Notebook.ipynb) is the key deliverable and contains the details of my data strategy, methodology, data cleaning, visualizations, and actionable insights.

* **Presentation**

This 5-7 minute, non-technical [presentation](...) was made in [Canva](https://www.canva.com/design/DAFzlcctuzo/YpMIvURJO6cI7aveTLrNDA/edit?utm_content=DAFzlcctuzo&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) and gives an impactful and brief overview of the key insights and recommendations. 

* **Data**

The data used in this analysis can be found in the ‘Data’ folder. Some data can be found on the [IMDb Website](https://developer.imdb.com/non-commercial-datasets/).


├── code
│   ├── __init__.py
│   ├── data_preparation.py
│   ├── visualizations.py
│   └── eda_notebook.ipynb
├── data
├── images
├── __init__.py
├── README.md
├── Film_Investment_Ananlysis_Presentation.pdf
└── Film_Investment_Analysis.ipynb
