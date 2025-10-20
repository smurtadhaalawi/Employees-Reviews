# Project Title (Employees Job Reviews)
# Overview :
Our dataset comes from Glassdoor, a website where employees share their work experiences anonymously. Each row represents one employee review and includes details like job title, company name, employment status, location, and ratings such as overall satisfaction, work-life balance, culture, and career growth. This data helps us understand employee opinions about their workplaces and explore patterns in satisfaction, company image, and management performance across different industries.

# Problem Statement:
Between 2008 and 2021, overall employee satisfaction varied significantly across sectors. Reviews show that the Food sector scored only 3.32/5, lagging behind Finance (3.67/5) and Education (3.94/5). A manager exploring job opportunities wants to understand why satisfaction differs across these sectors, focusing on work-life balance, culture, recommendation rates, and leadership approval to identify industries with higher employee satisfaction.

# approche:
* Approach 1 – Employee Ratings Analysis
  
Compare overall satisfaction, work-life balance, recommendation rates, CEO approval scores, and culture and values across the Food, Finance, and Education sectors. Identify how leadership perception and willingness to recommend relate to overall satisfaction. Further, analyze career advancement opportunities, compensation and benefits, and senior management performance to understand their influence on employee perceptions. Evaluate sector-level differences to determine which industry provides the best overall work environment

* Approach 2 – Job Title Analysis for Business Management Graduates
  
Identify the most suitable job titles for jobseekers with a Business Management degree by analyzing employee ratings across sectors. This approach examines how employees in various roles within the Food, Finance, and Education sectors rate factors such as overall satisfaction, career growth, compensation, and management support. By comparing these ratings, the analysis determines which job titles offer the most favorable work experiences and long-term opportunities for Business Management graduates. The goal is to highlight the best-rated positions and sectors for career development, as well as to uncover patterns in job satisfaction and professional advancement potential across industries.

* Approach 3 – Cross-Sector Pros and Cons Text Analysis

Identify the common strengths and weaknesses across all sectors by analyzing the written pros and cons provided by employees in their reviews. This approach uses text analysis to extract frequently mentioned themes that reflect positive and negative aspects of working in the Food, Finance, and Education sectors.

# Dataset: 
Columns: 18

Rows: 839k

You can find the Data in the 
[Website](https://www.kaggle.com/datasets/davidgauthier/glassdoor-job-reviews/data)

# Analysis: 
The analysis compares employee satisfaction across the Education, Finance, and Food sectors by examining key rating dimensions such as overall rating, work-life balance, culture, career growth, compensation, management, recommendation, and CEO approval. After cleaning and filtering the data, average scores are calculated and compared across sectors using descriptive statistics and visualizations. Statistical tests such as ANOVA are used to assess whether the differences are significant. The findings help identify the best-performing sector in terms of overall employee satisfaction, while also revealing common strengths and weaknesses shared across industries, highlighting the key pros and cons that shape employee experiences in each sector.

# How to Run: 
download the Data from website, Then open the data in python by :

     reviews_csv='glassdoor_reviews.csv'
     reviews_df=pd.read_csv(reviews_csv)

# Dependencies: 
* import pandas as pd
* from collections import Counter
* import re
* import seaborn as sns
* import numpy as np
* import matplotlib.pyplot as plt
* from IPython.display import display
