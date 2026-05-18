# Predicting Division 1 Women’s Basketball Game Outcomes

### Introduction
Women's basketball is rapidly gaining popularity around the world, but has historically been under-represented in similar machine learning contexts. This provided an interesting landscape for exploring this domain. This project explores binary game outcome predictions for NCAA Division 1 Women's Basketball games during the 2025-2026 season using random forest and logistic regression.

### Data
The data set for this project was procured from sports-reference.com, and was concatenated with a data set from warrennolan.com which provided strength of schedule metrics for each team.
The final data set contains 6024 games, with the following features:

- Team
- Team win percentage before date
- Team games played before date
- Team strength of schedule
  
- Opponent
- Opponent win percentage before date
- Opponent games played before date
- Opponent strength of schedule

### Evaluation
Random forest and logistic regression were benchmarked for performance in comparison with an LLM, and both LIME and SHAP were used to explain results on multiple test cases. 

### Contents
- Code/WomensBasketballGamePrediction.ipynb
  - Project code for random forest, logistic regression, and explanations
- Data/Basketball.cvs and Data/Basketball-SOS.cvs
  - Division 1 womens basketball game data with and without strength of schedule features, respectively
- Report/ProjectReport.pdg
  - Report with more information on methods and results
- csce581-project-KennedyMarren.pptx.pdf
  - Presentation slides
