# Project Title (Employees Job Reviews)
# Overview :
Our dataset comes from Glassdoor, a website where employees share their work experiences anonymously. Each row represents one employee review and includes details like job title, company name, employment status, location, and ratings such as overall satisfaction, work-life balance, culture, and career growth. This data helps us understand employee opinions about their workplaces and explore patterns in satisfaction, company image, and management performance across different industries.

# Problem Statement:
Between 2008 and 2021, employee satisfaction differed across sectors  food (3.32), Finance (3.67), and Education (3.94). The manager aims to identify key factors like work-life balance, culture, recommendations, and leadership approval to find industries with higher satisfaction.

# approche:
* Approach 1 – Employee Ratings Analysis
  
Compare overall satisfaction, work-life balance, recommendation rates, CEO approval scores, and culture and values across the Food, Finance, and Education sectors. Identify how leadership perception and willingness to recommend relate to overall satisfaction. Further, analyze career advancement opportunities, compensation and benefits, and senior management performance to understand their influence on employee perceptions. Evaluate sector-level differences to determine which industry provides the best overall work environment

* Approach 2 – Recommendation & Leadership
  
Next, we examined recommendation rates and CEO approval to assess how leadership quality and organizational reputation influence employee trust and loyalty.This approach highlights the link between leadership effectiveness and employee endorsement, showing whether employees are willing to recommend their company and how much confidence they have in top management. These measures reflect the broader reputation of each sector and its ability to inspire commitment among employees.

* Approach 3 – Experience & Review Type
  
Finally, we explored employee experience through anonymous vs. named reviews, along with factors such as career opportunities, benefits, senior management, and the pros/cons mentioned in reviews.This approach provides a deeper understanding of how transparency, career development, and organizational support shape satisfaction and influence how employees choose or perceive sectors. It reveals whether employees feel secure and valued enough to attach their identity to their feedback and how different industries promote growth and openness.

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
