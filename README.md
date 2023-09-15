# Tung Le - Data Analyst Portfolio
<a name="about"></a>
## About

Hi, I'm Tung! I have an analytical background in Nutritional Sciences and currently, I am on track to completing my degree in Business Analytics (MSc Business Analytics). I have developed a strong foundation in the life sciences and a passion for leveraging data to discover meaningful insights. I am excited to bring my technical and analytical skills to the domain of data analytics as a data analyst.

During my studies, I honed my ability to work with complex data and developed a keen eye for identifying patterns and trends. I also gained experience in laboratory techniques, data management, and statistical analysis, which I believe will be valuable assets in my role as a data analyst.

In my free time, I enjoy exploring new data analysis tools and techniques, always on the lookout for opportunities to expand my knowledge and enhance my skill set. Whether collaborating within a team or working independently, I am driven by the excitement of uncovering new findings and the satisfaction of using data to solve complex problems.

My CV in [pdf](TungLe_resume.pdf).

This repository serves as a platform to showcase skills, share projects and track my progress in Data Analytics / Data Science related topics.

## Table of Contents

- [About](#about)

- [Portfolio Projects](#portfolio-projects)
  - R
    - [Bikeshare Rider Volume Forecast (Machine Learning Project)](#bikeshare)
    - [Junk Removal Company Operations Analysis & Optimization](#gi-junk)
  - Excel / Google Sheets
  - [Tableau](https://public.tableau.com/app/profile/tung.le1094)
  
- Education

- Certificates

- Contact

<a name="portfolio-projects"></a>
## Portfolio Projects
In this section I will briefly list data analytics projects describing the technology stack used to solve cases.
<a name="bikeshare"></a>
### Bikeshare Rider Volume Forecast (Machine Learning Project)
**Code:** [Bikeshare Rider Volume Forecast.R](https://github.com/tungble/PortfolioProjects/blob/311a8965dc22fc60c8807f4f33a509219cff5875/Bikeshare%20Rider%20Volume%20Forecast.R)

**Goals:** 
1. Determine what factors contribute the most to ridership volume
2. Forecast ridership volume

**Description:** The project focused on analyzing a dataset of bikeshare ridership from January 2011 through December 2012. The dataset included season, holiday, workingday, weathear, temperature, humidity, windspeed, ridership type, and other relevant information. The project involved loading the data, cleaning and preprocessing it, performing exploratory data analysis (EDA), performing multivariate analysis to analyze the correlation between external factors and ridership types, and forecasting rider volume using 4 ML algorithms: linear regression, regression tree, knn regression, and ensemble learning. 

**Skills:** multivariate analysis, hypothesis testing, data cleaning, data analysis, machine learning, data visualization.

**Technology:** R, lubridate, caret, rpart, rpart.plot, Metrics.

**Results:** 
1. Multivariate analysis revealed that time is the strongest predictor of ridership, with peak hours in the early morning (7:00-9:00 AM), noon (12:00-1:00 PM), and late afternoon/evening (3:00-8:00 PM), while specific month or weekday have no significant impact.
2. Ensemble learning is the most optimal ML model for predicting rider volume, outperforming the benchmark RMSE and MAPE by a multiple of 2.5 and 10 respectively.

<a name="gi-junk"></a>
### Junk Removal Company Operations Analysis & Optimization
**Code:** [Junk Removal Company Operations Analysis & Optimization.Rmd](https://github.com/tungble/PortfolioProjects/blob/311a8965dc22fc60c8807f4f33a509219cff5875/Junk%20Removal%20Company%20Operations%20Analysis%20%26%20Optimization.Rmd)

**Goals:** 

**Description:** The project focused on analyzing a dataset of bikeshare ridership from January 2011 through December 2012. The dataset included season, holiday, workingday, weathear, temperature, humidity, windspeed, ridership type, and other relevant information. The project involved loading the data, cleaning and preprocessing it, performing exploratory data analysis (EDA), performing multivariate analysis to analyze the correlation between external factors and ridership types, and forecasting rider volume using 4 ML algorithms: linear regression, regression tree, knn regression, and ensemble learning. 

**Skills:** data cleaning, text-processing, aggreagate functions, join functions, route optimization, performance measurement, data visualization.

**Technology:** R, tidyverse, dplyr, tidyr, tidygeocoder, 

**Results:** Using ML algorithms the analysis revealed that time is the strongest predictor of ridership, with peak hours in the early morning (7:00-9:00 AM), noon (12:00-1:00 PM), and late afternoon/evening (3:00-8:00 PM), while specific month or weekday have no significant impact.
