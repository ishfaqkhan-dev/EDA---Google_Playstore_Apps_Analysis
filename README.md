# Google Play Store Apps Exploratory Data Analysis

## Introduction
The Google Play Store hosts millions of Android apps across diverse categories. This project focuses on analyzing a Kaggle dataset of Play Store apps to explore ratings, installs, reviews, and categories. The aim is to identify what drives app popularity and quality, and to provide useful insights for developers and researchers.

## Dataset
The dataset contains details such as:
- App name  
- Category  
- Rating  
- Number of reviews  
- Install counts  
- Size  
- Price  
- App type (free or paid)  
- Content rating  

Source: [Google Play Store Apps Dataset on Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

## Data Cleaning
Several issues were addressed before analysis:
- Converted `Reviews`, `Installs`, and `Price` into numeric format.  
- Standardized app `Size` into megabytes.  
- Handled missing values by filling with mean, median, or mode.  
- Removed 483 duplicate rows and dropped incomplete records.  
- Final dataset shape: **10,347 rows**.  

## Analysis
The analysis included:

### 1. Dataset Overview
- Descriptive statistics, unique values, and data types.  

### 2. Exploratory Data Analysis
- Distribution of ratings, reviews, installs, and app sizes.  
- Average ratings by category.  
- App type and content rating distribution.  
- Top apps by installs and reviews.  

### 3. Outlier Detection
- Boxplots for price, size, installs, and reviews to identify unusual values.  

### 4. Correlation Analysis
- Explored relationships between numerical features like reviews, installs, price, and rating.  

## Key Insights
- Free apps dominate the Play Store and gather far more installs compared to paid apps.  
- Categories like Games, Communication, and Tools have the highest number of apps.  
- Ratings are generally high across most categories, but reviews and installs are heavily skewed.  
- Duplicate entries existed for popular apps like Instagram and Facebook, which were cleaned for analysis.  

## Final Thoughts
The Play Store dataset analysis shows how app type, category, and installs shape the success of apps. The findings can guide app developers in understanding user engagement and category trends, while also highlighting the importance of data cleaning for accurate insights.

