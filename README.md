# Instructor Effectiveness Modeling

## Problem Statement
Built an ML model to predict instructor effectiveness tiers 
(Low/Medium/High) for an EdTech platform using learner outcome, 
engagement and feedback data.

## Dataset
- 2000 batch-level records
- 120 unique instructors
- 25 courses

## Approach
1. Exploratory Data Analysis
2. Defined custom Instructor Effectiveness Score
3. Aggregated batch data to instructor level
4. Built Random Forest Classifier
5. Achieved 92% accuracy and 0.89 cross-validation F1 score

## Key Findings
- Completion rate and dropout rate are the strongest 
  predictors of instructor effectiveness
- Score improvement confirms actual learning happened

## Libraries Used
pandas, numpy, scikit-learn, matplotlib, seaborn
