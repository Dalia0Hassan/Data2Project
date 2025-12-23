# The Shorts Revolution: YouTube Engagement Analysis

An empirical analysis of how short-form video content has transformed engagement patterns on YouTube between 2012 and 2025.

## Research Question

How has the rise of short-form videos (<60 seconds) on YouTube between 2021 and 2025 affected video-level engagement metrics and the relative share of short vs. long-form content consumption? 

## Project Overview

This data science project investigates the impact of YouTube Shorts on viewer engagement by analyzing video metrics across three distinct eras: Pre-Shorts, Experimenting, and Global Shorts. The analysis reveals surprising trends in how short-form content performance has evolved since YouTube's introduction of Shorts to compete with TikTok.

## Dataset

- **Source**: YouTube recommendation dataset from Kaggle 
- **Observations**: 537 videos 
- **Variables**: 16 features 
- **Timeframe**: 2012–2025
- **Key Variables**:
  - Video duration 
  - Engagement metrics (likes, comments, views) 
  - Publication dates 
  - Content categories 

## Methodology

### Data Preprocessing
- No missing values or duplicate rows detected 
- Converted `published_at` column to datetime format and extracted year 
- Classified videos into short-form (≤60 seconds) and long-form (>60 seconds) categories 

### Statistical Methods
- Descriptive Statistics 
- Correlation Analysis 
- One-Way ANOVA for hypothesis testing 
- Post-hoc Testing 
- T-tests and Chi-Square tests 
- Simple Linear Regression 

## Key Findings

### 1. The Rise and Decline of Shorts Engagement
Short-form videos drove overall engagement growth from 2019-2024, but engagement reversed sharply in 2025, with long-form videos reclaiming the lead.

### 2. Different Engagement Patterns
- **Shorts**: Higher likes-to-views ratios, indicating more efficient passive engagement 
- **Long-form**: Substantially higher comments-to-views ratios, indicating deeper audience discussion and meaningful engagement 

### 3. Temporal Engagement Dynamics
The first week is critical for video performance across both formats, with engagement declining significantly after the initial month. The engagement gap between shorts and long-form content fluctuated from 2021-2025, ultimately favoring long-form by 2025.

## Conclusions

- Shorts dominated engagement metrics from 2021–2024, but long-form videos reclaimed the lead in 2025 
- Long-form content generates deeper audience discussion despite lower raw interaction rates 
- Despite YouTube's aggressive promotion of Shorts, engagement rates for videos under 60 seconds declined significantly in 2025 

## Limitations

### Missing Demographics Data
- Shorts may appeal specifically to younger audiences with different engagement behaviors 
- YouTube's algorithm and user base vary significantly by country 

### Selection Bias
- Dataset is based on YouTube's recommendation system 
- Results generalize well to popular, recommended content but may not apply to niche channels or emerging creators 

## Contributions

**Dalia Hassan:**
- Data Preparation and Cleaning
- Statistical Analysis
- GitHub management and Repository setup

**Salma Sameeh:**
- Research Question Formulation
- Data Visualization
- Conclusions and Discussion

*Note: Development was done collaboratively and simultaneously using Google Colab. The final version was uploaded to GitHub from one account for consolidation.*


DSCI 2410 - Fundamentals of Data Science II  
American University in Cairo  
December 9, 2025 

## Technologies Used

- Python
- Statistical analysis libraries
- Data visualization tools

---

*This project was completed as part of the DSCI 2410 course at the American University in Cairo.*
