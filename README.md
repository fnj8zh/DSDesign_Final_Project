# DSDesign_Final_Project
### A Data-Driven Upset Model for NCAA March Madness (2013–2024)
This project explores the statistical liklihood of "Cinderella" teams, which are low-seeded (11-16) NCAA men's tournament teams, that defy the odds to reach the Sweet 16. By analyzing over a decade of tournament data, I developed the Cinderella Grade, a predictive metric designed to identify potential bracket-busters to watch out for in the tournament. 

### Project Overview
The data for this project is available here: https://www.kaggle.com/datasets/andrewsundberg/college-basketball-dataset
By analyzing over 307 tournament teams, I isolated the low-seeded teams to determine the specific performance metrics that separate teams that make surprising tournament runs from typical first-round exits.

#### Key Features
* Statistical normalization: Used Z-score standardization to compare teams across various metrics throughout their season, such as offensive efficiency, games played, etc. 
* Feature engineering: I then used a heatmap and other exploratory data analysis to determine which variables have the highest impact in determining a low-seeded team's performance while filtering out the noise. 
* Cinderella grade: A custom feature that scores a team on a scale of 1-100 based on "Cinderella" run likelihood. This grade is formed from aggregating and weighting team strength, efficiency, and "bubble" performance into a single predictive score.
* Infographic: I created an infographic in a Jupyter notebook titled "Final Product.ipynb" along with a project resource manifest and an in-depth project description. 
