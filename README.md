# Reddit-stress-analysis

## Overview
This project analyzes stress levels in Reddit posts using **sentiment analysis and language metrics**. The dataset is sourced from **Kaggle** and contains **2839 rows** with various trauma-related variables. The goal is to identify how linguistic and social factors influence user engagement and stress levels.

## Dataset & Variables
### **Source**
- Kaggle dataset (post-trauma related discussions on Reddit)
- **2839 rows** after data cleaning
- **17 columns** containing various linguistic and social metrics

### **Selected Variables**
- **Independent Variables:**
  - `syntax_ari` (syntactic complexity)
  - `confidence` (certainty in the text)
  - `sentiment` (positive/negative tone)
  - `lex_dal_avg` (Dictionary of Affect in Language score)
  - `social_upvote` (community approval metric)
- **Dependent Variable:**
  - `social_karma` (total engagement and response to posts)

### **Dictionary of Affect in Language (DAL)**
- DAL is a tool that **rates words based on their emotional impact**.
- It measures how **pleasant, exciting, and vivid** words are.

## Analysis & Findings
- **Statistical Modeling:** Regression analysis was performed to identify relationships.
- **Key Insights:** Higher R-square values were obtained using the selected independent variables.
- **Impact:** Sentiment and social upvotes have a strong correlation with social karma.

## Tools & Technologies
- **Python/R** for data processing and modeling
- **Statistical techniques** for regression analysis
- **Visualization libraries** for data representation

## How to Run the Analysis
1. Load the dataset (ensure proper data cleaning is applied)
2. Perform exploratory data analysis (EDA) to check distributions
3. Run regression models to determine key influencing factors

## License
This project is open-source and intended for academic and research purposes.

