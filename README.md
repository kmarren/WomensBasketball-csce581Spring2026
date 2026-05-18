# Predicting Division 1 Women’s Basketball Game Outcomes

### Introduction
Women's basketball is rapidly gaining popularity around the world, but has historically been under-represented in similar machine learning contexts. This provided an interesting landscape for exploring this domain. This project explores binary game outcome predictions for NCAA Division 1 Women's Basketball games during the 2025-2026 season using random forest and logistic regression.

### Data
The data set for this project was procured from sports-reference.com. The women's basketball data set initially features game data including in-game statistics such as points, field goal percentage, three point percentage, free throw percentage, and more. Early models exhibited uncharacteristically high performance, which indicated that game statistics are correlated with game outcome. As a result the data was reformatted to only include information that is available before the game, eliminates leakage, and is relevant to team performance.
