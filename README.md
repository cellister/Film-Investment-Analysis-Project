# Film Investment Analysis

This project was completed as the final Phase 2 assessment in the Flatiron School’s Data Science Bootcamp.

# Overview



# Business Problem

Analyzing several movie datasets can provide valuable insights that can lead to concrete business recommendations in various aspects of the film industry. When considering characteristics of a successful movie, I analyzed the movie data to identify movies with the greatest return on investment. Based on this analysis, which is explained below, I can recommend . Furthermore, below are three recommendations based on my analysis:

* **Action and/or Adventure genre movies gross higher than other genres**
* **Most successful release months are June, July, November, and December**
* **The most profitable movies are 85-125 minutes in length**

It's important to note that any business recommendations derived from data analysis should be accompanied by careful consideration of the specific context, legal and regulatory requirements, and limitations of the dataset. Additionally, these recommendations should be subject to ongoing evaluation and refinement based on updated data and emerging industry practices.

* **Jupyter Notebook**

The [Jupyter Notebook](https://github.com/cellister/Film-Investment-Analysis-Project/blob/main/Film%20Investment%20Analysis%20Notebook.ipynb) is the key deliverable and contains the details of my data strategy, methodology, data cleaning, visualizations, and actionable insights.

* **Presentation**

This 5-7 minute, non-technical [presentation](...) was made in [Canva](https://www.canva.com/design/DAFzlcctuzo/YpMIvURJO6cI7aveTLrNDA/edit?utm_content=DAFzlcctuzo&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) and gives an impactful and brief overview of the key insights and recommendations. 

* **Data**

The data used in this analysis can be found in the ‘Data’ folder. Some data can be found on the [IMDb Website](https://developer.imdb.com/non-commercial-datasets/).


# Data Understanding

Some media databases provide public data that includes various data about historical and current films both domestically and internationally. Each database has a variety of variables some of which may match other databases. The quantity of data provided was excllent, however, the quality of these various datasets were weak.  

Overview of dataset:

   **Independent Sources:** 
   * **Internet Movie Database (IMDb)** 
   * **The Movie Database (TMBd)** 
   * **Box Office Mojo** 
   * **The Numbers**
 
   **About:** Selected film industry data reported between 1915-2020. Due to the differences in the independent databases, when choosing variables several considerations were made:
   * **Data Relevance**
   * **Data Quantity**
   * **Data Quality**
 
   **Decision-based Variables used:** 
   * **Movie Runtime** 
   * **Movie Release Date** 
   * **Genre of Movie**
 
   **Missing Values:** In the case of data quality, missing data were handled on a case by case basis. Some considerations made were the relative importance of the variable in a particular analysis, how much data was needed, and finally, the possibility of filling data with a central measure of tendency and the statistical implications.  

# Methods

This project uses descriptive analytics to report film financial performance across several variables using historical and current data. This analysis organizes and uses data from a variety of datasets to alert, explore, and report trends and insights into the potential gross earnings of new films based on genre, runtime, and release date. 

There are two main sections:

1. Data preparation
The steps include:

Importing libraries
Reading and cleaning provided data
Dealing with missing values
Joining datasets

2. Visualisations and insights
For each characteristic:

Conduct feature engineering where applicable
Create visualisations
Draw conclusions
Provide recommendations

# Key Findings

## Profit and Profit Margin

## Genre

## Release Date

## Runtime

# Actionable Insights



# Author

Name: Erin Wasserman

GitHub: [Cellister](https://github.com/cellister)

Email address: cellister at gmail .com


├── code
│   ├── __init__.py
│   ├── data_preparation.py
│   ├── visualizations.py
│   └── eda_notebook.ipynb
├── data
├── images
├── __init__.py
├── README.md
├── Animal_Shelter_Needs_Presentation.pdf
└── animal_shelter_needs_analysis.ipynb
